# Slush-lolly-docker
## Development 
This package aims to simplify the setup process of developmend and storage environments for slush-lolly generator created applications. The reason the development environment is based on Ubuntu 14.04 for now is that most of the cases the slush-lolly user will be deploying their slush-lolly application to a Linux based server architecture so it should fit together nicely. Obviously the final testing and possibly compilation should be done matching the final setup of the deployment platform to guarantee success in production. So build the Docker image to match that target. Should be easy enough with the help of Docker tutorials lying around.

## Storage
The package provides different Docker containers for database and code base so they are persistent and the underlying development environment image can chase as much as it wants. 

## Misc
Anything else? Bugs? Issues? Suggestions? Fire away! I'm more than happy to discuss the setup and everything relating to it.

