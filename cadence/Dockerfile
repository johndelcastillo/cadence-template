FROM ubercadence/server:master-auto-setup

ARG DB DBNAME DB_PORT POSTGRES_USER POSTGRES_PWD POSTGRES_SEEDS FRONTEND_SERVICE

COPY dynamic.yaml /etc/cadence/config/dynamicconfig/dynamic.yaml

ENV DYNAMIC_CONFIG_FILE_PATH="config/dynamicconfig/dynamic.yaml"
ENV BIND_ON_IP="0:0:0:0:0:0:0:0"
