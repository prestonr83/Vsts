### How to use Remote Unzip build / release tasks

## Remote UnZip

* Add a new task and select Remote UnZip

* Enter one or more Remote Computer IP addresses or Hostnames
* Enter User name and password for remote machine
* Enter Zip file path on remote machine . for example : C:\Test.zip
* Enter output folder for extract . for example : C:\Output
* Do check for Clean Output CheckBox if you want to clean output befor unzip (This option is automatically selected and probably remove future update! ).
* Do check for Remove Zip CheckBox if you want to remove zip file after complete extract zip .
* Choose PSRemoting option of HTTP or HTTPs
* If using Self-signed certficate you can ignore it when using HTTPs

