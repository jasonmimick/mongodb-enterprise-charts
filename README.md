A curated set of Enterprise MongoDB Kubernetes
Helm charts.

Included Charts
---

`mongodb-enterprise-standalone`	
*A functional standalone MongoDB cluster running in a single namespace*

_coming_
`mongodb-enterprise-cluster`	
*A functional single-node MongoDB sharded cluster running in a StatefulSet*


Architecture

Single Namespace
 Operator
 ConfigMap
	- CloudMgr
  - OpsMgr
 Secret
 DB Deployment

Values:
cloud manager programatic apikey pair

