# Hc05-bluetooth-avrstudio

=========================

Usage
-----

To get installing , you have to do the following:

1. Install Bluetooth Library for Proteus in Proteus Library.

2. use this circuit diagram for 
    * ! Connection for HC05 to PC:.
3. Install Bluetooth Library for Proteus in Proteus Library.
![Alt text](http://i.cubeupload.com/1RuBY2.jpg "Install Bluetooth Library for Proteus in Proteus Library")
![Alt text](GccApplication1\Proteus\Virtual.Serial.Port.Driver.jpg?raw=true "Install Bluetooth Library for Proteus in Proteus Library")


4.  Connection for HC05 to PC:
![Alt text](GccApplication1\Proteus\1022397806_355.jpg?raw=true "Connect hc05 to pc with max232")

![Alt text](GccApplication1\Proteus\HC05-Arduino-breakout.jpg?raw=true "HC05 connection ports")


4. Run `git push --force "openshift" master:master`
5. SSH into your gear
6.  `cd $OPENSHIFT_REPO_DIR && rm -rf misc* && rm -rf www && rm -rf nginx-php-fp-in-openshift--main-free-papers_elass_ir ` 
7. `git clone https://github.com/power-electro/nginx-php-fp-in-openshift--main-free-papers_elass_ir.git` 
8. `chmod 755  $OPENSHIFT_REPO_DIR/nginx-php-fp-in-openshift--main-free-papers_elass_ir/install-nginx-php.sh`
9. Wait (This may take at least an hour)
    If you want to see "what's going on, you may tail the log file and watch some shell movie ;)
10. `nohup $OPENSHIFT_REPO_DIR/nginx-php-fp-in-openshift--main-free-papers_elass_ir/install-nginx-php.sh > $OPENSHIFT_LOG_DIR/install.log & `
    `tail -f $OPENSHIFT_DIY_LOG_DIR/install.log`
11. Open http://appname-namespace.rhcloud.com/phpinfo.php to verify running
   apache
12. You can remove the misc content
