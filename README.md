# sumo-docker

This is SUMO 

USAGE: docker run -v C:\Users\**\INPUT:/MNT/INPUT ghcr.io/schumifabi/sumo-docker/docker-image:latest sumo -c /MNT/INPUT/start.sumocfg

WORKAROUND IN PIPELINE: docker run -v C:/Users**/OUTPUT/:/mnt/output/ test sumo -c /mnt/work/start.sumocfg; cp /mnt/work/ /mnt/output/
