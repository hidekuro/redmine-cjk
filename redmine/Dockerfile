FROM redmine:3.3
LABEL maintainer "hidekuro"

COPY ./config/ /usr/src/redmine/config/
COPY ./plugins/ /usr/src/redmine/plugins/
COPY ./themes/ /usr/src/redmine/public/themes/
RUN chown -R redmine:redmine /usr/src/redmine
