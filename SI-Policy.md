# System and Information Integrity Policy

Bixal Solutions has a goal to ensure information integrity throughout its offerings. Services
to support this effort are available by contract and may be required by regulation or
law. When possible, support for this effort may cover one or more controls within these
families:

* Awareness and Training (AT)
* Configuration Management (CM)
* Contingency Planning (CP)
* Incident Response (IR)
* Maintenance (MA)
* Media Protection (MP)
* Physical and Environmental Protection (PE)
* Personnel Security (PS)
* System and Information Integrity (SI)

## Purpose

Ensures information systems have not been compromised through system errors, malicious
attacks, or unauthorized access during operation and transmission.

## Scope

See the [Bixal Solutions Common Control Policy](BixalSolutions-Common-Control-Policy.md).

## Policy overlay

For information on roles and responsibilities, management commitment, coordination among
organizational entities, compliance, reviews, and updates please see the
[Bixal Solutions Common Control Policy](BixalSolutions-Common-Control-Policy.md).

## Procedures

The Bixal Solutions team identifies system flaws, tracks and reports them, and corrects them.

The Bixal Solutions Operations team monitors upstream projects for new releases, implements
the new releases (including promptly installing newly-released security-relevant patches),
and tests patches for effectiveness and potential side effects on information systems
before installation. The testing takes place in development and test environments.

Flaws discovered during security assessments, continuous monitoring, incident response
activities, and information system error handling are addressed through the Bixal Solutions
configuration management process.

See SI-2.

Bixal Solutions employs tools at information system entry and exit points to detect and
eradicate malicious code with real-time scans. The Bixal Solutions Operations team follows
the [Security Incident Response
Guide @todo link](https://github.com/NuCivic/healthdata/wiki/incident-response-plan) upon detection
of any potential security incident.

Bixal Solutions-developed open source code that is used in the Bixal Solutions products and
services is scanned using static analysis tools. When anyone proposes a change to the code
(a pull request), the static analysis tool automatically runs and displays results.

See SI-3.
