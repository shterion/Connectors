<p align="center">
  <img src="https://github.com/openintegrationhub/Connectors/blob/master/Assets/medium-oih-einzeilig-zentriert.jpg" alt="Sublime's custom image" width="400"/>


The revolution in data synchronization — the Open Integration Hub enables simple data synchronization between any software applications and thus accelerates digitalisation

Visit the official [Open Integration Hub homepage](https://www.openintegrationhub.de/)

# Connector

## Table of Content

<!-- TOC depthFrom:2 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

- [Table of Content](#table-of-content)
- [Introduction](#introduction)
	- [Adapter](#adapter)
	- [Transformer](#transformer)
- [Contribution](#contribution)
	- [Contribution Guidelines](#contribution-guidelines)
	- [Code of Conduct](#code-of-conduct)
- [Contact](#contact)
- [Content](#content)
	- [Folders](#folders)
	- [Documents](#documents)
- [Workgroup](#workgroup)
	- [Information](#information)
	- [Member](#member)
- [Wording](#wording)

<!-- /TOC -->


## Introduction

The Open Integration Hub enables data synchronization across a variety of applications. To create a connection and enable interaction a link is needed between the software application and the Open Integration Hub - namely an Open Integration Hub connector.
A connector connects a software solution to the Open Integration Hub. It consists of two distinct parts, namely adapter and transformer.  It contains different functionalities e.g. to fetch and transform data. These functionalities are further explained in the sections [adapter](#adapter) and [transformer](#transformer). In order to achieve our goal to establish a successful open source community we need to steadily increase the number of connectors. So join us and help us grow as an open source community!


The following illustration provides a holistic overview of a connector:
![Connector](Assets/ConnectorsV2.svg)

### Adapter

An adapter is a module for the syntactic connection of an external application and its data to the Open Integration Hub. This includes protocol translation, data format transformation, etc.
Furthermore it provides functionalities to perform e.g. CRUD operations within the source system.
<p/>
For further information please read through the information within the [adapter folder](/Adapters).


### Transformer

A transformer is responsible to semantically transform an incoming JSON object into another JSON object. Thus the mapping between two data models is done within the transformer.

For further information please read through the information within the [transformer folder](/Transformer).


## Contribution
### Contribution Guidelines
Before you contribute please read our [contribution guidelines](CONTRIBUTING.md).

### Code of Conduct

To see how members of the community are expected to behave, please read the [code of conduct](CODE_OF_CONDUCT.md). We apply the code of conduct defined by the Contributor Covenant, which is used across many open source projects, such as [NodeJS](https://github.com/nodejs/node), [Atom](https://github.com/atom/atom) and [Kubernetes](https://github.com/kubernetes/kubernetes).

## Contact
When looking for further information or support, please contact: philipp.hoegner@cloudecosystem.org.

## Content
### Folders

- [Adapters](Adapters): Describes the adapters, their goals, standardized behavior and checklists for building an adapter
- [ApplicationDocuments](ApplicationDocuments): Contains all application documents needed to apply for the funding of the creation of a connector
- [Protocols](Protocols): Collection of all taken protocols by the workgroup
- [Transformer](Transformer): Includes the transformer concept, a basic introduction into the JSONata transformation language,  transformer evolution and suggestions for possible implementations

### Documents
- [CONTRIBUTING](CONTRIBUTING.md): Contains the contribution guideline for the Open Integration Hub project
- [CODE_OF_CONDUCT](CODE_OF_CONDUCT.md): Contains an explanation of the expected behavior of the community members, following  the code of conduct defined by the Contributor Covenant

## Workgroup
### Information
- Each workgroup has atleast one status call every two weeks
- Every committer must attend the status call
- The governance model defines the workgroup members' roles into managers, committers or contributors

### Member
#### Connectors
|Member Name |GitHub Alias|Company| Role |
| --- | --- | --- | --- |
| Philipp Hoegner|[philecs](https://github.com/philecs)|[Cloud Ecosystem](http://www.cloudecosystem.org/)| **Manager**  |
| Robin Brinkmann |[RobinBrinkmann](https://github.com/RobinBrinkmann)|[Cloud Ecosystem](http://www.cloudecosystem.org/) | Committer   |
| Jacob Horbulyk |[jhorbulyk](https://github.com/jhorbulyk)|[Elastic.io](https://www.elastic.io/)| Committer   |
| Renat Zubairov|[zubairov](https://github.com/zubairov)|[Elastic.io](https://www.elastic.io/)| Contributor   |
| Dennis Steiniger|[dennisCES](https://github.com/dennisCES)|[Cloud Ecosystem](http://www.cloudecosystem.org/)| Contributor   |

## Wording
Within the project different terms and abbreviations are frequently used. All terms and abbrevations are explained within the [glossary](https://github.com/openintegrationhub/Connectors/wiki/Glossary) and our [list of abbrevations](https://github.com/openintegrationhub/Connectors/wiki/Abbreviations).
