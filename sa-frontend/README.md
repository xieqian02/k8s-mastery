## Starting the Web App Locally
` $ yarn start `

## Building the application
` $ yarn build `

## Building the container
` $ docker build -f Dockerfile -t $DOCKER_USER_ID/sa-frontend . `

## Running the container
` $ docker run -d -p 80:80 $DOCKER_USER_ID/sa-frontend `

## Pushing the container
` $ docker push $DOCKER_USER_ID/sa-frontend `
