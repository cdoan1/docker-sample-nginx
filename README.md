# docker-sample-nginx

a sample nginx container to display container name

# usage

```
docker build -t dhubchris/nginx-sample:0.0.1 .
docker push dhubchris/nginx-sample:0.0.1
docker run -p 3000:80 -name nginx-sample dhubchris/nginx-sample:0.0.1
```

