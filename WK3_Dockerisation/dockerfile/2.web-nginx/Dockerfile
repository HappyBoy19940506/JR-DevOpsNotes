FROM nginx

RUN echo 'construction building ..............'

WORKDIR /usr/share/nginx

COPY . ./html/

RUN echo 'construction compelete..............'

EXPOSE 80

#CMD ["nginx", "-g", "daemon off;"]
#不写这句也没事，因为nginx 镜像里面已经写了这句了，

# CMD ["=", "2]


# ENTRYPOINT ["echo", "1+1"]

# 先运行entry point，然后拼接cmd

# when you run : docker run ... it will show 1+1 = 2
