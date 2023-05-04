FROM gitlab.84.201.150.198.sslip.io:443/gitlab-instance-711bf56d/dependency_proxy/containers/mysql:5.7

# ENV MYSQL_ROOT_PASSWORD DEFAULT_PASS
# ENV MYSQL_ALLOW_EMPTY_PASSWORD=true
# ENV MYSQL_DATABASE=socksdb

COPY ./data/dump.sql /docker-entrypoint-initdb.d/

