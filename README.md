## installation

arch based distros download from aur https://archlinux.org/packages/extra/x86_64/cronie/ 

or for other distros download from github https://github.com/cronie-crond/cronie/

enable the service

sudo systemctl enable chronie

## [optional webUI hosted on docker or installed locally via npm](https://github.com/alseambusher/crontab-ui)

## script example

@reboot ( sleep 90 ; sh /location/script.sh )

## resources

https://www.baeldung.com/linux/tag/cron

https://www.baeldung.com/linux/cron-jobs-path

https://www.baeldung.com/linux/cron-files-backup

https://www.baeldung.com/linux/load-env-variables-in-cron-job
