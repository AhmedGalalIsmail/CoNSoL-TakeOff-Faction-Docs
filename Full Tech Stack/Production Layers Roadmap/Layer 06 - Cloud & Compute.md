# Layer 06 - Cloud & Compute

## Purpose

Provide scalable, secure, and manageable computing resources to run the application reliably.

The cloud layer manages infrastructure, compute, networking, storage, and orchestration.

---

## AI Agent Mission

Act as a Cloud Infrastructure Engineer responsible for:

- Provisioning compute resources
- Configuring network and storage
- Implementing scalable solutions
- Monitoring infrastructure
- Automating provisioning and scaling

---

## Objectives

- Deploy reliable infrastructure
- Ensure security and access control
- Enable autoscaling
- Optimize resource usage
- Enable disaster recovery
- Support high availability

---

## Required Deliverables

- Cloud architecture design
- Infrastructure as Code templates
- Network topology
- Auto-scaling policies
- Disaster recovery plan
- Monitoring & alerting configuration

---

## Execution Tasks

### Task Group 01 - Compute Resources

Agent must:

- Provision servers, VMs, or containers
- Define CPU, memory, and storage needs
- Configure images and base OS

Validation:

- Infrastructure matches spec
- Resources are monitored

---

### Task Group 02 - Networking

Agent must:

- Configure VPC, subnets, and routing
- Configure firewall and security groups
- Configure DNS, load balancers, and gateways

Validation:

- Network connectivity verified
- Security policies enforced

---

### Task Group 03 - Storage

Agent must:

- Provision object storage
- Configure block storage
- Set backup and replication policies

Validation:

- Storage accessible
- Redundancy tested

---

### Task Group 04 - Autoscaling & Load Balancing

Agent must:

- Set up horizontal scaling
- Set up vertical scaling
- Configure load balancing
- Monitor metrics for scaling triggers

Validation:

- Services scale under load
- Load balanced traffic evenly

---

### Task Group 05 - Infrastructure as Code

Agent must:

- Implement Terraform/CloudFormation scripts
- Version all infrastructure
- Test changes in dev environment

Validation:

- Infrastructure reproducible
- Changes auditable

---

### Task Group 06 - Security & Compliance

Agent must:

- Implement IAM roles
- Define access policies
- Encrypt resources
- Enable logging for compliance

Validation:

- Access control enforced
- Security audits passed

---

### Task Group 07 - Monitoring & Observability

Agent must:

- Monitor compute, storage, and network
- Set alerts on failures and thresholds
- Collect logs and metrics

Validation:

- Alerts trigger correctly
- Dashboards display correct metrics

---

## Anti-Patterns

- Hardcoded credentials
- Overprovisioning resources
- Lack of monitoring
- Manual scaling
- No disaster recovery

---

## Success Criteria

- Infrastructure provisioned reproducibly
- Autoscaling and load balancing verified
- Security policies enforced
- Monitoring and alerts active
- Disaster recovery plan tested