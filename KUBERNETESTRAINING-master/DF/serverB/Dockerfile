FROM giriraj789/webserver:A
RUN echo "SERVER B IS RUNNING" > /var/www/html/index.html
# Always execute entry point
ENTRYPOINT	["/usr/sbin/httpd"]
# Run process in foregroud as a parameter
CMD		["-DFOREGROUND"] 
