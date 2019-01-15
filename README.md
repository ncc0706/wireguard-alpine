
Usage:

This uses a custom installs a kernel module hence the mounts

docker run --rm -it \
 	--name wireguard \
 	-v /lib/modules:/lib/modules \
 	-v /usr/src:/usr/src:ro \
 	r.j3ss.co/wireguard:install
