# System Health Check Script

This repository contains a simple shell script to monitor system health.  
It checks CPU usage, memory usage, disk space, and logs the results to `health.log`.

## Features
- Monitors top 5 CPU‑hungry processes
- Monitors top 5 memory‑hungry processes
- Logs system health status to `health.log`
- Easy to extend with alerts or automation

## Usage
1. Clone the repository:
   ```bash
   git clone git@github.com:<your-username>/<repo>.git
   cd <repo>

2. Run the script:
  ./health_check.sh
   
3.Check the log file
   cat health.log
