# Jenkins Backup Automation (Real World)

This repo shows how to back up Jenkins config using `rsync` + `cronjob`.

## Problem
If Jenkins server crashes, configuration is lost.

## Solution
1. Rsync to backup Jenkins dir to remote server (Kali)
2. Restore from backup to another server in case of failure

## Files
- backup-script.sh – rsync command
- crontab.txt – Daily cron setup

## Preview
![screenshot](screenshots/terminal-output.png)
