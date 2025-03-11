
# Github Actions CICD testing 

This is an example of implementing CICD pipeline to automate build, test and deploy the container on dockerhub.


##  Features:
- Automated testing after each commit 
after each commit to the main branch it does a few test 

- after deployment on dockerhub we can pull the image to local system 

```docker pull anonymouspi/flask-app```
- run the container locally 
```	docker run -p 5000:5000 anonymouspi/flask-app:latest ```