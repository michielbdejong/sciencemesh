---
title: "How to join Science Mesh"
linkTitle: "How to join Science Mesh"
weight: 100
description: >
    The steps to join the Science Mesh
---

To join the Science Mesh, there are several formal and technical steps. If you encounter any problems during this process or have some general questions, feel free to [contact the Science Mesh administration](../support/). If you are joining with a Nextcloud site, you will need to set up a Reva server next to your Nextcloud server. Please see the [sciencemesh-nextcloud documentation](https://sciencemesh-nextcloud.readthedocs.io/en/latest/) on how to set this up.

1. In order to join the Science Mesh, you as the operator of a site are expected to
run one of supported EFSS (sync and share systems). FIXME link

1. Get into contact with a Science Mesh representative by using this [form]({{< ref "docs/How to join ScienceMesh/OnlineForm" >}})

1. After that, a Science Mesh representative will get back to you, detailing the next steps to get your site into the mesh.

1. While the system may support all necessary protocols (CS3 APIs, OCM) by itself (or you can
run any protocol-compatible implementation to your taste), it is quite
probable that you will need to install the [Reva IOP (interoperability platform)]({{< ref "docs/Technical-documentation/IOP" >}}) acting
as an Executive Module of your EFSS instance in the Science Mesh.

1. Your site needs to be [registered in the Central
Database]({{< ref "docs/Technical-documentation/Central-Database" >}}) where
metadata about your site and applications running there are stored.
A Science Mesh representative will create initial entries for your site,
but from there on, it will be your responsibility to keep these entries up to date.

1. [Monitoring and accounting]({{< ref "docs/Technical-documentation/Monitoring" >}}) is not a replacement of your standard
tools for operating your infrastructure but an addition; all information
collected by Science Mesh monitoring and accounting is strictly related to
Science Mesh operations, collecting just very high-level and aggregated
information.

1. [Formal steps]({{< ref "docs/Science-mesh-governance-and-operations" >}}) include
declaring compliance with policies, appointing a representative into the
governance structure of the infrastructure etc. As of January 2022, the
infrastructure is to be formally established, so this part of the
procedure will be covered later. It is neverheless recommended to get
familiar with the proposed structure, as this is the best time to comment
on it.

<!--
FIXME: I have asked Kuba and Pedro for an email addres helpdesk@sciencemesh.io
-->

<!--
From the Site Admission Procedure

Technical requirements
1. Each service must offer a way to be testable and verifiable from the outside by the
Operational Team to support automated testing.
1. The service MUST offer the required endpoints to perform these tests.
2. An account MUST be created in order to facilitate these tests.
3. These endpoints MUST be protected by some kind of authorisation mechanism.
4. It is only necessary to open these endpoints to the Operational Team; the Operational
Team will inform the site administrators in advance what IPs these tests will come from.
2. The service MUST support the Up-Test: This test will probe the service to see if it is up and
running, i.e. whether it can respond to a simple query on its endpoint.
3. An endpoint to collect accounting metrics MUST be provided.
1. This endpoint MUST be protected by some kind of authorisation mechanism.
2. It is only necessary to open this endpoint to the Operational Team; the Operational Team
will inform the site administrators in advance from what IPs the accounting metrics will
be collected.

Site admission procedure
The following steps need to be undertaken to join the Science Mesh:
1. A representative of the applicant Site signs the Science Mesh Policy Declaration and
presents it to the Operational Team together with the necessary contact information.
2. The applicant Site MUST make sure that it conforms with the requirements in section
“Requirements for Sites joining the Science Mesh”.
3. The Operational Team verifies that the applicant conforms with the requirements in section
“Requirements for Sites joining the Science Mesh”. If the applicant does not conform with
the requirements, the Operational Team MUST describe reasons and SHOULD give a
recommendation how to remedy.
4. The Operational Team informs the Science Mesh Steering Group about a new Site.
45. The Operational Team performs registration of the applicant Site to the Science Mesh. This
includes registration in the Central Database and making sure that accounting metrics are
collected and the Site monitoring tests are running.
-->

<!--

For the CS3 workshop, the governance boards and the OT will not be in place.
Therefore let us just focus on the technical part and leave the paperwork for
later on. We want sites to join the Science Mesh and not be deterred bij a mountain of bureaucracy.

-->

<!--
Here is a brief overview of the steps necessary to join the Science Mesh project:

1. First you need to setup:
    - the [Inter Operability Platform]({{< ref "docs/Technical-documentation/IOP" >}}) (IOP)
    - the [health monitoring]({{< ref "docs/Technical-documentation/monitoring/Health-Monitoring" >}})
    - the [accounting metrics]({{< ref "docs/Technical-documentation/monitoring/Accounting-Metrics" >}}) collection    

   for your site. You may find information on how to setup these components by following the links above.

1. Get into contact with a Science Mesh representative by using this [form]({{< ref "docs/How to join ScienceMesh/OnlineForm" >}})
1. After that, a Science Mesh representative will get back to you, detailing the next steps to get your site up and running.
1. Your site is then added to our central database, effectively integrating it into the Science Mesh.
    - This includes appearing on all Science Mesh dashboards and being actively monitored for proper health.
1. In order to maintain your site's information in the central database, you will need to create an administrative account for our central database and request proper accesss rights.
    - More information will be provided by a Science Mesh representative after your site has joined the Science Mesh.
-->

<!--
1. Read the technical and legal documentation which can be found here (FIXME).
1. Get into contact with the Science Mesh administration by using this online form (FIXME).
1. After reviewing your request, an administrator will get back to you, detailing the next steps; these include:
    - Getting remaining details about your site, especially technical ones like your IOP address for health monitoring
    - Performing initial compatibility and quality tests
    - FIXME...
1. Once all prerequisites have been met, you need to agree to and sign our OLAs/SLAs (FIXME).
1. Your site is added to our central database, effectively integrating it into the Science Mesh.
    - This includes appearing on all Science Mesh dashboards and being actively monitored for proper health.
1. In order to maintain your site's information, you will need to create an administrative account for our central database and request proper accesss rights.
    - More information will be provided by an administrator after your site has joined the Science Mesh.

-->

<!--

This stuff should go to FIXME1 I think.

### Checklists (FIXME)
Below you'll find some quick checklists to help you get your site ready for joining the Science Mesh.

#### General requirements (FIXME)
- Have this...
- And that...
- Legal stuff...
- FIXME...

#### Basic technical requirements
- Supported EFSS systems: _ownCloud 10/OCIS_, _Nextcloud_ (Version?), _Seafile_ (Version?)
- IOP (Reva) installed, configured and running next to your EFSS system
- EFSS and IOP must be accessible from the outside (see here (FIXME))
- FIXME...

#### Before joining the Science Mesh
- Read this (FIXME) introductory document that details the technical requirements to join the Science Mesh
- Install the IOP (Reva) as explained here (FIXME)
- Configure the IOP and connect it to your EFSS as explained here (FIXME)
- Run some self-tests as explained here (FIXME)
- FIXME...
-->
