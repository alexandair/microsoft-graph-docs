---
description: "Automatically generated file. DO NOT MODIFY"
---

```java

IGraphServiceClient graphClient = GraphServiceClient.builder().authenticationProvider( authProvider ).buildClient();

IGroupLifecyclePolicyCollectionPage groupLifecyclePolicies = graphClient.groups("{id}").groupLifecyclePolicies()
	.buildRequest()
	.get();

```