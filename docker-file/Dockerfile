# 
#

FROM ubuntu:20.04
RUN DEBIAN_FRONTEND="noninteractive" apt-get update
RUN DEBIAN_FRONTEND="noninteractive" apt-get upgrade
RUN DEBIAN_FRONTEND="noninteractive" apt-get install -y curl openssh-server ca-certificates tzdata perl
RUN DEBIAN_FRONTEND="noninteractive" apt-get install -y postfix
RUN curl https://packages.gitlab.com/install/repositories/gitlab/gitlab-ee/script.deb.sh | bash
RUN EXTERNAL_URL="https://192.168.0.37" apt-get install gitlab-ee



