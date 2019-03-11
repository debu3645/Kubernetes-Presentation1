FROM giriraj789/webserver:A
RUN echo "VERSION 2.0" > /var/www/html/index.html
# Always execute entry point
ENTRYPOINT	["/usr/sbin/httpd"]
# Run process in foregroud as a parameter
CMD		["-DFOREGROUND"] 
