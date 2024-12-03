# Building the future of cloud operations

"the totality is not, as it were, a mere heap, but the whole is something besides the parts.." - Aristotle

Connecting the dots (bots) 
@Ops-IT-Tron - Formation of multiple cloud ops bots

## Transform how you govern
### Challenges 
- Consistent Visibility
- Continuous Identification of coverage gaps
- Prescriptive controls and tools to remediate

- Unknown unknowns - have no idea it exists but it's there costing us (zombie resources). I can not put any engineering behind these to fix issues they are having. With 
- Known Unknowns - We know the resources is there, but don't know why it's failing

### New Features
AWS Systems Manager will be a new unified experience to simplify node management And is useable across the AWS accounts/regions, and manage on-prem and multi-cloud nodes. This also will have integrations with Amazon Q
Declarative Policies - Give you the ability to prevent non-compliance actions. Stays in place even when new API are introduced 
Resource Control Policies - Allows you to control the maximum allowable permissions for any resource (like buckets or keys). Integrates with AWS Organizations.

### Capital One Case Study
Using Config and CloudTrail in combination to put engineering behind the various resources across the organization, Capital One was able to reduce their customer issues by 75%. They were able to detect the dependencies between their resources and be able to put together automation to ensure proper remediation.


## Transform how you observe
You can't manage what you can't see. 

### New Features
Cloudwatch telemetry - Connected Telemetry and Faster troubleshooting with the Explore Relations in CLoudwatch once you've set up metrics. It can create a connection between the application level metrics and the infrastructure metrics. Application signals, Service Map, Services, etc will show visually the 

Fault Injection Service - is a service for doing experiments on your application recovery response

Network flows can now be cloudwatch! Monitors TCP traffic between AWS resources and sends health events to AWS Support dashboards.

Cloudwatch Data base INsights Curated observability experience for Aurora Posgres and MySQL.

Enhanced observability for ECS is now available along with EKS. No agent! Fully managed out of the box



## Transform how you analyze

### Challenges
- Difficult to PInpoint root cause
- Hard to connect to business outcomes
- Analyzing performance issues i tedious
- Having to build context distracts from the important work



### New Features
Transaction Search - Allows you to look at spans that keep track of all interactions across the platform.
- Tasia's Question: Does this ingest instrumentation from other platforms by chance? Can we use this in combination to Dynatrace
OpenSearch querying is now in Cloudwatch logs!! We don't have to export the data or ingest it into Opensearch.
Cloudwatch allows for indexing t
- Can still use Logs insights Query Language to query for things.
- 


## Reference section
https://aws.amazon.com/blogs/mt/top-announcements-for-aws-cloud-operations-at-reinvent-2024/
