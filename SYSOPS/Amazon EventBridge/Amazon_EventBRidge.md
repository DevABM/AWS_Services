# Amazon EventBridge

### What?
- Amazon EventBridge is a serverless event bus service to connect your applications with data from a variety of sources.
- EventBridge expands on the capabilities of CloudWatch Events, adding for processing events from SAAS partner applications and making it easier for you to process events from your own applications.

### Why?
- EventBridge enables you to build event-driven architectures that are loosely coupled and distributed.
- EventBridge ingests data from supported SAAS applications without writing custom integration code and reduce operational overhead as there are no servers to provision, patch, and manage and no software to install.

### When?
- You want to extend the functionality of your applications by easily connecting them to other SaaS applications.
- you want to monitor and audit your AWS environments and respond to operational changes in your applications in real-time to prevent infrastructure vulnerabilities.

### Where?
- Amazon EventBidge is a regional service.
- It also supprts Global endpoints to fail over event ingestion automatically to a secondary Region during service disruptions.

### Who?
- Amazon EventBridge is a fully managed service.
- Your account has a default event bus which receives events from AWS services. You can create custom event buses to send or recive events from a different account or Region.

### How?
- EventBridge receives an event( an indicator of a change in environment) and applies a rule to route the event to a target. Rules match events to targets based on the event pattern, or ona schedule.
- All events that come to EventBridge are associated with an event bus and rules are tied to a single event bus.

### How much?
- Charge are calculated for per million events published, which includes custom events, third-party events, and events to another bus.
- Customers may incur additional data transfer charges between regions for cross-Region invocations.
- There is no additional charge for global endpoints.

### Link to Service FAQs:
[FAQ](https://aws.amazon.com/eventbridge/faqs/)

