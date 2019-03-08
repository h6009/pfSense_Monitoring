*STEP 1:*

SSH to pfsense with root permission.

STEP 2: Download source and put it into /usr/local/www/

`cd /usr/local/www && curl -LO https://github.com/h6009/pfSense_Monitoring/archive/master.zip`

STEP 3: unzip

`unzip /usr/local/www/master.zip`

STEP 4: delete README file.

`rm /usr/local/www/README`

STEP 5: Result

```
https://yourpfsense/pfSense_Monitoring-master/pfsense_json.php
https://yourpfsense/pfSense_Monitoring-master/pfsense_ui.php
```

*Note: *
This is using for developer with purpose testing. Not for production because problem of security.

Everyone can easy access to this link and see all the devices of your network. This not good. 

But if I have time, I will make a password for POST or GET method to improve security later.
