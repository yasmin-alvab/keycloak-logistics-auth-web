# keycloak-logistics-auth-web
Repository to register activities executed for the Keycloak implementation in a web solution for Logistics Traceability

### 1. Requirements & Analysis
- Documented user roles, access matrices, and authorization requirements for the web application.

### 2. Infrastructure Setup (AWS EC2)
- Provisioned an AWS EC2 instance and configured Security Groups with strict inbound/outbound traffic rules.
- Linked the custom domain to the EC2 public IP via DNS records.

### 3. Keycloak Deployment
- Set up Docker environment on the EC2 instance for container management.
- Deployed Keycloak and configured persistent database connectivity.

### 4. IAM & Keycloak Configuration
- Created and configured the application Realm and OIDC Client settings.
- Managed user accounts, created Realm roles, and assigned granular permissions.
- Defined fine-grained authorization policies for client access control.

### 5. Testing & Validation
- Validated end-to-end authentication flows (Login, Logout, and Secure Redirections).
- Verified Role-Based Access Control (RBAC) enforcement for both Standard and Admin roles.
- Inspected JWT tokens to validate payload integrity, claims, and signature expiration.
