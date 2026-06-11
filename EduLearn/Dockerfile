FROM nginx:alpine

LABEL maintainer="Samiksha"
LABEL project="EduLearn Portal"
LABEL version="1.0"

WORKDIR /usr/share/nginx/html

COPY . .

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]