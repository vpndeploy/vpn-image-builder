# Vpn Image Builder

Build VPN Server Images using Packer, so we can setup a VPN Server in 5 seconds .

## How to Use 

1. Install Packer (https://www.packer.io)
2. seutp `DIGITALOCEAN_API_TOKE`
  
  ```
  export DIGITALOCEAN_API_TOKEN="YOUR-DIGITALOCEAN-API-TOKEN"
  ```
3. checkout vpn-deploy-playbook 
  
  ```
  git clone https://github.com/ftao/vpn-deploy-playbook ../vpn-deploy-playbook/
  ```
4. run packer 
  
  ```
  packer build vpn.do.json
  ```
