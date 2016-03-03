FROM ronalex/mesos:0.27.0
MAINTAINER RedJack, LLC

# Mesos fetcher uses unzip to extract staged zip files

RUN \
  apt-get install -y unzip && \
  apt-get clean

EXPOSE 5051
CMD ["mesos-slave"]
