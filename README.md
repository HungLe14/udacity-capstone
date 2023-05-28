# Multicontainer application

http://a23976a05fbeb4689b72767342e23f2a-1353686138.us-west-2.elb.amazonaws.com:3000/
reference: https://www.youtube.com/watch?v=I3hGuWVUyWU&list=PLKRWHMZ_QGZCTxLF-U7jI9F4CktvEO9oh&index=20

the steps i do in turn are:
First I build 3 containers, they are backend front-end and database.
then i write docker files for each of my apps
I went to github action to create a jobs which is used to build images and deploy images.
I went to aws to initialize eks and add a node group to it
finally i run kubectl apply -f k8s
picture of pipeline you can see i attached

NOTICE: I don't have any credit card so that I'll use Github action for this project.
