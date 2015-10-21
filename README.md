# docker-logrotate
Truncates container logs when they grow in size

## Usage

	docker run -v /var/lib/docker/containers:/var/lib/docker/containers goblain/logrotate

## Credits
This image started as a spinoff from tutumcloud/logrotate
