# install docker in ubuntu
daocloud quick install command
in ubuntu terminal:

    curl -sSL https://get.daocloud.io/docker | sh


test install successfully:
'''
sudo docker run hello-world
'''

success if print:
> Unable to find image 'hello-world:latest' locally
latest: Pulling from library/hello-world
1b930d010525: Pull complete                                                                                                                                  Digest: sha256:c3b4ada4687bbaa170745b3e4dd8ac3f194ca95b2d0518b417fb47e5879d9b5f
Status: Downloaded newer image for hello-world:latest
Hello from Docker!
......

(it means run hello-world image in your docker, but you don't have. So, it pull hello-world from Docker Registry)
