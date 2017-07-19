# Random-Docker
A way to ensure that all Docker containers are started with enough entropy to create cryptographic keys

# Installation
To install, simply type:

curl -L https://bit.ly/2uGNBbW -o ~/random.sh


Then, type in:

`sh random.sh`

	`-d` docker name
	`-s' inital entropy size
	`-a` apps already configured on Docker container that need their keys reset (Example: SSH)