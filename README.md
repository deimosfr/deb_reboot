deb_reboot
==========

Indicate if your Debian needs to be restarted or not (due to packages upgrades)

You can simply call it to tells you if you need to reboot or not. Options call be displayed with -h argument :

> ./deb_reboot -h
usage: deb_reboot [-h] [-q] [-s] [-v] [-d]

> Check if reboot is required on a Debian machine

> optional arguments:
> 
  -h, --help     show this help message and exit
>
  -q, --quiet    quiet mode, only return code (0 noting to do | 2 reboot
                 required)
>
  -s, --show     show full list of packages that request a reboot
>  
  -v, --version  Version 0.1
>  
  -d, --debug    debug mode

Note : A good use case for the -q option, is for monitoring solutions like Nagios.
