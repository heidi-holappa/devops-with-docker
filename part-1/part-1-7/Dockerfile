# Start from the alpine image that is smaller but no fancy tools
FROM ubuntu:20.04

# Use /usr/src/app as our workdir. The following instructions will be executed in this location.
WORKDIR /usr/src/app

# Update apt-get    
RUN apt-get update

# Install curl
RUN apt-get install -y curl

# Copy the part-1-7.sh file from this location to /usr/src/app/ creating /usr/src/app/hello.sh
COPY part-1-7.sh .

# When running docker run the command will be ./hello.sh
CMD ./part-1-7.sh
