# Week 3 – Data Security Controls Implementation

## 1. Objective

The objective of this implementation plan is to deploy practical data security controls in a telecom network environment. The plan converts the risks identified during the previous risk assessment into measurable technical and operational controls.

Telecom systems process sensitive customer, authentication, network and service information. Therefore, controls must protect confidentiality, integrity and availability while maintaining reliable network operations.

## 2. Control Selection and Justification

### 2.1 Role-Based Access Control (RBAC)

RBAC will restrict access according to job responsibilities. Users will receive only the permissions required for their assigned role.

**Reason:** Excessive privileges can allow compromised accounts or insiders to access sensitive systems.

**Implementation:** Create roles, assign minimum required permissions, remove unused accounts and review privileged access regularly.

### 2.2 Multi-Factor Authentication (MFA)

MFA will be enabled for privileged users, administrators and remote access.

**Reason:** A stolen password alone should