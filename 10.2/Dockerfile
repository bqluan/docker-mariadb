FROM mariadb:10.2

# Set timezone to Asia/Shanghai
RUN set -e \
	&& echo "Asia/Shanghai" > /etc/timezone \
	&& dpkg-reconfigure -f noninteractive tzdata
