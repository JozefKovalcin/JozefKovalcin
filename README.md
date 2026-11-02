# Jozef Kovalčín

MSc Computer Networks student (TUKE, expected 2027). IT operations background, now building delivery automation: CI/CD pipelines, containerised workloads and GitOps deployments. Networking and security depth from CCNA/ENCOR and applied cryptography work. Currently focused on building Tor and Nym mixnet clients for embedded systems.

Based in Prešov, Slovakia. Open to junior DevOps / platform / SRE roles (hybrid Košice, Prešov; remote from Slovakia).

## Currently building

**[ReleaseLab](https://github.com/JozefKovalcin/releaselab)** — status: work in progress

NestJS REST API used as the target workload for a delivery chain: GitLab CI (build, test, image build, registry push), deployment to a local Kubernetes cluster, ArgoCD for GitOps sync, and HashiCorp Vault for secrets. The goal is one working end-to-end path.

**Verified:** GitHub Actions build, automated HTTP tests, Docker image packaging and artifact upload; local Vault scoped-token secret retrieval and denied-path tests; GitOps update and rollback scripts tested against isolated Git repositories.

**Configured:** five-stage GitLab pipeline, Kubernetes Deployment and Service, Kustomize overlay, ArgoCD application with automatic sync and self-healing, Vault policy and JWT authentication role.

**Still open:** live GitLab CI and registry publishing, GitLab ID token authentication with Vault, ArgoCD sync/self-healing on kind, and deployment/rollback verification through `/version`.

**[Tor and Nym mixnet clients for embedded systems](https://github.com/JozefKovalcin/Tor-and-NymMixNet-Clients-for-embended-systems)** 

Master thesis. Minimal Tor and Nym mixnet clients targeting constrained embedded environments. 

## Selected projects

**[Bio-Token-Auth-FIDO2](https://github.com/JozefKovalcin/Bio-Token-Auth-FIDO2)** · TypeScript, Kotlin, Next.js, PostgreSQL

Multi-factor authentication prototype: FIDO2/WebAuthn with YubiKey, TOTP and Android biometrics. Covers credential lifecycle, attestation flows and integrating a second factor into an application.

**[secure-file-transfer-sake](https://github.com/JozefKovalcin/secure-file-transfer-sake)** · C, sockets

Bachelor thesis, 2025. Encrypted TCP file transfer using a SAKE-inspired authenticated key exchange, Argon2 derivation, ChaCha20-Poly1305 and key rotation. Companion repository [secure-file-transfer-x25519-baseline](https://github.com/JozefKovalcin/secure-file-transfer-x25519-baseline) is the simpler v1 used as a comparison baseline.

**[sportbuddy-fullstack-ai](https://github.com/JozefKovalcin/sportbuddy-fullstack-ai)** · TypeScript, Next.js, PostgreSQL, Prisma, Docker

Team project for organising local sports activities. Dockerised local stack, AI-assisted search and activity creation. Top 20 at Živé IT projekty 2026.

**[workout-progress-tracking-pwa](https://github.com/JozefKovalcin/workout-progress-tracking-pwa)** · TypeScript, Vite, Playwright, Firebase

PWA with offline support, automated tests and documented local/cloud workflows.

## Skills

- **Delivery:** Git, GitHub Actions, Docker, Docker Compose, Bash; GitLab CI, Kubernetes, ArgoCD and Vault in the ReleaseLab lab, with validation status above
- **Networking:** TCP/IP, routing, switching, CCNA
- **Security:** authentication flows, FIDO2/WebAuthn, key exchange, encryption, secret handling
- **Systems:** Linux, Windows Server, C, sockets, troubleshooting
- **Web and data:** TypeScript, React, Next.js, PostgreSQL, SQL, Prisma

## Certification

Cisco Certified Network Associate (CCNA), February 2025

## Course

Cisco Enterprise ENCOR (350-401), February 2026

## Notes on the crypto projects

Both file-transfer repositories are academic work. They document their own cryptographic limitations and have not been independently audited. Treat them as implementation exercises, not as libraries to build on.

## Contact

[LinkedIn](https://www.linkedin.com/in/jozef-kovalcin-5b7072374/) · jozefkovalcin@gmail.com
