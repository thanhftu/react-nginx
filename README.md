> docker build -f Dockerfile.dev .
> docker run -p 3000:3000
> docker run -p 3000:3000 -v /app/node_modules -v $(pwd):/app <image>
> docker exec -it <container> npm run test
## We may build other service with default command is "npm run test" for testing purpose
## for product tion
> docker build .
> docker run -p 8080:80 <image>