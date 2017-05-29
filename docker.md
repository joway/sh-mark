## Docker Clean 

### Install

#### For linux

	curl -s https://raw.githubusercontent.com/ZZROTDesign/docker-clean/v2.0.4/docker-clean |
	sudo tee /usr/local/bin/docker-clean > /dev/null && \
	sudo chmod +x /usr/local/bin/docker-clean

#### For Mac

	brew update
	brew install docker-clean

### Usage

- docker-clean stop         
	> Stops and removes all containers, cleans dangling volumes, and networks
	
- docker-clean images       
	> Removes all tagged and untagged images, stopped containers, dangling volumes, and networks
	
- docker-clean run
	> Removes all stopped containers, untagged images, dangling volumes, and networks
	
- docker-clean all          
	> Stops and removes all containers, images, volumes and networks