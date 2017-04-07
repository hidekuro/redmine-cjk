FROM mariadb:10.1
LABEL maintainer "hidekuro"

# put conf file
COPY ./conf/my.cnf /etc/mysql/conf.d/zzz-my.cnf

# treat Windows
RUN chmod 644 /etc/mysql/conf.d/*
