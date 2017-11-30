# pihole-swarm-armhf #

pihole service stack for docker swarm on raspberry pi

## Getting Started

```bash
# clone
git clone git@github.com:klutchell/pihole-swarm-armhf.git
cd pihole-swarm-armhf

# configure
cp pihole.env.example pihole.env
nano pihole.env
```

## Deployment

```bash
docker stack deploy --compose-file docker-compose.yml pihole 
```

## Usage

```bash
bin/pihole --help
```

## Author

Kyle Harding <kylemharding@gmail.com>

## License

_tbd_

## Acknowledgments

_tbd_
