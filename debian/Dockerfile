FROM debian
MAINTAINER Ivan Xu "theivanxu@gmail.com"
ENV REFRESHED_AT 2017-06-26
RUN apt-get update
RUN apt-get -y install ruby rake
RUN gem install --no-rdoc --no-ri rspec ci_reporter_rspec
