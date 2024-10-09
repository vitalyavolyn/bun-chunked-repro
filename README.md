```
curl -X POST localhost:8080 -H "Transfer-Encoding: chunked" -H 'Content-Type: application/json' -d '{"hello": "world"}'
```

```
vitalya@applin ~/d/bun-chunked-repro> bun run index.ts             
Listening on port 8080...
{}
^C
```

```
vitalya@applin ~/d/bun-chunked-repro> node index.js                                                                                                                                                           1
Listening on port 8080...
{ hello: 'world' }
^C
```
