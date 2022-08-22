# dc_nextcloud-mysql
add to /nc_app/config/config.php before bloc "trusted_domains"
'overwritehost' => 'your domain'
# in block "trusted_domains" row "array" add:
   1 => 'ip adress nginx',
   2 => 'you-domains.com',
