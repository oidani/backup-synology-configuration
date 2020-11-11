### Script to backup Synology NAS configuration to a file and store it on NetBackup folder, located at:
- GUI: File Station --> NetBackup
- CLI: /volume1/NetBackup/

Output example file: synology01_20200722.dss

### OBS: you can store the configuration file in any local or remote folder mounted on your Synology NAS, just remember to change the "--filepath" parameter.

You can schedule it by doing:
- GUI schedule: Log on to Synology NAS via Web --> Control Panel --> Task Scheduler --> Create --> Scheduled Task --> User-defined script
- CLI schedule: Log on to Synology NAS via SSH --> use Linux cron
