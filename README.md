# mongodbTx
fvcvxc

Build this Dockerfile

docker build ./ -t mongodb:4.7-replset
Run this created image

docker run --name mongodb-replset -p 27017:27017 -d mongodb:4.7-replset
Connect to database using this URI

mongodb://localhost:27017/myDB