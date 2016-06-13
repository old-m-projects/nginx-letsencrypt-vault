The following are installed

- nginx 
- letsencrypt
- vault
- curl 
- jq 
- git 
- cron 
- python-pip 
- openssl 
- coreutils 
- wget 
- unzip 
- ca-certificates 

NOTES!
 - letsencrypt is setup on a cron to try and auto renew once a month
 - added default.conf to disable port 80, you should include specific .conf files for your domains with server_name's and proper configurations
 - add your own default.conf to override
