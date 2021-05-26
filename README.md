# arkadii-homework

#Comand to run docker images for rep clone in current local directory
docker run -e REPO_URL=https://github.com/Dgadavin/itea-base-course.git -v ${PWD}:/data clonerep:1.0
