---
layout: post
title:  "How Much Does It Cost to Run Odoo ERP with 40 Employees?"
categories: saas
---
Odoo, a popular open-source ERP system, effectively manages various business processes like CRM, accounting, inventory, and operations, known for its flexibility, scalability, and affordability. Potential users often inquire about the cost of running the software, which varies based on the number of users, hosting options, and required customizations. We will discover the expenses associated with operating Odoo for 40 users, comparing the costs of Odoo Standard Plan vs a self-hosted alternative using Amazon AWS.
<!--more-->

![Photo taken of an Odoo’s billboard in Nashville by a LinkedIn user.](https://h7g4rb6t8u7i.blob.core.windows.net/blog/yc5gjpu8wwnh.png)

To perform this comparison accurately, we need to determine the minimum hardware requirements necessary to deploy our platform on Amazon AWS and support 40 users effectively. Odoo does not provide specific minimum hardware requirements, likely due to the complexity and variability involved in such calculations. However, some experienced members of the Odoo community have shared insights from their own deployments. Based on their experiences, they have successfully managed a similar workload using an instance with 4 vCPUs, 16 GB of RAM, and 1 TB of SSD storage. Using the Amazon AWS Price Calculator and the previous mentioned specifications, we can obtain the following estimate:

![Amazon AWS Estimate Details](https://h7g4rb6t8u7i.blob.core.windows.net/blog/6798995g56zg.png)

AWS Pricing Calculator provides only an estimate of your AWS fees and doesn't include any taxes that might apply. We also must remember that actual fees depend on a variety of factors, including actual usage.

## Cost Comparison
For this comparison, we will use Odoo regular pricing as of June 2024, which is $11.20 USD per user per month.

![Cost Comparison Chart](https://h7g4rb6t8u7i.blob.core.windows.net/blog/btj8iqg896w5.png)

The self-hosted alternative would save us almost 68% compared to the Standard Plan. However, these savings of $3,654.48 USD come with a caveat. We would be missing out on customer support and many apps that are not included in the self-hosted edition. Additionally, if we have more users in the near future, our costs will increase, whereas on the managed plan, they will remain the same and Odoo will handle all the scaling requirements for our operations.

## Conclusion
In summary, Odoo's competitive pricing has contributed significantly to its rapid growth in the market. For comparison, as of June 2024, Zoho One costs $3,600 USD monthly for 40 users, with flexible user pricing at $90 USD per user per month.

Choosing between Odoo's Standard Plan and a self-hosted setup on Amazon AWS involves balancing cost savings against potential limitations. Opting for self-hosting can save nearly 68%, but it requires giving up customer support and access to many apps, with possible higher costs as user numbers grow. In contrast, Odoo's Standard Plan offers predictable costs and comprehensive support, ensuring stability and scalability managed by Odoo themselves. The best choice depends on considering budget, support needs, future growth plans, and crucially, technical expertise required to set up and maintain your own infrastructure and security.

## Sources
<div class="sources" markdown="1">
Van, Y. (2023). Hardware Requirements for Odoo?. Odoo Forum.]Retrieved from https://www.odoo.com/forum/help-1/hardware-requirements-for-odoo-216576

Odoo. (2024). Pricing Plans. Retrieved from https://www.odoo.com/pricing-plan

Odoo. (2024). Compare Editions. Retrieved from https://www.odoo.com/page/editions

Zoho. (2024). Zoho One Pricing.Retrieved from https://www.zoho.com/one/pricing

Vaishnani, B. (2022). Odoo billboard in Nashville. LinkedIn. Retrieved from https://www.linkedin.com/posts/bhoomi-vaishnani-16125458_odooerp-odoo-odoodevelopment-activity-6932092240001441792-eYl-

</div>