FROM eclipse/stack-base:debian
RUN sudo apt-get update && \
	curl -sSL https://get.haskellstack.org/ | sudo sh -s -- -d /bin && \
	sudo stack setup