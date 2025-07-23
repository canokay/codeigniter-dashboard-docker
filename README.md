# Codeigniter Dashboard

Codeigniter Dashboard SB Admin 2 Bootstrap Theme


## config.php

```php
$config['base_url'] = 'http://localhost:8080/';

$config['sess_save_path'] = APPPATH.'sessions';
```


## database.php

```php
$db['docker'] = array(
	'dsn'	=> '',
	'hostname' => 'mysql',
	'username' => 'ci_user',
	'password' => 'ci_pass',
	'database' => 'ci_db',
	'dbdriver' => 'mysqli',
	'dbprefix' => '',
	'pconnect' => FALSE,
	'db_debug' => (ENVIRONMENT !== 'production'),
	'cache_on' => FALSE,
	'cachedir' => '',
	'char_set' => 'utf8',
	'dbcollat' => 'utf8_general_ci',
	'swap_pre' => '',
	'encrypt' => FALSE,
	'compress' => FALSE,
	'stricton' => FALSE,
	'failover' => array(),
	'save_queries' => TRUE
);
```