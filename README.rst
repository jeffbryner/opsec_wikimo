====================================
The Mozilla Operations Security Team
====================================

OpSec assists Mozillians in defining and operating security controls to ensure that data at Mozilla is protected consistently across the organization.

- we help you define the risks around your services and data
- we help projects design and implement security controls
- we maintain a risk-based inventory of systems and their functional security controls to help Mozilla management determine where to invest in security measures
- we develop a catalog of services and tools that help you appropriately secure your data
- we respond to security investigations and incidents
- we provide baseline practices and assist teams in defining their security standards

Service Catalog
===============

The services listed below are available to everyone working on the Mozilla project. Contact us directly for more details on any of the services listed below.

.. Template
   Service label
   ~~~~~~~~~~~~~
   :Support commitment: FILLME
   :Costs: FILLME
   :Service request: FILLME
   
   Description:
   FILLME-FEWLINES
   
   What you can do with this service:
   FILLME LIST


Service: Security Information and Event Management (SIEM)
---------------------------------------------------------

:Support commitment:

- 5k-10k events per second capacity
- 10 days of event storage online, 1 year offline in AWS glacier

:Costs: Engineering time, compute resources, AWS archiving
:Service request: 

Description
~~~~~~~~~~~

OpSec develops and operates MozDef as a service to assist Mozilla projects in defending  their operations. Mozilla
systems can send events, logs and other data to MozDef to  be automatically correlated and consistently treated.

What you can do with this service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Send events to be stored
- Search events
- Create dashboards summarizing events
- Create alerts
- Correlate on events
- Collaborate in real time with incident handlers
- Integrate systems into automated response to security events


Service: NSM: Network Security Monitoring
-----------------------------------------

:Support commitment: best effort, non-HA A statistical approach is used so results might not be 100% accurate by design. Logs limited to between 3 and 10 days.
:Costs: traffic interception capabilities, servers for running it, disk space for log storage.
:Service request: file the Operations Security bug

Description
~~~~~~~~~~~

The  goal of the NSM project is to provide useful context information for  both the IR and early detection of possible intrusions.

What you can do with this service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

Coverage of traffic at the entry point and key routing points of Mozilla's data centers including firewalls and Load Balancers.
Interfaces and utilities to facilitate and accelerate Incident Response
Detection of various network level anomalies that might suggest either intrusion or network issues.
Give a lot of statistical information that traditional monitoring systems can't, from the application level protocols.
Make  sense out of the data at the higher protocol levels, sessions and  packets.


Service: Real-time systems forensic
-----------------------------------

:Support commitment: business hours availability. 1 year data retention.
:Costs: platform supported by OpSec. Subscriber’s handles the cost of provisioning and monitoring the agents on target systems.
:Service request: `request bug <https://bugzilla.mozilla.org/enter_bug.cgi?assigned_to=jvehent%40mozilla.com&blocked=896480&bug_file_loc=http%3A%2F%2F&bug_ignored=0&bug_severity=normal&bug_status=NEW&cf_blocking_b2g=---&cf_fx_iteration=---&cf_fx_points=---&component=Security%20Assurance%3A%20Operations&contenttypemethod=autodetect&contenttypeselection=text%2Fplain&defined_groups=1&flag_type-4=X&flag_type-607=X&flag_type-800=X&flag_type-803=X&form_name=enter_bug&groups=infra&maketemplate=Remember%20values%20as%20bookmarkable%20template&op_sys=Linux&priority=--&product=mozilla.org&rep_platform=x86_64&short_desc=[mig]%20Subscription%20request%20for%20%3Cteam%20name%3E&status_whiteboard=[mig]&target_milestone=---&version=other>`_

Description
~~~~~~~~~~~

OpSec operates a client/server platform to facilitate the investigation of large numbers of systems in parallel. We
distribute agents across endpoints of an infrastructure that can be queried in real-time through a central console. This
service uses Mozilla InvestiGator (MIG).

What you can do with this service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Search filesystems by filename, content and hashes.
- Check, add and delete user accounts.
- Read and write host firewall rules.
- Search through the memory of a live system.
- Search for MAC addresses, IP addresses and connected IPs.
- Verify conformity of a configuration with OpSec best practices.

Service: Test driven systems security
-------------------------------------

:Support commitment: business hours availability. 1 year data retention.
:Costs: platform supported by OpSec. Subscriber’s handles the cost of provisioning and monitoring the agents on target systems.
:Service request: `request bug <https://bugzilla.mozilla.org/enter_bug.cgi?assigned_to=jvehent%40mozilla.com&blocked=896480&bug_file_loc=http%3A%2F%2F&bug_ignored=0&bug_severity=normal&bug_status=NEW&cf_blocking_b2g=---&cf_fx_iteration=---&cf_fx_points=---&component=Security%20Assurance%3A%20Operations&contenttypemethod=autodetect&contenttypeselection=text%2Fplain&defined_groups=1&flag_type-4=X&flag_type-607=X&flag_type-800=X&flag_type-803=X&form_name=enter_bug&groups=infra&maketemplate=Remember%20values%20as%20bookmarkable%20template&op_sys=Linux&priority=--&product=mozilla.org&rep_platform=x86_64&short_desc=[mig]%20Subscription%20request%20for%20%3Cteam%20name%3E&status_whiteboard=[mig]&target_milestone=---&version=other>`_

Description
~~~~~~~~~~~

TBD.

Service: Rapid Risk Assessment (RRA)
------------------------------------

:Support commitment: Response within a week.
:Costs: 30 minutes meeting with OpSec.
:Service request: `Open a bug <https://bugzilla.mozilla.org/enter_bug.cgi?product=mozilla.org&component=Security%20Assurance%3A%20Operations>`_

Description
~~~~~~~~~~~

