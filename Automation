# Apache-Automation
yum -y  install httpd mod_ssl                                              #install apache and ssl support
systemctl start httpd                                                      # start apache
sed -i  ' s/^/#/g ' /etc/httpd/conf.d/welcome.conf                         # comment out the default welcome page
systemctl restart httpd                                                    # restart apache so our changes take effect
