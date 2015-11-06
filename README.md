example
==

    docker pull docker.io/centos
    make
    ./bin/packer build -only=7 -var='tag=hello' ./centos_build.json
