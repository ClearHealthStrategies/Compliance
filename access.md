# Access

`2025.04.16`

Access to ClearHealth systems and applications is limited for all users,
including but not limited to: workforce members, volunteers, business
associates, contracted providers, consultants, and any other entity. Such access
is allowable only on a minimum necessary basis. All users are responsible for
reporting an incident of unauthorized user or access of the organization's
information systems.

These safeguards have been established to address the HIPAA Security regulations
and industry best practices.

## Policy Statements

### Access Control Policy

ClearHealth policy requires that:

(a) Access to all computing resources, including servers, end-user computing
devices, network equipment, services, and applications must be protected by
strong authentication, authorization, and auditing.

(b) Interactive user access must be associated with an account or login unique
to each user.

(c) All credentials, including user passwords, service accounts, and access
keys, must meet the length, complexity, age, and rotation requirements defined
in ClearHealth's security standards.

(d) Use strong password and multi-factor authentication (MFA) whenever possible
to authenticate to all computing resources (including both devices and
applications).

(e) MFA is required to access any critical system or resource, including but not
limited to, resources in ClearHealth's production environments.

(f) Unused accounts, passwords, and access keys must be removed within 30 days.

(g) A unique access key or service account must be used for different
application or user access.

(h) Authenticated sessions must time out after a defined period of inactivity.

(i) Default accounts must be locked, disabled, or have passwords changed.

​(j) Ports, services, and applications installed on a computer or network
systems, which are not specifically required for business functionality, are
disabled or removed.

### Access Authorization and Termination

ClearHealth policy requires that:

(a) Avoid the need to grant elevated privileges to users as much as possible.

(b) Access authorization shall be implemented using role-based access control
(RBAC) or similar mechanism.

(c) Standard access based on a user's job role may be pre-provisioned during
employee onboarding. All subsequent access requests to computing resources must
be approved by the requestor's manager, prior to granting and provisioning of
access.

(d) Access to critical resources, such as production environments, must be
approved by the Security Team in addition to the requestor's manager.

(e) Access must be reviewed on a regular basis and revoked if no longer needed.

(f) Upon termination of employment, all system access must be revoked, and user
accounts terminated within 24 hours or one business day, whichever is shorter.

(g) All system access must be reviewed, at least, annually and whenever a user's
job role changes.

(h) All monitoring of authorized and unauthorized access follows legal
requirements.

​(i) Facilitates information sharing by enabling authorized users to determine
whether access authorizations assigned to business partners match the access
restrictions on information for specific circumstances in which user discretion
is allowed.

(j) Facilitates sharing by employing manual processes or automated mechanisms to
assist users in making information sharing/collaboration decisions.

### Shared Secrets Management

ClearHealth policy requires that:

(a) Use of shared credentials/secrets must be minimized and only approved when
based on exceptions.

(b) If required by business operations, secrets/credentials must be shared
securely and stored in encrypted vaults that meet the ClearHealth data
encryption standards.

(c) Usage of a shared secret to access a critical system or resource must be
supported by a complimenting solution to uniquely identify the user.

### Privileged Access Management

ClearHealth policy requires that:

(a) Users must not log in directly to systems as a privileged user.

- A privileged user is someone who has administrative access to critical
  systems, such as an Active Directory Domain Administrator and root user to a
  Linux/Unix system.

(b) Privileged access must only be gained through a proxy, or equivalent, that
supports strong authentication, such as MFA, using a unique individual account
with full auditing of user activities.

(c) Direct administrative access to production systems must be kept to an
absolute minimum.
