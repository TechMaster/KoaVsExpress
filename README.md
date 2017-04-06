# Introduction

Benchmark performance between Koa vs Express

- To start Koa: ```node koa.js```
- To start Express: ```node exp.js```

Use Apache Benchmark to generate load test to web server at localhost
```bash
ab -n 10000 -c 30 http://127.0.0.1:3000/
``` 
