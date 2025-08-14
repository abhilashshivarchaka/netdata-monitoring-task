<<<<<<< HEAD
# netdata-monitoring-task
=======
# Netdata Monitoring - Data Analyst Internship Task 7

## Objective
To install and use Netdata for real-time monitoring of system and application performance.

## Steps Performed
1. Pulled and ran Netdata via Docker:
   ```bash
   docker run -d --name=netdata -p 19999:19999 --cap-add SYS_PTRACE --security-opt apparmor=unconfined netdata/netdata
13b595e (Netdata Monitoring Task 7)
