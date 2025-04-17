# Configuration and Change Management

`2025.04.16`

ClearHealth standardizes and automates configuration management through the use
of automation scripts, as well as, documentation of all changes to production
systems and networks. Automation tools, such as Red gate and GitHub, must be
used when deploying production changes to ClearHealth systems according to
established and tested policies, and are used as part of our Disaster Recovery
plan and process.

## Policy Statements

ClearHealth policy requires that:

(a) All production changes, including but not limited to, software deployment,
feature toggle enablement, network infrastructure changes, and access control
authorization updates, must be invoked through an approved change management
process.

(b) Each production change must maintain complete traceability to fully document
the request, including requestor, date/time of change, actions taken and
results.

(c) Each production change must be fully tested prior to implementation.

(d) Each production change must include a rollback plan to back out the change
in the event of failure.

(e) Each production change must include proper approval.

- The approvers are determined based on the type of change.
- Approvers must be someone other than the author/executor of the change.
- Approvals may be automatically granted if certain criteria is met. The
  auto-approval criteria must be pre-approved by the Security Officer and fully
  documented and validated for each request.

(f) Each endpoint (user workstations or cloud VM) must be persistently protected
by a network-based malware protection agent which runs scans multiple times a
week and is updated by the vendor as new malware definitions are discovered.
Logs must be maintained by the service or by ClearHealth.

(g) Each endpoint must have appropriate restrictions limiting the potential for
abuse or misuse. Workstations are enrolled in Jamf and managed by Optum,  which
enables restriction of functionality to the bare minimum needed to accomplish
the user's duty. Server environments must have access limitations configured to
prevent misuse, accidental changes, or damage that can be done by a nefarious
actor.
