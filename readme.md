# tak-certbot-renew-script
Auotmation script to run certbot renewal on expired SSL certificates, push the files to your takserver config, then bounce the docker instance to make the changes live

## Make sure you have setup cert. enrollment using this first: https://github.com/atakhq/tak-cert-enrollment-script

## Run this to stage the scripts locally

``` cd /tmp/ && git clone https://github.com/atakhq/tak-letsencrypt-renew.git && sudo chmod -R +x * /tmp/tak-letsencrypt-renew/ ```

## Then run this to start the script
 
``` cd /tmp/tak-letsencrypt-renew/ && ./tak-certbot-renew.sh ```
