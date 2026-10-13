# Checkpoint 6 - Backup Script Guide

## 1. Backup Script Code

```bash
#!/bin/bash
# Automated Backup Script for CloudNova Technologies
SOURCE_DIR="app-data"
BACKUP_DIR="backups"
TIMESTAMP=$(date +"%Y%m%d_%H%M%S")
echo "Initiating automated backup..."
mkdir -p $BACKUP_DIR
tar -czf $BACKUP_DIR/backup_$TIMESTAMP.tar.gz $SOURCE_DIR
echo "Backup completed successfully at $TIMESTAMP!"
```

## 2. File Permissions

The `chmod +x backup.sh` command grants executable permission to the script. This allows the user to run it directly from the terminal using `./backup.sh`.

## 3. Cron Job Configuration

```cron
0 2 * * * /root/backup.sh
```

## Explanation of the Five Cron Fields\

The Cron job automatically runs the backup script every night at 2:00 AM, reducing the need for manual intervention.

| Field        | Value | Meaning                      |
| ------------ | ----- | ---------------------------- |
| Minute       | `0`   | Runs at minute zero.         |
| Hour         | `2`   | Runs at 2:00 AM.             |
| Day of Month | `*`   | Runs every day of the month. |
| Month        | `*`   | Runs every month.            |
| Day of Week  | `*`   | Runs every day of the week.  |