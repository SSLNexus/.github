### SECURE - DEPLOY - DELEGATE

# SSLNexus

SSLNexus is a certificate lifecycle management platform for infrastructure, security, DevOps, enterprise, and managed service provider environments.

It is designed to automate certificate issuance, deployment, verification, renewal, discovery, and monitoring across distributed infrastructure while keeping private keys under customer control.

## Why SSLNexus

Certificate management becomes difficult when certificates are spread across servers, applications, network devices, vendors, customer environments, and different certificate authorities.

SSLNexus provides a central control plane for managing that lifecycle without requiring organisations to redesign their infrastructure or hand custody of their private keys to a third-party SaaS provider.

Key capabilities include:

- Automated certificate issuance, renewal, deployment, and verification
- Support for ACME, commercial CAs, and private PKI workflows
- Certificate discovery and lifecycle monitoring
- Linux and Windows deployment targets
- Network device and application integrations
- PostgreSQL-backed control plane
- Audit logging and operational history
- Role and entitlement-based access control
- Software Bill of Materials generation
- FIPS-oriented cryptographic build controls

## Private Keys Stay Private

A core SSLNexus design principle is that private keys should remain within the infrastructure that owns them.

SSLNexus coordinates certificate operations without requiring private keys to be uploaded to a central SaaS platform.

This reduces unnecessary key-custody boundaries and allows organisations to retain control over their cryptographic material.

## MSP HUB

MSP HUB extends SSLNexus for managed service providers operating across multiple customer environments.

It provides:

- Multi-organisation management
- Customer separation
- Central certificate visibility
- Organisation-level reporting
- Distributed deployment support
- Customer onboarding and offboarding
- Certificate capacity and entitlement management

The architecture is designed for environments where customer networks may be segmented, private, or unreachable directly from the central SSLNexus server.

## Vendor Portal

The Vendor Portal allows approved third parties to request certificates without receiving access to the main SSLNexus administration interface.

Access can be restricted by organisation, permitted domains, CIDR ranges, authentication controls, and assigned entitlements.

This provides a controlled workflow for vendor onboarding, certificate requests, and eventual offboarding.

## Operational Visibility

SSLNexus provides visibility across the certificate lifecycle, including:

- Certificate status and expiry
- Issuance and renewal history
- Deployment and verification results
- Automation failures
- Organisation activity
- Audit events
- Certificate usage trends

Dashboards provide operational visibility while detailed logs remain the underlying source of truth.

## Architecture Principles

SSLNexus is developed around several core principles:

- Private keys remain customer-controlled
- Certificate renewal includes post-deployment verification
- Network segmentation should not prevent automation
- Multi-tenancy should provide real organisational separation
- Security controls must be enforced server-side
- Customers receive packaged software rather than source-code-dependent deployments

## Free and Commercial Use

SSLNexus includes a permanent Free tier for certificate automation.

Additional capabilities such as MSP HUB, advanced enterprise functionality, increased certificate capacity, and support are controlled through centrally managed entitlements.

Enterprise deployments can support effectively unrestricted certificate capacity where applicable.

## Learn More

Website: https://sslnexus.com

Documentation: https://sslnexus.com/docs

---

**SSLNexus is built to make certificate lifecycle management predictable, automated, and operationally manageable across modern infrastructure.**
