FROM ubercadence/server:master-auto-setup

ARG DB DBNAME DB_PORT POSTGRES_USER POSTGRES_PWD POSTGRES_SEEDS FRONTEND_SERVICE

COPY dynamic.yaml /etc/cadence/config/dynamicconfig/dynamic.yaml

ENV DYNAMIC_CONFIG_FILE_PATH="config/dynamicconfig/dynamic.yaml"
# :: doesnt work due to some docker mapping things (docker.yaml), might need to look into if 0.0.0.0 doesnt listen on ipv6 for private networking
ENV BIND_ON_IP="0.0.0.0"
