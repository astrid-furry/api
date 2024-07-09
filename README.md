furry.ong api

```curl --user-agent "furry" -X GET https://furry.ong/my-ip -H "X-Real-IP"```

```curl --user-agent "furry" -X POST http://furry.ong/ip-search -H "Content-Type: application/json" -d '{"ip": "8.8.8.8"}'```

```curl --user-agent "furry" -X POST https://furry.ong/bpf -H "Content-Type: application/json" -d '{"bpf": "tcp[22]=0x38"}'```

```curl --user-agent "furry" -X POST -F "file=@/root/attack.pcap" https://furry.ong/pcap```

```curl --user-agent "furry" -O https://furry.ong/socks```
