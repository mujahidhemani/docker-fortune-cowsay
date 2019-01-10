FROM ubuntu:18.04

RUN apt-get update && apt-get install -y cowsay fortunes fortunes-off \
&& rm -rf /var/lib/apt/lists/*

CMD /usr/games/fortune -a | /usr/games/cowsay
