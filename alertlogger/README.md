# Compile as docker image
sudo docker build -t alertlogger:1.0 .

# Run docker image
 sudo docker run -it -d --name alertlogger alertlogger:1.0
