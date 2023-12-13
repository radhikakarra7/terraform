FROM hashicorp/terraform:0.15.5
RUN apk add --no-cache --update zip bash curl py-pip py3-setuptools openssh-client
RUN pip3 install --upgrade awscli
RUN mkdir -p ~/.ssh
RUN chmod 700 ~/.ssh
RUN touch ~/.ssh/known_hosts
