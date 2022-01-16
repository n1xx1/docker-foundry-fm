FROM hurlenko/filebrowser:latest

ARG FB_DATABASE=/config/filebrowser.db
ARG FB_REAL_PASSWORD
ARG FB_ROOT=/data

COPY run.sh /run.sh
RUN chmod a+x /run.sh
ENTRYPOINT ["/run.sh"]
