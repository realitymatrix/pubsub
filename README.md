Installation instructions:

Clone the repository which contains the ROS2 pubsub package \n
git clone git@github.com:realitymatrix/pubsub.git \n

Pull the installation from github to skip the package building \n
wget -q https://github.com/realitymatrix/pubsub/releases/download/pubsub/compressed_pubsub_demo.tar.gz \n

Unpack the compressed archive of the pubsub installation \n
tar -xzf ./compressed_pubsub_demo.tar.gz \n

Spin up the docker container nodes via Docker-Composer \n
docker compose up \n

In the docker composer output you should see two ROS2 nodes, one talking and one listening. \n
