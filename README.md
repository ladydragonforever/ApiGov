# ApiGov
API data governance tool that captures client API calls, visualize and monitor data flows.

Refer to our [Architecture doc](./doc/architecture.md) for more details.

# Why is this tool useful?
There are various use cases that we think this tool will be useful:
1. GDPR/CCPA requirements: the tool demonstrates what types of data being shared, any sensitive data, audit trails on the changes, dashboard on which partners are called the most and when they are used.
2. Vendor risk: Initial data sharing with vendors are validated thru vendor contract, but any changes afterwards are difficult to capture. The tool sent alerts on any data changes or abnormal data sharing.
3. Client API data monitoring: Good data governance of client APIs can help to get matrices on data collected and data used to make the data usage and protection more efficient. 
4. Advanced client APIs monitoring: the tool can detect client API outages and monitor to avoid bad user experience.

# Why do we create this tool?
In the past couple of years, we saw increasing usage of 3rd party APIs. Also, more and more data are shared via APIs.

In my previous job doing cyber security risk consulting, I saw companies lacking visibility around data shared via APIs. With GDPR and CCPA, it is becoming mandate for companies to have data governance around their APIs.    

My co-founder has extensive experience is DevOps and software development. He wanted to have a tool for client API monitoring, beyond exgress logging. He was constantly fighting with client API outages and could not optimize the API usage based on needs.

We are both excited to build a tool that can log API calls, visualize API data flows, send alerts for outages and suspicious data flows.

It's a new breed of DevSecOps tool that we are creating for the new data economy, where data privacy and security should be designed in the infrastructure.

