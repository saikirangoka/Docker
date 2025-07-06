FROM almalinux:9

RUN dnf install nginx -y

# Copy HTML and image file
COPY index.html /usr/share/nginx/html/index.html
ADD https://www.cinejosh.com/newsimg/newsimg/newsminimg/pawan-kalyan-behind-year-2015_300.jpg /usr/share/nginx/html/pawan.jpg

# Set permissions
RUN chmod 644 /usr/share/nginx/html/* && \
    chown nginx:nginx /usr/share/nginx/html/*

CMD ["nginx", "-g", "daemon off;"]