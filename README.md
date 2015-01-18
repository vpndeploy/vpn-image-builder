# vpn-image-builder
Build  VPN Server Images using Packer 


## How to Use 

1. seutp `DIGITALOCEAN_API_TOKE`

```
export DIGITALOCEAN_API_TOKEN="YOUR-DIGITALOCEAN-API-TOKEN"
```

2. checkout vpn-deploy-playbook 

```
git clone https://github.com/ftao/vpn-deploy-playbook ../vpn-deploy-playbook/
```

3. run packer 

```
packer build vpn.do.json
```

