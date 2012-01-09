openengsb-domain-issue-2.0.0 2012-01-09
---------------------------------------------------------------------

This release upgrades the domain to a) work with the OpenEngSB 2.4.0 and b) incorporated the
latest features of the new version (EDB integration, WSDLs for easy bridge integration, dedicated documentation).

** Bug
    * [OPENENGSB-2330] - adapt issue domain to current openengsb-framework
    * [OPENENGSB-2582] - Domains and Connectors need to include our snapshot repo to work with deployed snapshots correctly

** Improvement
    * [OPENENGSB-1836] - Enhance issue domain with EDB CUD Events
    * [OPENENGSB-2586] - Include issuetracker, buildserver and inceptionYear from root
    * [OPENENGSB-2598] - Make package structure flat to make wsdl-generation possible

** New Feature
    * [OPENENGSB-2513] - move documentation to domain
    * [OPENENGSB-2575] - Include wsdl definition from 2.4.0 parent

** Task
    * [OPENENGSB-2566] - upgrade openengsb-domain-parent to 2.3.0 in all domains
    * [OPENENGSB-2596] - Adapt domain.name in domains to be e.g. AppointmentDomain instead of Appointment alone
    * [OPENENGSB-2625] - Release domain-issue-2.0.0


openengsb-domain-issue-1.2.2 2011-05-23
---------------------------------------------------------------------

Second support release of the Issue Domain upgrading to the latest OpenEngSB Framework.

** Library Upgrade
    * [OPENENGSB-1609] - Upgrade openengsb-framework to 1.3.0.M2

** Task
    * [OPENENGSB-1574] - Release openengsb-domain-issue-1.2.2


openengsb-domain-issue-1.2.1 2011-05-16
---------------------------------------------------------------------

Corrected minor error in interface definitions and added bundle-info

** Bug
    * [OPENENGSB-1468] - issuedomain should not use arraylist as returntype
    * [OPENENGSB-1573] - bundle.info uses wrong resource-filtering

** Library Upgrade
    * [OPENENGSB-1508] - Push connectors and domains to latest openengsb-framework-1.3.0.M1

** New Feature
    * [OPENENGSB-948] - Add OSGI-INF/bundle.info as used in Karaf to the openengsb bundles

** Task
    * [OPENENGSB-1430] - Release openengsb-domain-issue-1.2.1


openengsb-domain-issue-1.2.0 2011-04-27
---------------------------------------------------------------------

Initial release of the OpenEngSB Issue Domain as standalone package

** Bug
    * [OPENENGSB-1395] - mvn scm tags point to openengsb instead of domain

** Improvement
    * [OPENENGSB-1268] - Add components to domain-issue

** Library Upgrade
    * [OPENENGSB-1394] - Upgrade to openengsb-1.2.0.RC1

** Task
    * [OPENENGSB-1322] - adapt domains to new service-manager-api
    * [OPENENGSB-1369] - Release openengsb-domain-issue-1.2.0
    * [OPENENGSB-1396] - Add infrastructure for notice file generation
    * [OPENENGSB-1397] - Add ASF2 license file

