view live MySQL queries

mysql> show variables like 'general%';

mysql> set global general_log = 'on';

Don't forget to turn off
mysql> set global general_log = 'off';

% tail -f -n300 /usr/local/var/mysql/Users-Air.log