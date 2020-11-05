FROM mysql:5.7

MAINTAINER Hua(Nelson) Qiao

ADD ./custom.cnf /etc/mysql/conf.d/ 

COPY ./sql-scripts/ /docker-entrypoint-initdb.d/
