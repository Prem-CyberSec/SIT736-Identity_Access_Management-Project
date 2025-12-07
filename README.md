# SIT736 - Identity & Access Management Project

A comprehensive Identity and Access Management (IAM) implementation project developed as part of the SIT736: Identity, Access Management, and Physical Security course at Deakin University.

## Overview

This project demonstrates the implementation of modern IAM principles including authentication, authorization, and accountability mechanisms. The implementation covers role-based access control (RBAC), multi-factor authentication (MFA), and secure identity management practices aligned with industry standards.

## Key Features

### Authentication & Authorization
- **Multi-factor Authentication (MFA)** implementation for enhanced security
- **Role-Based Access Control (RBAC)** with hierarchical permission structures
- **Attribute-Based Access Control (ABAC)** for fine-grained access policies
- Session management and secure token handling

### Identity Management
- User lifecycle management (creation, modification, deletion)
- Group and role assignment mechanisms
- Centralized identity repository
- Password policies and passwordless authentication options

### Security Controls
- Principle of least privilege enforcement
- Regular access reviews and audit logging
- Accountability tracking for user activities
- Integration with authentication providers

## Project Structure

```
├── src/                    # Source code
├── config/                 # Configuration files
├── docs/                   # Documentation and reports
├── tests/                  # Unit and integration tests
└── README.md              # Project documentation
```

## Technologies Used

- **Keycloak** - Open-source Identity and Access Management solution
- Authentication frameworks and libraries
- Database for identity storage
- API security implementations

## Implementation Highlights

### RBAC Implementation
The project implements three core roles with distinct privileges:
- **Admin**: Full read/write access with administrative privileges
- **Editor**: Content modification capabilities
- **End-user**: Read-only access to authorized resources

### Security Features
- Comprehensive audit logging for accountability
- Conditional access controls
- Service account management for application-to-application authentication
- Real-time activity monitoring for anomaly detection

## Learning Outcomes

This project demonstrates understanding of:
- Authentication vs. Authorization vs. Accountability concepts
- Industry best practices for IAM implementation
- Security policy enforcement and compliance
- Integration of IAM solutions in enterprise environments

## Course Context

**Course**: SIT736 - Identity, Access Management and Physical Security  
**Institution**: Deakin University  
**Program**: Master of Cybersecurity

## Setup & Installation

```bash
# Clone the repository
git clone https://github.com/Prem-CyberSec/SIT736-Identity_Access_Management-Project.git

# Navigate to project directory
cd SIT736-Identity_Access_Management-Project

# Follow specific setup instructions in docs/
```

## Documentation

Detailed documentation includes:
- Architecture diagrams
- Authentication flow diagrams
- Role hierarchy models
- Security policy definitions
- Implementation guides

## Best Practices Implemented

- Phased deployment approach
- Comprehensive user training materials
- Regular access permission reviews
- Stakeholder engagement throughout development

## Author

**PremKumar Sharma**  
Cybersecurity Graduate Student | Deakin University

## License

Academic project for educational purposes.

---

*This project demonstrates practical application of IAM principles in securing modern applications and managing digital identities effectively.*