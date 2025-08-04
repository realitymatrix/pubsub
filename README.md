Installation instructions:

Clone the repository which contains the ROS2 pubsub package
git clone git@github.com:realitymatrix/pubsub.git

Pull the installation from github to skip the package building
wget -q https://github.com/realitymatrix/pubsub/releases/download/pubsub/compressed_pubsub_demo.tar.gz

Unpack the compressed archive of the pubsub installation
tar -xzf ./compressed_pubsub_demo.tar.gz

Spin up the docker container nodes via Docker-Composer
docker compose up

In the docker composer output you should see two ROS2 nodes, one talking and one listening.
