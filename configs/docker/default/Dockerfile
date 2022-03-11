FROM	ubuntu:20.04

RUN	set -x \
	# Install the needed package
	&& export DEBIAN_FRONTEND=noninteractive \
	&& apt update \
	&& apt install --no-install-recommends -y \
		gawk \
		gcc-arm-none-eabi \
		libnewlib-arm-none-eabi \
		make \
		python3 \
		stlink-tools \
		sudo \
	&& rm -rf /var/lib/apt/lists/*
