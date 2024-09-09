# Managing ECCO nodes on BioHPC

The scripts here scavenge free nodes, add them to the SLURM scheduler where possible. The scripts can be run manually, or through a cron job.

## Adding the scripts to crontab

```bash
crontab  crontab.master
```