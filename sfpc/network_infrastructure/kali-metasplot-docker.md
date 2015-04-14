

    $ brew install docker

    $ brew install boot2docker

    $ docker init

    $ docker start

# Run a kali linux image, you can find one on [docker hub](https://registry.hub.docker.com/). There are some with metasploit included already.

    $ docker run -t -i pandrew/kali

# If you got one without metasploit you can simply install using apt-get

    $ apt-get update && apt-get upgrade
    $ apt-get install metasploit


# Run metasploit

    $ msfconsole

# Run your image again, cotinue where you left off, first exit

    $ docker ps

    $ docker commit CONTAINER_ID YOUR_IMAGE_NAME

    $ docker run -t -i YOUR_IMAGE_NAME


