FROM ubuntu:22.04

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

COPY script.sh .

RUN chmod +x script.sh
RUN apt-get update
RUN apt-get install -y curl

# When running docker run the command will be ./script.sh
CMD ./script.sh
