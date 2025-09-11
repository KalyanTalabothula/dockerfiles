FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
#COPY https://github.com/daws-84s/notes/blob/main/session-01.txt /usr/share/nginx/html/index.html
ADD https://raw.githubusercontent.com/daws-84s/notes/refs/heads/main/session-01.txt /usr/share/nginx/html/index.html
RUN chmod +r /usr/share/nginx/html/index.html
ADD sample-1.tar /tmp/
CMD [ "nginx", "-g", "daemon off;" ]

# you can give path name after downloading the file or folder in your laptop or You can give directly URL-LINK