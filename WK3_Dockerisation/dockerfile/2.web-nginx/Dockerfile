FROM nginx

RUN echo 'construction building ..............'

COPY ./index.html /usr/share/nginx/html

RUN echo 'construction compelete..............'

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]
# 不写这句也没事，因为nginx 镜像里面已经写了这句了，