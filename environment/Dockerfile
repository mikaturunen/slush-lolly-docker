# Building on top of Ubuntu image
FROM ubuntu:14.04

MAINTAINER Mika Turunen <mika.turunen@ymail.com>

# Updating package listing
RUN sudo apt-get update

# Installing required packages (curl/wget required by n)
RUN sudo apt-get install -y wget curl npm nodejs

# Updating to specific Node and NPM versions
RUN sudo npm install -g n
RUN sudo n 0.10.33
RUN sudo npm install -g npm@2.1.7

# Installing stack specific packages
RUN sudo apt-get install -y mongodb
RUN sudo npm install -g slush bower
