# base-ml-docker

Base docker image for doing machine learning in docker containers. Supports only NVIDIA cuda, make sure to install [nvidia-docker2](https://docs.nvidia.com/datacenter/cloud-native/container-toolkit/install-guide.html#docker)


## Usage

`docker build -t ml .`
`docker run -it ml bash`