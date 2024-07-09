furry.ong api

```curl -X GET https://furry.ong/my-ip -H "X-Real-IP"```

```curl -X POST http://furry.ong/ip-search -H "Content-Type: application/json" -d '{"ip": "8.8.8.8"}'```

```curl -X POST https://furry.ong/bpf -H "Content-Type: application/json" -d '{"bpf": "tcp[22]=0x38"}'```

```curl -X POST -F "file=@/root/attack.pcap" https://furry.ong/pcap```

```curl -O https://furry.ong/socks```
