# V Risign

## Preinstall steps

### Pufferpanel user on docker group
Do you need to add pufferpanel user to docker group to execute commands on docker.

```shell
  sudo usermod -aG docker pufferpanel
```

Then, restart your server.

## Warning
The **stop server** does not work, just kill the server and the docker container may stop!

## Credits
All credits go to [TrueOsiris](https://github.com/TrueOsiris), on his docker [Vrisign project](https://github.com/TrueOsiris/docker-vrising).

Thank you to do this project !! you are awesome TrueOsiris!