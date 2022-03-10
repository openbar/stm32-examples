FROM	ubuntu:20.04

RUN	set -x \
	# Install the needed package
	&& export DEBIAN_FRONTEND=noninteractive \
	&& apt update \
	&& apt install --no-install-recommends -y \
		build-essential \
		gawk \
		make \
		sudo \
	&& rm -rf /var/lib/apt/lists/*
