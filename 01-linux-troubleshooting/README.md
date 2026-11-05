# Linux Production Server Health Check

## Objective
Perform a basic health check of a Linux server, similar to daily checks performed by an SRE or DevOps Engineer in a production environment.

## Scenario
As an SRE Engineer, you are responsible for monitoring Linux production servers. You need to verify CPU, memory, disk usage, uptime and running processes to identify potential infrastructure issues.

## Tasks and Linux Commands

### 1. Check Server Uptime
```bash
uptime
```

### 2. Check CPU and Running Processes
```bash
top
```

### 3. Check Memory Utilization
```bash
free -h
```

### 4. Check Disk Utilization
```bash
df -h
```

### 5. Check Disk and Directory Size
```bash
du -sh /var/log
```

### 6. Check Running Services
```bash
systemctl --type=service --state=running
```

### 7. Check System Load
```bash
uptime
```

## Expected Outcome
- Identify high CPU utilization.
- Identify memory usage and available memory.
- Identify disk space utilization.
- Check server uptime and load average.
- Verify important running services.

## Learning Outcome
Understand basic Linux server monitoring and troubleshooting activities performed by SRE and DevOps Engineers.

## Status
Documentation created. Practical command execution and results will be added after completing the hands-on exercise.
