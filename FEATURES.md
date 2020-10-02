# Features


  HostKit relies on other packages to do some of the work. For every feature I wrote which packages are required. For more information - Requirements.


## Configuration

HostKit is planned to be independent of the operating system configuration. So in the configuration file you should be able to change the location of every file or program needed by HostKit.

### HostKit offers:
* HostKit does not use hosting plans.
  * It allows the user to choose his
    * traffic, disk space limit
    * number of email accounts
    * ...see user area for more.
* In the configuration file you can specify
  * hosting periods
  * initial traffic
  * initial disk quota
  * initial number of email accounts
  *initial price
  * price for extra traffic
  * price for extra disk space
  * price for email account
  * price for using CGI and PHP
  * price for using MySQL
  * You can specify different values for subdomain
* Multilanguage support.
* Manage the content of HostKit.
* Enable Qmail.
* Enable Awstats.
* Enable free hosting

#### User area
* Choose free or commercial hosting
* Choose username and password
* Choose local domain or his own already registered domain
* Use CGI and PHP
* Use MySQL
   * includes phpMyAdmin
* Use ftp
* Use the HostKit web ftp
* Create new domains or subdomains of his domains (for the same user)
* Create virtual email accounts of type someuser@example.com or someuser@hsubdomain.example.com
  * Uses Qmail and Vpopmail
* Forward his mail to other email accounts
* Manage cron jobs
* View web statistic
  * Uses Awstats
* Change user properties:
  * password
  * contact email
  * MySQL options
* Change domain properties after paying:
  * extend hosting period
  * extra traffic
  * extra disk space
  * more email accounts
  * enable CGI and PHP
* Delete his domains and email accounts

#### Admin area
* View accounts by user name or domain like name (if you type .com you will see all domains of type something.com)
* Create and delete free or commercial hosting accounts
* Create and delete domains and email accounts
* Modify every user, domain and email property
* The administrator will receive notification for
  * expired domains
  * exceeded traffic and quota

#### Free hosting area
The free hosting user can:
* Choose username and password
* Choose local domain or his own already registered
* Choose advertise category
* HostKit's free hosting uses email confirmation of the account
* Use ftp
* Use the HostKit web ftp
* Create virtual email accounts of type someuser@example.com or someuser@subdomaid.example.com
* Forward his mail to other email accounts
* View web statistic
* Change user properties:
  * password
  * contact email
* In his pages could be inserted header and footer and a pop up window (ads)
* Can use CGI and MySQL only with the second method (paid)


**NOTE:** If you need additional features, create an [ISSUE](../../issues) and place a request.
