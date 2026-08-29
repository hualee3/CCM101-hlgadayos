# Infrastructure Report

## Operating System

| Attribute | Value |
|---|---|
| Name | Ubuntu |
| Version | 24.04.4 LTS (Noble Numbat) |
| ID | ubuntu |
| ID Like | debian |

Command used: `cat /etc/os-release`

---

## Kernel Version

| Attribute | Value |
|---|---|
| Kernel Version | 6.8.0-138-generic |

Command used: `uname -r`

---

## CPU Model

| Attribute | Value |
|---|---|
| Architecture | x86_64 |
| CPU op-mode(s) | 32-bit, 64-bit |
| Vendor ID | GenuineIntel |
| Model name | Intel Xeon E312xx (Sandy Bridge, IBRS update) |
| CPU family | 6 |
| Model | 42 |
| Thread(s) per core | 1 |
| Core(s) per socket | 1 |
| Socket(s) | 1 |
| BogoMIPS | 7391.99 |
| Virtualization | full (KVM) |

Command used: `lscpu`

---

## Number of CPU Cores

| Attribute | Value |
|---|---|
| CPU Core Count | 1 |

Command used: `nproc`

---

## Total RAM

| Type | Total | Used | Free | Shared | Buff/Cache | Available |
|---|---|---|---|---|---|---|
| Mem | 1.9Gi | 415Mi | 837Mi | 1.1Mi | 818Mi | 1.5Gi |
| Swap | 1.0Gi | 0B | 1.0Gi | — | — | — |

Command used: `free -h`

---

## Disk Capacity

| Filesystem | Size | Used | Avail | Use% | Mounted on |
|---|---|---|---|---|---|
| tmpfs | 191M | 996K | 190M | 1% | /run |
| /dev/vda1 | 19G | 5.4G | 13G | 30% | / |
| tmpfs | 952M | 84K | 952M | 1% | /dev/shm |
| tmpfs | 5.0M | 0 | 5.0M | 0% | /run/lock |
| /dev/vda16 | 881M | 117M | 703M | 15% | /boot |
| /dev/vda15 | 105M | 6.2M | 99M | 6% | /boot/efi |

Command used: `df -h`

---

## Mounted File Systems

| Device/Source | Mount Point | Type | Notable Options |
|---|---|---|---|
| sysfs | /sys | sysfs | rw,nosuid,nodev,noexec,relatime |
| proc | /proc | proc | rw,nosuid,nodev,noexec,relatime |
| udev | /dev | devtmpfs | rw,nosuid,relatime |
| devpts | /dev/pts | devpts | rw,nosuid,noexec,relatime |
| tmpfs | /run | tmpfs | rw,nosuid,nodev,noexec,relatime |
| /dev/vda1 | / | ext4 | rw,relatime,discard,errors=remount-ro |
| tmpfs | /dev/shm | tmpfs | rw,nosuid,nodev,inode64 |
| tmpfs | /run/lock | tmpfs | rw,nosuid,nodev,noexec,relatime |
| cgroup2 | /sys/fs/cgroup | cgroup2 | rw,nosuid,nodev,noexec,relatime |
| /dev/vda16 | /boot | ext4 | rw,relatime |
| /dev/vda15 | /boot/efi | vfat | rw,relatime,fmask=0077,dmask=0077 |

Command used: `mount` / `findmnt`

---

## Hostname

| Attribute | Value |
|---|---|
| Hostname | ubuntu |

Command used: `hostname`

---

## IP Address

| Attribute | Value |
|---|---|
| IP Address(es) | 172.30.1.2, 172.17.0.1 |

Command used: `hostname -I`