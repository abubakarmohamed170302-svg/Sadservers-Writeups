# SadServers — Jakarta 🛠️

## Scenario

This challenge focused on troubleshooting networking and connectivity issues on a Linux server.

The objective was to:

* identify network problems
* inspect active ports
* verify services
* troubleshoot connectivity

---

# Checking Network Interfaces

## Command Used

```bash
ip a
```

### Purpose

Displays:

* IP addresses
* network interfaces
* interface states

---

# Testing Connectivity

## Command Used

```bash
ping google.com
```

### Purpose

Checks:

* internet connectivity
* DNS resolution
* network communication

---

# Investigating Open Ports

## Command Used

```bash
ss -tulnp
```

### Purpose

Shows:

* listening ports
* active services
* TCP/UDP connections

---

# Checking Running Processes

## Command Used

```bash
ps aux
```

### Purpose

Displays:

* running processes
* CPU usage
* memory usage

---

# Filtering Processes

## Example

```bash
ps aux | grep nginx
```

### Purpose

Searches for:

* web servers
* active services
* suspicious processes

---

# Investigating Logs

## Command Used

```bash
tail -f /var/log/syslog
```

### Purpose

Monitors:

* system logs
* networking errors
* service failures

---

# Key Skills Practiced

* Linux networking
* troubleshooting
* process investigation
* log analysis
* service diagnostics

---

# Important Commands Learned

| Command     | Purpose                 |
| ----------- | ----------------------- |
| `ip a`      | show network interfaces |
| `ping`      | test connectivity       |
| `ss -tulnp` | inspect ports           |
| `ps aux`    | view processes          |
| `grep`      | filter output           |
| `tail -f`   | monitor logs            |

---

# What This Lab Taught

This challenge improved:

* networking diagnostics
* Linux troubleshooting
* command-line investigation
* system administration confidence
