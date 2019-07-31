ARG BUILD_FROM="homeassistant/amd64-base-python:3.7"
FROM $BUILD_FROM

# Copy data
COPY tensorflow-1.12.0-py3-none-any.whl /
COPY run.sh /
RUN chmod a+x /run.sh

WORKDIR /data
CMD ["/run.sh"]
