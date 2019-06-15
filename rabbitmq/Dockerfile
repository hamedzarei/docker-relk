FROM rabbitmq:latest

COPY rabbitmq.config /etc/rabbitmq/
COPY custom_definitions.json /etc/rabbitmq/

RUN rabbitmq-plugins enable --offline rabbitmq_management
RUN rabbitmq-plugins enable --offline rabbitmq_mqtt

EXPOSE 15672 5672 1883

CMD ["rabbitmq-server"]
