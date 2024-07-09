furry.ong api

```curl -3 -X GET https://furry.ong/my-ip -H "X-Real-IP"```

```curl -3 -X POST http://furry.ong/ip-search -H "Content-Type: application/json" -d '{"ip": "8.8.8.8"}'```

```curl -3 -X POST https://furry.ong/bpf -H "Content-Type: application/json" -d '{"bpf": "tcp[22]=0x38"}'```

```curl -3 -X POST -F "file=@/root/attack.pcap" https://furry.ong/pcap```

```curl -3 -O https://furry.ong/socks```
