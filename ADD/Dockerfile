FROM almalinux:9
RUN dnf install nginx -y
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://www.cinejosh.com/newsimg/newsmainimg/pawan-kalyan-behind-ye-mera-jahaan-song-in-kushi_b_2311220544.jpg /usr/share/nginx/html/index.html
RUN chmod 644 /usr/share/nginx/html/powerstar.jpg
CMD ["nginx", "-g", "daemon off;"]