##What does it do ?
This script run sa-learn on a spam directory and on a ham directory, then mail
the output with some stats (number of learned spam, ham and tokens)

##How to use it ?
Put the script somewhere, create a configuration file and run the script
directly or from a crontab. See salar -h for more infos.

Example for cron, in /etc/cron.d/salar:

```bash
42 2 * * * root /usr/local/bin/salar
```

##Dependancies
Well, sa-learn and that's all !
