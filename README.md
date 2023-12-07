# sumo-docker

This is SUMO  

USAGE: docker run -v C:\Users\**\INPUT:/MNT/INPUT ghcr.io/TUMFTM/sumo-docker/docker-image:latest sumo -c /MNT/INPUT/start.sumocfg

WORKAROUND IN PIPELINE:  docker run -v C:/Users/.../OUTPUT/:/mnt/output/ test bash -c 'sumo -c /mnt/work/start.sumocfg; cp -r /mnt/work/ /mnt/output/'
