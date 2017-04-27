# Drupal Custom Modules

#### (Epicodus Guided Practice)

#### _By Maggie Harrington_
##### _4-24-17 through 4-27-17_


## Description

##### _Practice creating custom modules in Drupal. My custom modules are located at sites/all/modules/custom and are displayed as menu links in the project._


##### This project demonstrates the following skills:

* Write a basic custom Drupal module in PHP.
* Use basic forms to collect and display information in a custom module.
* Use form element validation.


## Setup/Installation Requirements

##### Requirements:

* MAMP (see https://www.mamp.info/en/downloads/ for installation details)


##### Clone Project:

* Open the terminal and enter `cd Desktop`

* Enter `git clone ` and copy/paste the project link: https://github.com/maggie-harrington/drupal-custom-module-practice

* Enter `cd drupal-custom-module-practice`


##### Import Database and Configure:

* In MAMP Preferences, change document root to project folder listed above. Make sure Apache Port is set to 8888 and MySQL Port is set to 8889.

* In your web browser, open phpMyAdmin: http://localhost:8888/MAMP/index.php?page=phpmyadmin&language=English

* Click the 'Import' tab, leave the default settings and make sure the character set is 'utf-8'.

* Click the 'Choose File' button next to 'Browse your computer' and navigate to sites/db-backup/modules_practice.sql.zip , then click 'Go'.

* Select the 'Privileges' tab and click 'Add User', then enter 'admin' for the username and 'admin' for the password.

* Navigate to localhost:8888 in your web browser to view the project. (Make sure to keep the terminal window containing the server open while the project runs.)


## Support and contact details

If you run into any issues or have questions, ideas or concerns, please feel free to contact me at maggie.harrington@gmail.com


## Technologies Used

Written using Drupal, MAMP, PHP, Atom, and Git.


## MIT License

Copyright (c) 2017 Maggie Harrington
