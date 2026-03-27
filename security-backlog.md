# Security Backlog: SecureCloud Vault

## Epic 1: Identity & Access (AuthN/AuthZ)
- [ ] [BACKLOG-01] Provision Cognito User Pool with Password Policy.
- [ ] [BACKLOG-02] Enforce Mandatory Multi-Factor Authentication (MFA).
- [ ] [BACKLOG-03] Configure App Client with short-lived Refresh/Access tokens.
- [ ] [BACKLOG-04] Create Least-Privilege IAM Execution Roles for Lambda.
- [ ] [BACKLOG-05] Implement Cognito Post-Confirmation trigger for user profile creation.

## Epic 2: Data Protection & Encryption
- [ ] [BACKLOG-06] Create AWS KMS Customer Managed Key (CMK) for S3.
- [ ] [BACKLOG-07] Enable S3 Default Encryption using the CMK.
- [ ] [BACKLOG-08] Implement S3 Block Public Access at the bucket level.
- [ ] [BACKLOG-09] Configure DynamoDB encryption at rest.
- [ ] [BACKLOG-10] Implement Logic for S3 Pre-signed URLs (Temporary access).

## Epic 3: Infrastructure & Edge Security
- [ ] [BACKLOG-11] Deploy CloudFront Distribution with Origin Access Control (OAC).
- [ ] [BACKLOG-12] Associate AWS WAF with CloudFront (SQLi and XSS protection).
- [ ] [BACKLOG-13] Implement WAF Rate-limiting to prevent Brute Force.
- [ ] [BACKLOG-14] Configure TLS 1.2 minimum on all endpoints.

## Epic 4: Logging & Monitoring
- [ ] [BACKLOG-15] Enable CloudTrail (Global) for API auditing.
- [ ] [BACKLOG-16] Enable S3 Server Access Logging.
- [ ] [BACKLOG-17] Setup CloudWatch Alarms for "AccessDenied" API calls.
- [ ] [BACKLOG-18] Enable AWS GuardDuty for threat detection.

## Epic 5: Security Testing & CI/CD
- [ ] [BACKLOG-19] Integrate Checkov/Tfsec for Terraform static analysis.
- [ ] [BACKLOG-20] Scan Docker Images (if using containers) or Lambda layers with Trivy.
- [ ] [BACKLOG-21] Perform manual OWASP ZAP scan on the frontend.
