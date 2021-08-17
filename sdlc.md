# Secure Software Development and Product Security
`2021.08.03`

The ClearHealth development team follows the latest security best practices
when developing software, and automates security testing throughout the development
lifecycle whenever possible. Security is integrated into all phases
of the ClearHealth product development lifecycle, requiring all developers to adhere to the following guidelines:

* Secure Design:
    - Application Risk classification
    - Security requirement definition
    - Third-party security requirements for code/tools/services
    - Secure Application design / Feature Request
    - Threat modeling
    - Application Data Flow analysis

* Secure Development and Testing:
    - Secure coding guidelines
    - Peer review
    - Security testing that includes:
        - Open source security analysis
        - Static secure code analysis
        - Dynamic security analysis
        - External Vulnerability Scans
        - Annual Penetration Testing by a qualified 3rd Party

* Remediation:
    - Follows defined vulnerability management lifecycle
    - Ensures no high risk security vulnerability is in production
    - Ensures no license conflicts

Details about the ClearHealth software application architecture and security are documented on the Confluence page.
The following policies must be reviewed by the Security Officer and updated if necessary on an annual basis.

Employees are notified when changes are made to the policy.  Additionally, employees are required to complete yearly attestations confirming adherence to the policies defined herein.

## Policy Statements

ClearHealth policy requires that:

(a) ClearHealth software engineering and product development is required to follow security best practices. Products are "Secure by Design" and "Secure by Default".

(b) Quality assurance activities must be performed, including peer code reviews prior to merging new code into the master branch. 

(c) Risk assessment activities (i.e. threat modeling) must be performed for a new product or major changes to an existing product.

(d) Security requirements must be defined, tracked, and implemented.

(e) Security analysis must be performed for any open source software and/or third-party components and dependencies included in ClearHealth's software products. Any software or service not meeting the requirements must have additional controls mitigating against vulnerabilities or an alternative must be used.

(f) Static application security testing (SAST) must be performed throughout development and prior to each release.

(g) Dynamic application security testing (DAST) must be performed prior to each release.

(h) All critical or high severity security findings must be remediated prior to each release.

(i) All critical or high severity vulnerabilities discovered post release must be remediated in the next release or within 30 days, whichever is sooner.

(j) Any exception to the remediation of a finding must be documented and approved by the Security Officer.

(k) Any exception to the security requirements of third party software or services must be documented and approved by the Security Officer, indicating all additional controls necessary to mitigate any additional security risk.

(l) All procedures, guidelines, and standards for development of the applications must be periodically reviewed, assessed, and updated as necessary by the Security Officer of the organization.

(m) All input fields must have appropriate input validation and error checking.

(n) Using or purchasing third-party software must follow the defined acquisition process and Risk Assessment Process.

(o) Software must be designed to grant users the minimum necessary privileges to provide the functionality required to meet the business need.

