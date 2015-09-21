### Compose your own dev-Architecture


I want a node.js server speaking to an elasticsearch up and running in then minutes.

1 Compose your dev env with ...docker-compose


```HTML
nodejs:
  image: node-test
  volumes:
    - .:/var/app
  links:
    - elasticsearch
elasticsearch:
  image: elasticsearch:1.5.2
  ports:
   - "9200:9200"
```

2 Launch it :


```HTML
docker-compose up
```