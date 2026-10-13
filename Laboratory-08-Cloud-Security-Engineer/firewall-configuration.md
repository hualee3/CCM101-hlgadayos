# Checkpoint 6 - Firewall Configuration

## Command Used to Allow SSH

```bash
sudo ufw allow ssh
```

## Commands Used to Set the Default Deny Policy

```bash
sudo ufw default deny incoming
sudo ufw default allow outgoing
sudo ufw enable
sudo ufw status verbose
```

## Command Used to Allow Port 8080

```bash
sudo ufw allow 8080/tcp
```

## What If `ufw enable` Ran Before `ufw allow ssh`?

If the firewall were enabled before allowing SSH, incoming SSH connections could be blocked, potentially locking the administrator out of the server.