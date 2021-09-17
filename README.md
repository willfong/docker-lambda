# Dockerized Lambda Functions

Build the Docker image:
```
npm run docker-build
```

Run the Docker function:
```
npm run docker-run
```

Test the function:
```
npm run post
```

Tag the image:
```
docker tag <name-of-repo>:latest <1234567890>.dkr.ecr.<region>.amazonaws.com/<name-of-repo>:latest
```

Push the image:
```
docker push <name-of-repo>:latest <1234567890>.dkr.ecr.<region>.amazonaws.com/<name-of-repo>:latest
```


## Useful Links
- https://docs.aws.amazon.com/lambda/latest/dg/gettingstarted-images.html
- https://docs.aws.amazon.com/lambda/latest/dg/lambda-nodejs.html
