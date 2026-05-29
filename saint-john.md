# SadServers — Saint John 🛠️

## Scenario

The objective of this challenge was to investigate a Linux system experiencing issues and identify the root cause using Linux troubleshooting commands.

This lab focused on:

* process investigation
* system monitoring
* troubleshooting techniques
* Linux administration fundamentals

---

# Initial Investigation

The first step was checking running processes.

## Command Used

```bash id="sj1jlwm"
ps aux
```

### Purpose

Displays:

* running processes
* CPU usage
* memory usage
* process owners
* process IDs (PIDs)

---

# Filtering Processes

To narrow results, `grep` was used.

## Command Used

```bash id="sj2jlwm"
ps aux | grep nginx
```

### Purpose

Searches for:

* nginx processes
* suspicious services
* running applications

---

# Investigating Open Files

Used `lsof` to identify open files and active processes.

## Command Used

```bash id="sj3jlwm"
lsof
```

### Purpose

Shows:

* open files
* active network connections
* processes using resources

---

# Checking System Resources

Used `top` to monitor live system usage.

## Command Used

```bash id="sj4jlwm"
top
```

### Purpose

Displays:

* CPU usage
* memory usage
* active processes
* system load

---

# Network Investigation

Checked listening ports and active services.

## Command Used

```bash id="sj5jlwm"
ss -tulnp
```

### Purpose

Displays:

* listening ports
* active services
* TCP/UDP connections

---

# Investigating Logs

Linux logs help identify system problems.

## Example Command

```bash id="sj6jlwm"
tail -f /var/log/syslog
```

### Purpose

Monitors:

* system logs
* errors
* service failures
* troubleshooting information

---

# Killing Problematic Processes

Used `kill` to stop problematic processes.

## Example

```bash id="sj7jlwm"
kill PID
```

Replace:

* `PID` with actual process ID.

---

# Key Linux Skills Practiced

* process investigation
* system monitoring
* networking diagnostics
* log analysis
* troubleshooting
* Linux administration

---

# Important Commands Learned

| Command     | Purpose                  |
| ----------- | ------------------------ |
| `ps aux`    | view running processes   |
| `grep`      | filter output            |
| `lsof`      | list open files          |
| `top`       | monitor system usage     |
| `ss -tulnp` | inspect networking ports |
| `tail -f`   | monitor logs live        |
| `kill`      | stop processes           |

---

# What This Lab Taught

This challenge improved:

* Linux troubleshooting skills
* process investigation
* debugging techniques
* command-line confidence

These skills are essential for:

* DevOps
* cloud engineering
* Linux administration
* server management
