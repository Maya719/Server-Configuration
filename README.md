# Server-Configuration
VHOST
The vhost in nginx can also add by..
1) open the .conf file in code editor than copy the code and past the site vhost in cloudpanal
2) copy the .conf file to site than open the ssh than move the .conf file to /etc/nginx/sites-enabled/
---------------------------------------------------------------------------------------------------------------------
UWSGI 
open the ssh than the loction /etc/uwsgi/apps-enabled/
1) simple make file with the name by using cmd
   eg: nano domain.uwsgi.ini
2) than page the configuration and save it.
3) After this make the service of the uwsgi
