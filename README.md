# Docker registry cache

docker pull busybox
docker tag busybox localhost:5000/busybox
docker push localhost:5000/busybox
docker pull localhost:5000/busybox