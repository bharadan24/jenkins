FROM bharadan24/jenkinswithdocker:latest
MAINTAINER bharadan24@gmail.com
USER root

# Install node
RUN apt-get update \
    && curl -sL https://deb.nodesource.com/setup_12.x | bash - \
    && apt-get install -y nodejs \
    && curl -L https://www.npmjs.com/install.sh | sh
