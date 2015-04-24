# Template Globals

* Date:    April 16, 2014
* Author:  Jaime A. Rodriguez <hi.i.am.jaime@gmail.com>
* Version: 1.0
* License: http://opensource.org/licenses/MIT

Allows you to use sleepyMUSTACHE core globals form globals.php in your templates.

Available globals:

* URLBASE
* DIRBASE
* DBHOST
* DBUSER
* DBPASS
* DBNAME
* EMAIL_FROM
* EMAIL_TO
* EMAIL_CC
* EMAIL_BCC
* GA_ACCOUNT

## Usage

~~~ php 
	<script async data-main="<?= URLBASE ?>js/main" src="<?= URLBASE ?>js/require.js" ></script>
~~~