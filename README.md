# LEMP-centos-6-7
linux (centos), nginx, mysql, php (php-fpm)

# Added Stronger DHE Parameters
cd /etc/nginx/ssl/ && openssl dhparam -out dhparam.pem 2048


# Testing security of site

1. Qualys SSL Labs  
A free online service performs a deep analysis of the configuration of any SSL web server on the public Internet. Please note that the information you submit here is used only to provide you the service. We don't use the domain names or the test results, and we never will:

`https://www.ssllabs.com/ssltest/index.html`

