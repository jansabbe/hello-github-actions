FROM debian:9.5-slim

LABEL "com.github.actions.name"="Hello World" 
LABEL "com.github.actions.description"="Write arguments to standard output"
LABEL "com.github.actions.icon"="mic"
LABEL "com.github.actions.color"="purple"

LABEL "repository"="http://github.com/jansabbe/hello-github-actions"
LABEL "homepage"="http://github.com/actions"
LABEL "maintainer"="Jan <mail.inator@atrenko.com>"

ADD entrypoint.sh /entrypoint.sh
RUN chmod +x /entrypoint.sh
ENTRYPOINT [ "/entrypoint.sh" ]