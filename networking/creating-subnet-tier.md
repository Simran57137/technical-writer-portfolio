# Creating Subnet Tier

In Nimbus Cloud Platform, a subnet is a logical subdivision of a VPC that provides a dedicated IP address range for deploying cloud resources.&#x20;

A tier defines the network role assigned to a subnet based on its connectivity and security requirements. Nimbus Cloud Platform supports different tiers to help you organize workloads and control network traffic. For example, a Public Tier can be used for resources that require Internet connectivity, while a Private Tier can be used for internal workloads that should not be directly accessible from the Internet.

{% hint style="info" icon="note" %}
Create the required subnet tiers before deploying resources that depend on them.
{% endhint %}

To create a subnet tier, follow these steps:

1. Navigate to **Networks > Virtual Private Networks**.&#x20;
2. Click the **VPN Name**.
3. Navigate to the **Subnet Tier** tab.
4. Click the **Add Tier** button.
5. Enter the following details:

* **Tier Name**
* **Protocol**
* **Port ranges**

6. Click the **Create** button.
