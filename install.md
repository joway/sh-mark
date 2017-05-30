## Go

### Ubuntu 16.04

	apt-get install software-properties-common
	sudo add-apt-repository ppa:longsleep/golang-backports
	sudo apt-get update
	sudo apt-get install golang-go
	
	
	# append into ~/.bashrc
	export GOROOT=~/go
	export GOARCH=386
	export GOOS=linux
	export GOBIN=$GOROOT/bin/
	export GOTOOLS=$GOROOT/pkg/tool/
	export PATH=$PATH:$GOBIN:$GOTOOLS

## Docker

### General

	curl -sSL https://get.docker.io | sh
	
	# or for china mirror
	curl -sSL https://get.daocloud.io/docker | sh
	
## Telegraf


### Ubuntu & Debian

	wget https://dl.influxdata.com/telegraf/releases/telegraf_1.3.0-1_amd64.deb
	sudo dpkg -i telegraf_1.3.0-1_amd64.deb
	
### RedHat & CentOS

	wget https://dl.influxdata.com/telegraf/releases/telegraf-1.3.0-1.x86_64.rpm
	sudo yum localinstall telegraf-1.3.0-1.x86_64.rpm

## Influxdb


### Ubuntu & Debian

	wget https://dl.influxdata.com/influxdb/releases/influxdb_1.2.4_amd64.deb
	sudo dpkg -i influxdb_1.2.4_amd64.deb
	
### RedHat & CentOS

	wget https://dl.influxdata.com/influxdb/releases/influxdb-1.2.4.x86_64.rpm
	sudo yum localinstall influxdb-1.2.4.x86_64.rpm