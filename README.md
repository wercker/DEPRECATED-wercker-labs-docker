wercker-labs-docker
===================

This is the packer script used to provision the docker image (an amazon AMI).
The image is based on the default amazon ubuntu 12.04 64-bit ami

Feel free to make suggestions, send pull request and such.

__Note:__ This project is meant to show how the docker image is created, not 
like the normal wercker boxes: enable all users to create their own variants.

## How to provision an ami image
Provision the docker labs ami with the following command:

``` bash
export AWS_ACCESS_KEY=<<THE_AWS_KEY>>
export AWS_SECRET_KEY=<<THE_AWS_SECRET>>
packer build docker.json
```
## License
The MIT License (MIT)

# Changelog

## 0.0.2
* initial public release
