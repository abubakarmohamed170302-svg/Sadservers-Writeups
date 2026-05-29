# saskatoon.md

# SadServers — Saskatoon 🛠️

## Scenario

The objective of this challenge was to troubleshoot Linux system issues and investigate server behaviour using command-line tools.

This lab focused on:

* Linux troubleshooting
* networking diagnostics
* process monitoring
* log analysis
* system administration

---

# Initial System Investigation

The first step was identifying active processes and system usage.

## Command Used

```bash id="sk1jlwm"
ps aux
```

### Purpose

Displays:

* running processes
* process owners
* CPU usage
* memory usage
* process IDs (PIDs)

---

# Monitoring System Performance

Used `top` to inspect live resource usage.

## Command Used

```bash id="sk2jlwm"
top
```

### Purpose

Shows:

* CPU usage
* memory usage
* active tasks
* system load

Useful for identifying:

* high CPU processes
* memory leaks
* overloaded services

---

# Filtering Processes

Used `grep` to search for specific services.

## Example

```bash id="sk3jlwm"
ps aux | grep apache
```

### Purpose

Filters:

* running services
* web servers
* suspicious processes

---

# Investigating Network Connections

Checked active ports and services.

## Command Used

```bash id="sk4jlwm"
ss -tulnp
```

### Purpose

Displays:

* listening ports
* TCP/UDP services
* active network connections

---

# Checking Open Files

Used `lsof` to identify active file usage.

## Command Used

```bash id="sk5jlwm"
lsof
```

### Purpose

Shows:

* open files
* active services
* network connections
* processes using resources

---

# Monitoring Logs

Linux logs are important for troubleshooting.

## Command Used

```bash id="sk6’wini"
tail -f /var/log/syslog
```

### Purpose

Monitors:

* system logs
* service errors
* warnings
* troubleshooting information

---

# Disk Usage Investigation

Checked filesystem usage.

## Command Used

```bash id="sk7’wini"
df -h
```

### Purpose

Displays:

* disk usage
* storage capacity
* mounted filesystems

---

# Investigating Directory Sizes

Used `du` to identify large folders.

## Command Used

```bash id="sk8’wini"
du -sh *
```

### Purpose

Shows:

* folder sizes
* storage consumption
* large directories

---

# Stopping Problematic Processes

Used `kill` to stop problematic services.

## Example

```bash id="sk9’wini"
kill PID
```

Replace:

* `PID` with actual process ID.

---

# Key Linux Skills Practiced

* Linux troubleshooting
* process investigation
* system monitoring
* networking diagnostics
* disk usage analysis
* log analysis

---

# Important Commands Learned

| Command     | Purpose                  |
| ----------- | ------------------------ |
| `ps aux`    | view running processes   |
| `top`       | monitor system resources |
| `grep`      | filter output            |
| `ss -tulnp` | inspect network services |
| `lsof`      | list open files          |
| `df -h`     | check disk usage         |
| `du -sh`    | analyze directory sizes  |
| `tail -f`   | monitor logs live        |
| `kill`      | stop running processes   |

---

# What This Lab Taught

This challenge improved:

* Linux troubleshooting skills
* command-line investigation
* debugging techniques
* server monitoring
* problem-solving confidence

These skills are highly valuable in:

* DevOps
* cloud engineering
* Linux administration
* infrastructure management
