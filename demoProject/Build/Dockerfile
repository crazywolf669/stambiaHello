FROM stambiadev/runtime:20.1

COPY ./deliveries /opt/stambia/stambiaRuntime/build/deliveries

WORKDIR /opt/stambia/stambiaRuntime

EXPOSE 42000 42200

CMD ["/opt/stambia/stambiaRuntime/startengine.sh", "-verbose"]