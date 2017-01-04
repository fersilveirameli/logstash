FROM kibana:5.0.0

RUN gosu kibana kibana-plugin install \
    https://github.com/sivasamyk/logtrail/releases/download/0.1.4/logtrail-5.x-0.1.4.zip

ADD logtrail.json /usr/share/kibana/plugins/logtrail/logtrail.json
