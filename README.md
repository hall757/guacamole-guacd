Guacamole-guacd
====

Guacamole guacd service

Exposes port 4822

---
Author
===

Randy Hall <randy.hall@open-source.guru>

---
Building
===

Build from docker file:

```
git clone git@github.com:hall757/guacamole-guacd.git
docker build -t hall/guacamole-guacd . 
```

---
Running
===


```
docker run -d --name guacamole-guacd hall/guacamole-guacd
```

Now you can link it to a container running the web portion of guacamole
