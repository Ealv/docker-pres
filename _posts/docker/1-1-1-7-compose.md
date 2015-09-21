### Compose your own dev-Architecture

A node.js server speaking to elasticsearch !

1 Compose with ...docker-compose


```HTML
nodejs:
  image: node-test
  links:
    - elasticsearch
elasticsearch:
  image: elasticsearch:1.5.2
```

2 Launch it :

```HTML
docker-compose up
```