# SadServers — Melbourne 🛠️

## Scenario

This challenge focused on investigating disk usage and identifying storage-related issues on a Linux system.

---

# Checking Disk Usage

## Command Used

```bash
df -h
```

### Purpose

Displays:

* filesystem usage
* storage capacity
* mounted disks

---

# Investigating Directory Sizes

## Command Used

```bash
du -sh *
```

### Purpose

Shows:

* folder sizes
* large directories
* storage consumption

---

# Finding Large Files

## Command Used

```bash
find / -type f -size +100M 2>/dev/null
```

### Purpose

Searches for:

* large files
* storage-heavy data
* unnecessary files

---

# Monitoring Processes

## Command Used

```bash
top
```

### Purpose

Displays:

* CPU usage
* memory usage
* active processes

---

# Investigating Open Files

## Command Used

```bash
lsof
```

### Purpose

Shows:

* open files
* active processes
* resource usage

---

# Monitoring Logs

## Command Used

```bash
tail -f /var/log/syslog
```

### Purpose

Helps identify:

* storage warnings
* system errors
* service failures

---

# Key Skills Practiced

* disk usage analysis
* Linux troubleshooting
* filesystem investigation
* system monitoring

---

# Important Commands Learned

| Command   | Purpose              |
| --------- | -------------------- |
| `df -h`   | check disk usage     |
| `du -sh`  | analyze folder sizes |
| `find`    | search files         |
| `top`     | monitor system usage |
| `lsof`    | inspect open files   |
| `tail -f` | monitor logs         |

---

# What This Lab Taught

This challenge improved:

* Linux administration
* troubleshooting skills
* storage analysis
* debugging confidence
