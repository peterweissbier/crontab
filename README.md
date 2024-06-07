## installation

download and install either from aur https://archlinux.org/packages/extra/x86_64/cronie/ or for other distros on github https://github.com/cronie-crond/cronie/

sudo systemctl enable chronie

## docker webUI

https://github.com/alseambusher/crontab-ui

## script example

@reboot ( sleep 90 ; sh /location/script.sh )

## resources

https://www.baeldung.com/linux/tag/cron
https://www.baeldung.com/linux/cron-jobs-path
https://www.baeldung.com/linux/cron-files-backup
https://www.baeldung.com/linux/load-env-variables-in-cron-job
