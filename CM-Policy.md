# Configuration Management

The Bixal Solutions Configuration Management Policy covers:

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

Bixal Solutions works to maintain information systems in an immutable and ephemeral state as much as
feasible. To the greatest degree possible, the configuration of systems should be
maintained in code so that at any time they can be rebuilt and replaced from a known and
secure baseline state. Logging should be forwarded to a Security Information and Event Management system
where possible.

## Scope

See the [Bixal Solutions Common Control Policy](BixalSolutions-Common-Control-Policy.md).

## Policy overlay

For information on roles and responsibilities, management commitment, coordination among
organizational entities, compliance, reviews, and updates please see the
[Bixal Solutions Common Control Policy](BixalSolutions-Common-Control-Policy.md).

## Procedures

A current baseline configuration is always available such that the site can be regenerated
or rolled back should unauthorized or failing changes be applied.

See CM-2.

Bixal Solutions Operations works with relevant stakeholders, decision-makers, and
Bixal Solutions Information Security to determine any necessary changes, and their impacts,
to the configuration of the system. All changes to the configuration of the system are
tracked in Git. The process is overseen by the Change Control Board (CCB) consisting of
the System Owner, Project Manager and Bixal Solutions Development during sprint planning
meetings. All changes undergo peer review, behavioral and security testing, and are made
to reasonably ensure the configurations require the least amount of functionality
necessary.

See CM-3, CM-4, CM-5, CM-7, CM-8.

The Bixal Solutions team uses the Agile development methodology to govern configuration
changes with configuration captured in code and issue tickets. In some cases, a detailed
Configuration Plan document will be created to detail specific needs for a client.

See CM-6, CM-9.