The Rapid Risk Assessment (also called Rapid Risk Analysis) is a 30 minutes or less discussion about the potential risks of a project.
The RRA (pronounced RA) is high level and lightweight.

What you can do with this service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Quickly identify risks related to your project, service, tool, etc.
- Make decision making more efficient: spend more time where it matters on your project, service, tool (where the risks are).
- Get your service recorded in a risk heatmap to compare it with other services.
- Find out if you need a security review.


Service: Security Review
------------------------

:Support commitment: Response within a week.
:Costs: One or more meeting with OpSec.
:Service request: `Open a bug <https://bugzilla.mozilla.org/enter_bug.cgi?product=mozilla.org&component=Security%20Assurance%3A%20Operations>`_

Description
~~~~~~~~~~~

Security reviews are in depth reviews of the security of a project. They are more specific, thorough and more time
consuming than Rapid Risk Assessments (RRA). An RRA is required before performing a security review that is more than a
quick reply in a bug.

What you can do with this service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Get an in depth security review of your project with technical details, recorded in a document.
- Get a quick in-line reply in Bugzilla (responses sec-review flag).
- Get architectural tips from the security point of view at the project design time.

Security Incident Response
--------------------------

:Support commitment: FILLME
:Costs: FILLME
:Service request: `Open a bug <https://bugzilla.mozilla.org/enter_bug.cgi?product=mozilla.org&component=Security%20Assurance%3A%20Incident>`_

Description
~~~~~~~~~~~

The Security Incident Response process is designed to facilitate a rapid coordinated response to system and network security incidents.

What you can do with this service
~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~~

- Incident investigation.
- Coordinated response.
- Containment, eradication, and recovery of security incident
- Notification and communication of incident related details, activities, status, and resolution. 
- Post Mortem.

Tools catalog
=============

.. Template:
   Tool label
   ~~~~~~~~~~~~~
   
   :Services provided: FILLME [‘Development’, ‘Hosting’]
   :Maturity: FILLME [‘Alpha’, ‘Beta’, ‘Release Candidate’,      ‘Production’]
   :Source code: <FILLME-URL>

   Description:
   FILLME-FEWLINES

System call auditing: Audisp-json
---------------------------------

:Services provided: Auditing
:Maturity: Release Candidate
:Source code: <https://github.com/gdestuynder/audisp-json>

Description
~~~~~~~~~~~

Linux Audit can record information about any system call, and relay it to a user-space process. Audisp-json is a plugin
for Auditd which takes these events, correlate them and issue a standard, single JSON message in the MozDef format -
over HTTPS (it does not use syslog).

Audisp-json coupled with MozDef provide a strong solution to monitor and correlate security event on linux systems. It
supersede the audisp-cef plugin.

Trophy Store
------------

:Services Provided: Development
:Maturity: Alpha
:Source Code: <https://github.com/gene1wood/trophy-store>

Description
~~~~~~~~~~~

A web application to automate and simplify the process of requesting or renewing certificates, generating SSL keys,
issuing certificates and deploying the resulting keys and certificates into software load balancers.

MIG: Mozilla InvestiGator
-------------------------

:Services Provided: Endpoint Security
:Maturity: Production
:Source Code: <http://mig.mozilla.org>

Description
~~~~~~~~~~~

MIG is a platform to perform investigative surgery on remote endpoints. It enables investigators to obtain information
from large numbers of systems in parallel, thus accelerating investigation of incidents.

MIG is composed of agents installed on all systems of an infrastructure. The agents can be queried in real-time using a
messaging protocol implemented in the MIG Scheduler. MIG has an API, a database, RabbitMQ relays and a console client.
It allows investigators to send actions to pools of agents, and check for indicator of compromise, verify the state of a
configuration, block an account, create a firewall rule, update a blacklist and so on.


MozDef: The Mozilla Defense Platform
------------------------------------

:Services Provided: Development
:Maturity: Production
:Source Code: <http://mozdef.com>

Description
~~~~~~~~~~~

The Mozilla Defense Platform (MozDef) seeks to automate the security incident handling process and facilitate the
real-time activities of incident handlers.

Goals:

- Provide a platform for use by defenders to rapidly discover and respond to security incidents.
- Automate interfaces to other systems like bunker, banhammer, mig
- Provide metrics for security events and incidents
- Facilitate real-time collaboration amongst incident handlers
- Facilitate repeatable, predictable processes for incident handling
- Go beyond traditional SIEM systems in automating incident handling, information sharing, workflow, metrics and response automation




Contact
=======

Email us at **opsec** [at] mozilla.com. For confidential information, encrypt
your email using our public PGP: `Operations Security (Mozilla Security
Assurance) <http://gpg.mozilla.org/pks/lookup?op=get&search=0xBC17301B491B3F21>`_ .

For security incidents, file a bug in Bugzilla under the component
`mozilla.org :: Security Assurance: Incident` .

Our public mailing list is `opsec [at]
lists.mozilla.org <https://lists.mozilla.org/listinfo/opsec>`_.

Our IRC channel is #security in `irc.mozilla.org <irc://irc.mozilla.org/security>`_.

Members
=======

* `Joe Stevensen <https://mozillians.org/en-US/u/joes/>`_ [:joes]
* `Guillaume Destuynder <https://mozillians.org/en-US/u/kang/>`_ [:kang]
* `Michal Purzynski <https://mozillians.org/en-US/u/michalpurzynski/>`_ [:michal`]
* `Julien Vehent <https://mozillians.org/en-US/u/jvehent/>`_ [:ulfr]
* `Jeff Bryner <https://mozillians.org/en-US/u/jbryner/>`_ [:jeff]
* `Gene Wood <https://mozillians.org/en-US/u/gene/>`_ [:gene]
