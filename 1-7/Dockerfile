FROM ubuntu:16.04
WORKDIR /1-7

RUN apt-get update && apt-get install -y curl

COPY curl_script.sh .
RUN chmod +x curl_script.sh
CMD ./curl_script.sh
