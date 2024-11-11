# AWS Well-Architected Framework - Security Pillar

## AWS account management and separation
  - SEC01-BP01: Separate workloads using accounts
  - SEC01-BP02: Secure account root user and properties


## Operating your workloads securely
  - SEC01-BP03: Identify and validate control objectives
  - SEC01-BP04: Stay up to date with security threats and recommendations
  - SEC01-BP05: Reduce security management scope
  - SEC01-BP06: Automate deployment of standard security controls
  - SEC01-BP07: Identify threats and prioritize mitigations using a threat model
  - SEC01-BP08: Evaluate and implement new security services and features regularly


## Identity and access management

### Identity management
  - SEC02-BP01: Use strong sign-in mechanisms
  - SEC02-BP02: Use temporary credentials
  - SEC02-BP03: Store and use secrets securely
  - SEC02-BP04: Rely on a centralized identity provider
  - SEC02-BP05: Audit and rotate credentials periodically
  - SEC02-BP06: Employ user groups and attributes

### Permissions management
  - SEC03-BP01: Define access requirements
  - SEC03-BP02: Grant least privilege access
  - SEC03-BP03: Establish emergency access process
  - SEC03-BP04: Reduce permissions continuously
  - SEC03-BP05: Define permission guardrails for your organization
  - SEC03-BP06: Manage access based on lifecycle
  - SEC03-BP07: Analyze public and cross-account access
  - SEC03-BP08: Share resources securely within your organization
  - SEC03-BP09: Share resources securely with a third party


## Detection
  - SEC04-BP01: Configure service and application logging
  - SEC04-BP02: Capture logs, findings, and metrics in standardized locations
  - SEC04-BP03: Correlate and enrich security alerts
  - SEC04-BP04: Initiate remediation for non-compliant resources


## Infrastructure protection

### Protecting networks
  - SEC05-BP01: Create network layers
  - SEC05-BP02: Control traffic flow within your network layers
  - SEC05-BP03: Implement inspection-based protection
  - SEC05-BP04: Automate network protection

### Protecting compute
  - SEC06-BP01: Perform vulnerability management
  - SEC06-BP02: Provision compute from hardened images
  - SEC06-BP03: Reduce manual management and interactive access
  - SEC06-BP04: Validate software integrity
  - SEC06-BP05: Automate compute protection


## Data protection

### Data classification
  - SEC07-BP01: Understand your data classification scheme
  - SEC07-BP02: Apply data protection controls based on data sensitivity
  - SEC07-BP03: Automate identification and classification
  - SEC07-BP04: Define scalable data lifecycle management

### Protecting data at rest
  - SEC08-BP01: Implement secure key management
  - SEC08-BP02: Enforce encryption at rest
  - SEC08-BP03: Automate data at rest protection
  - SEC08-BP04: Enforce access control

### Protecting data in transit
  - SEC09-BP01: Implement secure key and certificate management
  - SEC09-BP02: Enforce encryption in transit
  - SEC09-BP03: Authenticate network communications


## Incident response

### AWS incident response

### Design goals of cloud response

### Preparation
  - SEC10-BP01: Identify key personnel and external resources
  - SEC10-BP02: Develop incident management plans
  - SEC10-BP03: Prepare forensic capabilities
  - SEC10-BP04: Develop and test security incident response playbooks
  - SEC10-BP05: Pre-provision access
  - SEC10-BP06: Pre-deploy tools
  - SEC10-BP07: Run simulations

### Operations

### Post-incident activity
  - SEC10-BP08: Establish a framework for learning from incidents

## Application security
  - SEC11-BP01: Train for application security
  - SEC11-BP02: Automate testing throughout the development and release lifecycle
  - SEC11-BP03: Perform regular penetration testing
  - SEC11-BP04: Conduct code reviews
  - SEC11-BP05: Centralize services for packages and dependencies
  - SEC11-BP06: Deploy software programmatically
  - SEC11-BP07: Regularly assess security properties of the pipelines
  - SEC11-BP08: Build a program that embeds security ownership in workload teams