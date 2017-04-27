# php-fpm

the only modified file is [www.conf](pool.d/www.conf)

## conf.d

the content of conf.d:

	.
	├── 05-opcache.ini -> ../../mods-available/opcache.ini
	├── 10-pdo.ini -> ../../mods-available/pdo.ini
	├── 20-apcu.ini -> ../../mods-available/apcu.ini
	├── 20-curl.ini -> ../../mods-available/curl.ini
	├── 20-gd.ini -> ../../mods-available/gd.ini
	├── 20-intl.ini -> ../../mods-available/intl.ini
	├── 20-json.ini -> ../../mods-available/json.ini
	├── 20-mcrypt.ini -> ../../mods-available/mcrypt.ini
	├── 20-mysqli.ini -> ../../mods-available/mysqli.ini
	├── 20-mysql.ini -> ../../mods-available/mysql.ini
	├── 20-pdo_mysql.ini -> ../../mods-available/pdo_mysql.ini
	├── 20-readline.ini -> ../../mods-available/readline.ini
	└── 20-redis.ini -> ../../mods-available/redis.ini

