# Homelab Argocd


### Reference docs for cert-manager
- (Installing with helm)[https://cert-manager.io/docs/installation/helm/#installing-with-helm]
- (Using vault)[https://cert-manager.io/docs/configuration/vault/]
- (Troubleshooting)[https://cert-manager.io/docs/faq/troubleshooting/]
- (Authenticating via an approle)[https://cert-manager.io/docs/configuration/vault/#authenticating-via-an-approle]
- (issuer)[https://cert-manager.io/docs/concepts/issuer/]

### Reference for hashicorp vault
- (Install vault using helm charts)[https://www.vaultproject.io/docs/platform/k8s/helm/run]
- (Build Your Own Certificate Authority CA)[https://learn.hashicorp.com/tutorials/vault/pki-engine]
- (Policies)[https://learn.hashicorp.com/tutorials/vault/getting-started-policies]
- (Vault envs for cli)[https://www.vaultproject.io/docs/commands]
- (AppRole Auth Method)[https://www.vaultproject.io/docs/auth/approle]


### Reference kubernetes
- (debug dns)[https://kubernetes.io/docs/tasks/administer-cluster/dns-debugging-resolution/]

### Other references
- (Using Hashicorp Vault as a Certificate issuer in Cert Manager)[https://medium.com/nerd-for-tech/using-hashicorp-vault-as-a-certificate-issuer-in-cert-manager-9e19d7239d3d]
- (fix argocd redirects with istio)[https://github.com/argoproj/argo-cd/issues/2784#issuecomment-662330176]

### Command Reference

```
export VAULT_ADDR=""
export VAULT_ROOT_TOKEN=""
kubectl exec -i -t dnsutils -- nslookup
```