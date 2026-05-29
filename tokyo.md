# SadServers — Tokyo 🛠️

## Scenario

This challenge focused on process investigation and Linux service troubleshooting.

The goal was to:

* identify problematic services
* monitor processes
* inspect logs
* troubleshoot system behaviour

---

# Investigating Processes

## Command Used

```bash
ps aux
```

### Purpose

Displays:

* active processes
* CPU usage
* memory usage
* process owners

---

# Filtering Specific Services

## Example

```bash
ps aux | grep apache
```

### Purpose

Searches for:

* web services
* background processes
* suspicious activity

---

# Monitoring System Resources

## Command Used

```bash
top
```

### Purpose

Displays:

* CPU usage
* memory usage
* active tasks
* system load

---

# Monitoring Logs

## Command Used

```bash
tail -f /var/log/syslog
```

### Purpose

Monitors:

* live logs
* service failures
* Linux errors

---

# Investigating Ports

## Command Used

```bash
ss -tulnp
```

### Purpose

Shows:

* listening ports
* network services
* TCP/UDP connections

---

# Killing Problematic Processes

## Example

```bash
kill PID
```

### Purpose

Stops problematic services or stuck processes.

---

# Key Skills Practiced

* process investigation
* Linux troubleshooting
* system monitoring
* networking diagnostics
* service debugging

---

# Important Commands Learned

| Command     | Purpose           |
| ----------- | ----------------- |
| `ps aux`    | inspect processes |
| `grep`      | filter output     |
| `top`       | monitor resources |
| `ss -tulnp` | inspect ports     |
| `tail -f`   | monitor logs      |
| `kill`      | stop processes    |

---

# What This Lab Taught

This challenge improved:

* troubleshooting confidence
* Linux administration skills
* process investigation
* debugging techniques
