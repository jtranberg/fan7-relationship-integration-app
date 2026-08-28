# Security Policy

Fan7 handles automotive operational information, customer information, vehicle records, and integration data. Security and privacy are treated as product requirements throughout design, development, deployment, and operation.

## Public Repository Scope

This repository contains approved public documentation and product materials. It does not contain Fan7 production source code, customer data, credentials, internal endpoints, deployment configuration, or proprietary business logic.

## Security Principles

Fan7's current security architecture includes:

- authenticated application sessions;
- role-based authorization;
- tenant-aware access controls;
- protected application and integration routes;
- isolated tenant operating contexts;
- controlled handling of integration credentials;
- filtered responses for AI-accessible tools; and
- human oversight for consequential decisions.

Security claims in this repository describe Fan7's documented practices and architecture. They do not represent third-party certification unless a certification is explicitly named.

## Reporting a Vulnerability

Please do not disclose a suspected vulnerability through a public GitHub issue, discussion, social-media post, or pull request.

Report security concerns privately through the contact channel at [App Intelligence.ca](https://appintelligence.ca/). Include:

- the affected feature or page;
- a clear description of the observed behaviour;
- reproducible steps where safe;
- potential impact; and
- supporting screenshots or logs with personal information removed.

Do not access, alter, retain, or share customer information while investigating a suspected issue. Do not perform denial-of-service testing, social engineering, credential attacks, or destructive testing.

## Response Process

Reports are reviewed, validated, prioritized, and addressed according to their potential impact. App Intelligence.ca may request additional information and will coordinate disclosure timing when appropriate.

For additional information, visit the [Fan7 Trust Center](https://fan7.netlify.app/trust).
