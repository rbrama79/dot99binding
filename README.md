IEEE P1451.99 bindings (demo)
===============================

This repository will hold information about the IECON2023 demonstration of IEEE P1451.99 bindings.

SPARQL Endpoint
-----------------

SPARQL is a standardized query language (find references below) that can be used to:

1. Query semantical information
2. Transform semantical information
3. Perform federated queries

For the demo, the following live resources are available:

* [SPARQL Endpoint](https://lab.tagroot.io/sparql), with associated [web form](https://lab.tagroot.io/Sparql.md). 
* Use this endpoint to execute SPARQL queries.
* [Request login credentials to access SPARQL Endpoint](https://lab.tagroot.io/Feedback.md). Provide your full name, e-mail and purpose, to receive access to SPARQL endpoint above.

Graph Store (Graph Database)
--------------------------------

W3C has [standardized a protocol](https://www.w3.org/TR/sparql12-graph-store-protocol/) for 
creating, updating, retrieving and getting semantic graphs in *graph stores*. These graphs
can later be processed using SPARQL, and other semantic web-related technologies.

For the demo, the following live resources are available:

* [Graph Store](https://lab.tagroot.io/rdf-graph-store) with associated [web form](https://lab.tagroot.io/GraphStore.md). 
Use this endpoint to create (`PUT`), update (`POST`), retrieve (`GET`) or delete (`DELETE`) graphs, as described in the W3C
standard [SPARQL 1.2 Graph Store Protocol](https://www.w3.org/TR/sparql12-graph-store-protocol/).
* [Request login credentials to access Graph Store](https://lab.tagroot.io/Feedback.md). 
Provide your full name, e-mail and purpose, to receive access to the Graph Store above.

Example Files
---------------

Repository contains the following examples files:

* UBI V1
	* [Semantic sensor data in RDF/XML format](UBI/V1/ReadTEDSExample.rdf)
	* [Semantic sensor data in graph form](UBI/V1/ReadTEDSExample.png)
	* [Comments on semantic sensor data](UBI/V1/CommentsOnRDF.md)
	* [Semantic sensor data in JSON-LD format](UBI/V1/ReadTEDSExample.jsonld)
* UBI V2
	* [ReadMetaTEDSv2ieee1415.rdf](UBI/V2/ReadMetaTEDSv2ieee1415.rdf)
	* [ReadMetaTEDSv2xs.rdf](UBI/V2/ReadMetaTEDSv2xs.rdf)
	* [ReadMetaTESDxs.svg](UBI/V2/ReadMetaTESDxs.svg)
	* [SelectTemperatureSPARQL.rq](UBI/V2/SelectTemperatureSPARQL.rq)
	* [TemperatureExample.jsonld](UBI/V2/TemperatureExample.jsonld)
	* [TemperatureExample.rdf](UBI/V2/TemperatureExample.rdf)
	* [exampleData.svg](UBI/V2/exampleData.svg)
	* [ReadMetaTEDSieee1451.svg](UBI/V2/ReadMetaTEDSieee1451.svg)
* [Last IECON 2022 1451.99.0 Demo Material](dot99_0/README.md)

Example Devices
------------------

Following resources list devices used in the demo.

* Simulated Modbus devices
	* [Modbus Device List](ModbusDevices.md)
	* [Simulating Modbus devices using ComSim](https://lab.tagroot.io/Community/Post/Simulating_Modbus_devices_using_ComSim)
	* [Modbus simulation output/expected behaviour](https://lab.tagroot.io/Reports/ModBusDeviceControl.md)

References
-------------

* [Current IEEE P1451.99 Proposal](https://gitlab.com/IEEE-SA/XMPPI/IoT)
* [W3C Semantic Web specifications](https://www.w3.org/TR/?tag=data)
* [W3C specification for the TURTLE format for semantic information](https://www.w3.org/TeamSubmission/turtle/#sec-collections)
* [W3C specification for SPARQL 1.2 query language](https://www.w3.org/TR/2023/WD-sparql12-query-20230516/)
* [W3C specification for SPARQL 1.2 protocol](https://www.w3.org/TR/sparql12-protocol/)
* [W3C specification for Graph Store protocol](https://www.w3.org/TR/sparql12-graph-store-protocol/)
* [IEEE P1451.99 Implementation reference broker](https://cybercity.online/)
* [Lab server for demo](https://lab.tagroot.io/)
* [Server documentation](https://lab.tagroot.io/Documentation/Index.md)
* [IoT Gateway repository, with Simplie IoT Client for test](https://github.com/PeterWaher/IoTGateway)
* [TAG Digital ID App, for Android, for test](https://play.google.com/store/apps/details?id=com.tag.IdApp)
* [TAG Digital ID App, for iOS, for test](https://apps.apple.com/tr/app/trust-anchor-id/id1580610247)