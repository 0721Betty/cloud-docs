# Get Started with EMQ X Cloud

Welcome to EMQ X Cloud! EMQ X Cloud is the first fully hosted MQTT 5.0 public cloud service in the world. With the support of EMQ X Cloud,
you can create an EMQ X cluster on the cloud and use all the features of EMQ X Enterprise Edition. This allows you to spend more time on business
connections and less time for EMQ X operation, maintenance, and management. This tutorial will guide you through the process of creating and connecting
to EMQ X Cloud deployment. Before starting, let's review some core concepts and phrases:

* Deployment: EMQ X Enterprise cluster hosted on EMQ X Cloud
* Basic Plan: Single node version of EMQ X Enterprise
* Professional Plan: An EMQ X Enterprise Edition cluster with separate networks, instances, and load balancing
  
  <div style="position: relative; padding: 30% 45%;">
  <iframe style="position: absolute; width: 100%; height: 100%; left: 0; top: 0;" src="https://www.youtube.com/embed/nOmIomoFn28" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
  </div>

You can follow these steps shown below to quickly complete the EMQ X Cloud QuickStart.

1. [Login/Register](./create_account.md) EMQ X Cloud account

> EMQ X Cloud offers one 30-day free trial of basic plan, and a 14-day free trial of the professional plan for each user (Professional plan free trial is available after you bind the credit card).
    ![add_users](./_assets/log_in.png)


2. Visit EMQ X Cloud [console](https://cloud-intl.emqx.com/console/) and create a free trial deployment
   
   ![console](./_assets/free_trial.png)


3. Visit Authentication & ACL page to add authentication information

   ![authentication](./_assets/auth.png)


4. Click the menu on the left to get the deployment connection information and ports

   ![authentication](./_assets/detail.png)
    

5. Use the MQTT client or SDK that you are familiar with to [connect to the deployment](../connect_to_deployments/introduction.md) 
   ![authentication](./_assets/mqttx_connect.png)
   
