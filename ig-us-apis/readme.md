# IG US APIs

# Table of Contents
- [Rules of Engagement](#rules-of-engagement)
- [FIX Based APIs](#fix-based-apis)
- [WebSocket API](#websocket-api)
- [FIX API](#fix-api)

## Rules of Engagement 
You will find the [ig-orchestrations](https://github.com/IG-Group/ig-orchestrations) project in Github. 

The project contains and/or generates API Documents, as well as JSON Schema, Java bindings and TypeScript interfaces. 

You don’t need to build this project as the artifacts are published to “oss.sonatype.org” and can be downloaded from there.
You’ll want to download the roe.zip for either the WebSocket or FIX API. You can follow the following links to the download location.

| **API**   | **Artifact** |
|-----------|--------------------------|
| WebSocket | [![Sonatype Nexus (Releases)](https://img.shields.io/nexus/r/com.ig.orchestrations.us.rfed/document-websocket?label=WebSocket&server=https%3A%2F%2Foss.sonatype.org%2F)](https://oss.sonatype.org/#nexus-search;gav~com.ig.orchestrations.us.rfed~document-websocket~~~) | 
| FIX5.0SP2	    | [![Sonatype Nexus (Releases)](https://img.shields.io/nexus/r/com.ig.orchestrations.us.rfed/document-fixt?label=FIXT&server=https%3A%2F%2Foss.sonatype.org%2F)](https://oss.sonatype.org/#nexus-search;gav~com.ig.orchestrations.us.rfed~document-fixt~~~)   |

### How to use the "Rules of Engagement" documents.

The conventional FIX API is documented with Markdown and HTML. These can both be found in the deployed artifact referenced above. The Markdown can be viewed without downloading the artifact.

 * [Markdown](https://github.com/IG-Group/ig-orchestrations/tree/master/ig-us-rfed/document/document-fixt/markdown) for the FIX50SP2 over FIXT1.1 API

* [Markdown](https://github.com/IG-Group/ig-orchestrations/tree/master/ig-us-rfed/document/document-websocket/markdown) for the eWebSocket API

## FIX Based APIs

The APIs are built on FIXT1.1 or FIX/P and defined using FIX Orchestra. The latter is a new FIX Trading Community initiative that is in active development.
Please see: 
-	[Fix Trading Community](https://www.fixtrading.org/)
-	[Fix Orchestra](https://www.fixtrading.org/standards/fix-orchestra/)
-	[Fix Protocol Standards](https://www.fixtrading.org/standards/)

## WebSocket API

## WebSocket Client Examples
You can also find simple WebSocket Client Examples here:
- [Node Example](https://github.com/IG-Group/fix-ws-client-example)
- [Python Pre-Trade Example](https://github.com/IG-Group/ig-us-websocket-client-python-example) 
- [Python Trade Example](https://github.com/IG-Group/ig-us-websocket-trade-python-example)
- [Java Example](https://github.com/IG-Group/ig-us-websocket-java-examples)

N.B. Logging onto the WebSocket API using username and password results in a “logout” messages being sent to web platform (as it does when you try to log on to the web platform multiple times). For testing you can log onto the API first. Logging onto web platform does not log out the API.

These are the Demo connection details.  Please refer to the examples.

| **API**   | **Host**                 | **Port** | **Path**  |
|-----------|--------------------------|----------|-----------|
| Pre Trade | demo-iguspretrade.ig.com | 443	    | /pretrade |
| Trade	    | demo-igustrade.ig.com	   | 443	    | /trade    |	 	 

## FIX API
### FIX API Client Example
- [Java](https://github.com/IG-Group/ig-us-websocket-java-examples)

We have updated a fork of the open source QuickFix/J project to support our API including a customised QuickFIX/J dictionary. This is our QuickFixJ github forked repository: [qfj-ig-us](https://github.com/IG-Group/qfj-ig-us)

We have made artifacts publicly available in Sonatype at the following location:

[![Sonatype Nexus (Releases)](https://img.shields.io/nexus/r/com.ig.us.otc/quickfixj-all?label=QuickFixJ&server=https%3A%2F%2Foss.sonatype.org%2F)](https://oss.sonatype.org/#nexus-search;gav~com.ig.us.otc~~~)


### Contact
In order to use the FIX API, please contact Trading Services with the details below.

| **Department**    | **Contact Email**    |
|-------------------|----------------------|
| Trading Services  | helpdesk.us@ig.com   |
