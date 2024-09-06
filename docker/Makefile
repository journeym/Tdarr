USERNAME=journeym
REPO=tdarr_node
TAG=test
VERSION=2.24.05
PLATFORMS=linux/amd64

build-server:
	docker buildx build -f Dockerfile.base -t ${USERNAME}/${REPO}:${TAG} --build-arg VERSION=$(VERSION) --build-arg MODULE=Tdarr_Server --platform ${PLATFORMS} --push .
#build-node:
	#docker buildx build -f Dockerfile -t ${USERNAME}/${REPO}:${TAG} --build-arg VERSION=$(VERSION) --build-arg MODULE=Tdarr_Node --platform ${PLATFORMS} --push .