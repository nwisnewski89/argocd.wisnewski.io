## Argo app of apps repository

1. Create the app of apps application `kubectl apply -f app-of-apps.yaml`
2. Application secrets are managed with terraform in a separate repository [homelab.wisnewski.io](https://github.com/nwisnewski89/homelab.wisnewski.io)

## Apps

- [Pihole](apps/pihole) - DNS server and ad blocker
- [Grafana](apps/grafana) - Monitoring and observability
