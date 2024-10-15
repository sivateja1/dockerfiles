FROM almalinux:9
RUN dnf install nginx -y 
RUN rm -rf /usr/share/nginx/html/index.html
ADD https://github.com/sivateja1/expenses-documention/blob/main/3-tier-expense.svg /usr/share/nginx/html/index.html
CMD ["nginx", "-g", "daemon off;"]