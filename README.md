# Orbitcart Commerce

E-commerce platform built from 12 .NET 10 microservices, delivered with GitOps to AWS EKS.

## Services
| Service | Responsibility | Port |
|---|---|---|
| identity-api | Sign-up, login, JWT | 8081 |
| customer-api | Customer profiles and addresses | 8082 |
| catalog-api | Products and categories | 8083 |
| pricing-api | Prices, discounts, promotions | 8084 |
| inventory-api | Stock levels and reservations | 8085 |
| cart-api | Shopping carts | 8086 |
| order-api | Orders and order status workflow | 8087 |
| payment-api | Payments and refunds (simulated) | 8088 |
| shipping-api | Shipments and tracking | 8089 |
| notification-api | Email / SMS notifications | 8090 |
| review-api | Product reviews and ratings | 8091 |
| reporting-api | Sales reports | 8092 |

## Related repositories
- orbitcart-platform-pipelines – shared CI/CD
- orbitcart-terraform-modules – Terraform modules
- orbitcart-infra-live – Terragrunt environments
- orbitcart-gitops – ArgoCD desired state

## Status
🚧 Phase 1 – Foundation
