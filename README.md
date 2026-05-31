# CyberHelios-infra
CyberHelios, infra would contain the code/config that deploys and runs our projects, not the project logic itself.


infra/
├── proxmox/
│   └── gateway-lxc/
│
├── nginx/
│   └── meshgate/
│
├── dns/
│   └── meshgate-ddns/
│
├── vpn/
│   └── topology/
│
├── scripts/
│   ├── deploy-gateway.sh
│   ├── bootstrap-ddns.sh
│   └── join-node.sh
│
└── monitoring/
