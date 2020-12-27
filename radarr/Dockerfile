FROM linuxserver/radarr

# MOFIFY DATA PATH
RUN sed -i "s|config|data|share|g" /etc/services.d/radarr/run

VOLUME [ "/share" ]