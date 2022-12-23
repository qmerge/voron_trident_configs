# voron_trident_configs
configuration for my fombot voron trident

Add debug in .cfg with 
{ action_respond_info("_PRINT_START") }

When you install the Octopi way..

Klippy.log is in tmp.

read Klippy.log using  ~/klipper/scripts/logextract.py  i.e

cp ~/tmp/klippy.log . 
~/klipper/scripts/logextract.py  klippy.log 

watch klippy.log (highly recomended) from linux with
tail -f  /tmp/klippy.log |grep -v Stats


Octoprint logs are in:
~/.octoprint/logs



its not uncommon to have klipper fail to connect if you use mcu_pi.
to restart klipper, type following in linux login
sudo service klipper restart



