# Custom images for n8n

See [my blog post on how](https://www.weeumson.com/posts/Persist-n8n-community-nodes-on-docker-through-updates/) to persist n8n custom and community nodes in your docker setups.

The easiest option is to use the example in 'bwill-nodes-simple' folder - 

```
FROM n8nio/n8n:latest
RUN npm install -g bla bla
```

The other examples build the n8n image from scratch, so to speak.
