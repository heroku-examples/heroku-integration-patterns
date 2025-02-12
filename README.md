# Heroku Integration and Eventing Samples (Pilot)

> [!IMPORTANT]
> For use with the Heroku Integration and Heroku Eventing pilots only. For more information check out this [video and video description](https://www.youtube.com/watch?v=T5kOGNuTCLE) and this [video](https://www.youtube.com/watch?v=Pvg1m295WA8) for information more on how to signup to these pilots.

This collection of sample applications demonstrates various integration patterns between Heroku and Salesforce that take advantage of our Heorku Integration and Heroku Eventing features.  They cover key use cases such as accessing Salesforce APIs for data exchange and automation (including efficient bulk data handling), extending Salesforce functionality by enabling Apex, Flow, and Agentforce to interact with Heroku apps, and scaling batch jobs by delegating compute-intensive tasks to Heroku Workers.  Furthermore, the samples illustrate how to leverage eventing for automation and communication, including triggering jobs and notifying users via custom notifications, showcasing the integration with low-code tools like Salesforce Flow.

> [!NOTE]
> Please follow this repository for updates as we continue to expand the samples and languages they are availble in.

| Sample | What it covers? |
| ------ | --------------- |
| [Salesforce API Access - Java](https://github.com/heroku-examples/heroku-integration-pattern-api-access-java) | This sample application showcases how to extend a Heroku web application by integrating it with Salesforce APIs, enabling seamless data exchange and automation across multiple connected Salesforce orgs. It also includes a demonstration of the Salesforce Bulk API, which is optimized for handling large data volumes efficiently. |
| [Extending Apex, Flow and Agentforce - Java](https://github.com/heroku-examples/heroku-integration-pattern-org-action-java) | This sample demonstrates importing a Heroku application into an org to enable Apex, Flow, and Agentforce to call out to Heroku. For Apex, both synchronous and asynchronous invocation are demonstrated, along with securely elevating Salesforce permissions for processing that requires additional object or field access. |
| [Scaling Batch Jobs with Heroku - Java](https://github.com/heroku-examples/heroku-integration-pattern-org-job-java) | This sample seamlessly delegates the processing of large amounts of data with significant compute requirements to Heroku Worker processes. It also demonstrates the use of the Unit of Work aspect of the SDK (JavaScript only for the pilot) for easier utilization of the Salesforce Composite APIs. |
| [Using Eventing to drive Automation and Communication - Java](https://github.com/heroku-examples/heroku-integration-pattern-eventing-java) | This sample extends the batch job sample by adding the ability to use eventing to start the work and notify users once it completes using Custom Notifications. These notifications are sent to the user's desktop or mobile device running Salesforce Mobile. Flow is used in this sample to demonstrate how processing can be handed off to low-code tools such as Flow. |
