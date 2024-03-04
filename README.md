[![hubia-consulting-firm-isaac-arnault-watsonx-data-tutorial.png](https://i.postimg.cc/DZdHVDSf/hubia-consulting-firm-isaac-arnault-watsonx-data-tutorial.png)](https://postimg.cc/hzvpT28N)

# Presentation
[![Project Status: Active – The project has reached a stable, usable state and is being actively developed.](https://www.repostatus.org/badges/latest/active.svg)](https://www.repostatus.org/#active)

This is a set of 3 gists intended to present `IBM watsonx` platform.<br>
If you are a `HUBIA` client or a prospective customer you may wonder what is `watsonx` about and how it can be used to solve your business use cases or data & AI challenges.<br>

IBM **watsonx** platform presentation will be made in 3 parts:<br><br>
**Part 1 - Introducing IBM watsonx data<br>
Part 2 - Introducing IBM watsonx ai<br>
Part 3 - Introducing IBM watsonx governance**

<hr>

The testing and GitHub documentation were technically performed by Isaac Arnault, EMEA Managing Director for Data, AI and Analytics at HUBIA (Consulting IT firm for Data, AI, BI and Analytics) in France. This gist is mainly dedicated to HUBIA's Clients' teams and its prospective customers. Follow Isaac Arnault on GitHub: https://isaacarnault.github.io/.

<hr>

Without any further due let's get started. 

[![isaac-arnault-watsonx.png](https://i.postimg.cc/Kzq7grVr/isaac-arnault-watsonx.png)](https://postimg.cc/wyNRCJ97)

## Part 1 - Introducing IBM watsonx data<br>
`Testing and Documentation: 48 hrs`

These are `watsonx` 3 core tools:<br>
`watsonx data`<br>
`Watsonx governance`(New tool released on February 2024)<br>
`watsonx ai<br>

1. go to https://cloud.ibm.com/watsonx/overview.
2. Go to https://cloud.ibm.com and log into your account or register for a new `IBM` user account.<br>

<details>
<summary>🐝 See console</summary>
<p>
  
[![isaac arnault watsonx 0](https://i.postimg.cc/k4CxkxgQ/isaac-arnault-watsonx-0.png)](https://postimg.cc/7CBGzJ7h)

</p>
</details>

3. Click on **watsonx.data** Get Started
4. Once you land on WatsonX data console, leave `IBM Cloud` as default Cloud platform.<br>
! At this point, please notice that **watsonx data** can be deployed on `IBM Cloud` or `AWS Cloud`.
5. Leave IBM Cloud as default platform and if you are in Europe, choose `Frankfurt` or `London` as location.
6. Apply **WATSONXDATA** in the Code section to start with **$1,500** worth of free credits.

 [![isaac arnault watsonx 3](https://i.postimg.cc/V6TbznYZ/isaac-arnault-watsonx-3.png)](https://postimg.cc/hzLGrJQV)

<hr>

**Important<br>
It is possible that you get an error message asking you to upgrade your account before applying a discount code, therefore open a new IBM Console window at https://cloud.ibm.com/account/, go to Account > Account upgrade (bottom of the page)**.
  
[![isaac arnault watsonx 5](https://i.postimg.cc/hGts2kpL/isaac-arnault-watson-x-5.png)](https://postimg.cc/5XD80Rcy)

**Add credit card** info. Passing your credit card info will help you **Upgrade your account** and therefore you will be elligible for a free tier access among which **watsonx data**.<br>

Once your credit card info are passed and you have upgraded your account, go back to the previous tab with the **watsonx data** console.<br>

Now it works! You are now ready to use the $1500 promo code for **watsonx data**.<br><br>

<details>
<summary>🐝 See console</summary>
<p>
  
[![isaac arnault watsonx 6](https://i.postimg.cc/KzgnVxLM/isaac-arnault-watsonx-6.png)](https://postimg.cc/R646JrgS)

</p>
</details>

<hr>

**Important**<br>
Clicking on **About** you can have an estimation of what the **watsonx data** would have cost you on a regular basis (default configuration)**.<br><br>

<details>
<summary>🐝 See console</summary>
<p>
  
[![isaac arnault watsonx 2](https://i.postimg.cc/9MfGmcy0/watsonx-isaac-arnault-2.png)](https://postimg.cc/2qPqTRcN)

</p>
</details>

7. Go back to **Create** tab, **Configure your resource**: leave everything as default and click **Create**.<br>
8. Once the service is created you'll be redirected to the resource unit list. Under **AI/Machine Learning** section you'll see that the **watsonx data** service has been successfully provisioned.
  
[![isaac arnault watsonx 7](https://i.postimg.cc/6Q426z3s/isaac-arnault-watsonx-7.png)](https://postimg.cc/FfmsDy3G)

9. On the **Databases** section wait until both services `Cloudant-oa` and `watsonx.data-dmr` are active.

[![isaac arnault watsonx 8](https://i.postimg.cc/bNqmGSkV/isaac-arnault-watsonx-8.png)](https://postimg.cc/qgZsSRm2)

10. Click on `watsonx.data-dmr` under **Databases**.

11. Click on **Open Web console**.

[![isaac-arnault-watsonx-9.png](https://i.postimg.cc/zDQfvKs8/isaac-arnault-watsonx-9.png)](https://postimg.cc/t7hbmZRM)

12. Now you are ready ton figure your infrastructure by setting up the **Engines, Catalogs, Buckets**.

13. On the Welcome tab you can have an overview of **watsonx data**. Click on Next for **Bucket configuration**. We will use the **Provision new IBM managed bucked** selected for this tutorial and we click **Next**.

[![ibm-watsonx-isaac-arnault-10.png](https://i.postimg.cc/DZZ2yw5S/ibm-watsonx-isaac-arnault-10.png)](https://postimg.cc/gwC9gdCp)

14.For **Catalog configuration** choose `Apache Iceberg`.

15. On **Engine configuration** leave `Presto` as engine and select **Starter** as engine size.

[![isaac-arnault-watsonx-11.png](https://i.postimg.cc/MHfqV3Cx/isaac-arnault-watsonx-11.png)](https://postimg.cc/ZvmGhHYD)

16. Now you are about to review your configuration, click **Next**.

17. Review your infrastructure configuration per listed above and click **Finish and go**.

18. Wait until your infrastructure is provisioned and you are now ready to go!

19. On your **watsonx data** dashboard you must have an overview on your newly provisioned infrastructure with the **Infrastructure components** such as `Engines`, `Catalogs`, `Buckets` and `Databases`.

[![New-Project-9.jpg](https://i.postimg.cc/pLRyMRNF/New-Project-9.jpg)](https://postimg.cc/jL3RzVSx)

20. On the side menu you can have all revelant sections useful for your daily activities such as **Infrastructure Manager, Data Manager, Query workspace** and **Query history**. Other sections **Access control, Billing and usage** are also key when using **watsonx data**.

21. Click on **Infrastructure Manager** on the side menu.<br>

[![isaac arnault watsonx 8](https://i.postimg.cc/bNqmGSkV/isaac-arnault-watsonx-8.png)](https://postimg.cc/qgZsSRm2)

This is the infrastructure that has been provisioned for **watsonx data**, you can click on **Buckets**.

[![New-Project-10.jpg](https://i.postimg.cc/7YyZSwZW/New-Project-10.jpg)](https://postimg.cc/232YDpvQ)

You can find relevant info about your provisioned bucket such as the `Bucket ID`, `Time created` and `Endpoint`.

22. On the **Access control** tab, you'll see who has access to your newly created bucket and that you can pass access to other IBM users.

[![New-Project-11.jpg](https://i.postimg.cc/43MJyT0w/New-Project-11.jpg)](https://postimg.cc/qtsfDW4C)

23.Go back to your **Infrastructure Manager** and click on **Catalog**. You'll see all related objects that have been created with the default iceberg_data catalog used as sample for this gist.<br> 

You can also navigate **Engines** from your **Infrastructure Manager** to have more details about the type of engine used and the access permission policies to that engine.

<hr>

**Important**<br>
Your side menu is really important for a daily use of **watsonx data** because it provides you four sections you'll mainly use on a daily basis: **Infrastructure Manager** (Infrastucture topology), **Data Manager** (Data objects and Ingestion Jobs), **Query Workspace** (RDBMS type query engine, SQL-based statements) and **Query history** (all passed queries from an historical perspective). Other menu items such as **Access control** and **Billing and usage** are also key if you are a **watsonx data** platform administrator or a Data governance manager.

[![isaac-arnault-watsonx-data-15.png](https://i.postimg.cc/rs2MGNMr/isaac-arnault-watsonx-data-15.png)](https://postimg.cc/zb7s8WLz)

24. Click on **Data Manager** on your side menu. This section is at the epicenter of **watsonx data** platform because it offers an understanding of the available data objects such as **Catalogs associated, System and Benchmarking data, Information schema (columns, schemata, table_privileges, tables and views)** and for each table its **Schema, Data Sample and DDL**.

[![isaac-arnault-watsonx-14.png](https://i.postimg.cc/nrhTP6Fb/isaac-arnault-watsonx-14.png)](https://postimg.cc/wynht4R0)

25. Another great view from the **Data Manager** panel on **Watson data**.

[![isaac-arnault-watsonx-15.png](https://i.postimg.cc/8z649dS5/isaac-arnault-watsonx-15.png)](https://postimg.cc/zyqTRg3Z)

26. Click on **Query Workspace** on your side menu. This is another great section of the platform letting users with read access query the objects from BI, Data Architecture / Engineering or Data Analysis perspectives.

27. Querying a specific table on **watsonx data** platform.

[![isaac-arnault-watsonx-16.png](https://i.postimg.cc/yNWZ2s9T/isaac-arnault-watsonx-16.png)](https://postimg.cc/3y5NvMty)

28.Try the **Query History** tool. It is particulary helpful when you need to dive into the performance of a specific query when optimizing your queries or stored procedures.

[![New-Project-13.jpg](https://i.postimg.cc/RFHnVdg6/New-Project-13.jpg)](https://postimg.cc/ZBJqw8t4)

<hr>

At this stage of the gist you must have a good overview of **watsonx data** platform and its core components: **Infrastructure manager, Data manager, Query workspace, Query history**.

Let's dive into two more components offered by the platform which allows you passing access control policies and integrating other services.

### Access Control
29. Click on **Access control** in your side menu.
29.1 You can manage access to specific resources in your infrastructure.

[![isaac-arnault-watsonx-17.png](https://i.postimg.cc/L5kYjXKm/isaac-arnault-watsonx-17.png)](https://postimg.cc/MfTpSzpL)

29.2 You can create access control policies to Allow or Deny that some Users or Groups perform specific actions on specific data objects.

[![isaac-arnault-watsonx-data-18.png](https://i.postimg.cc/vHM6bWfT/isaac-arnault-watsonx-data-18.png)](https://postimg.cc/fk2bvSHQ)

29.3 You can integrate third-party services to your **watsonx data** platform.

[![isaac-arnault-watsons-data-19.png](https://i.postimg.cc/CxxBfSvV/isaac-arnault-watsons-data-19.png)](https://postimg.cc/zV4XsZZd)

### Billing and usage
30. It provides you insights related to your consumption usage of **watsonx data** in **Running Units**.

[![isaac-arnault-watsonx.png](https://i.postimg.cc/GmgBFVNT/isaac-arnault-watsonx.png)](https://postimg.cc/gxRkdSGG)

It is highly recommended to click on **Manage in IBM Cloud** to get deeper insights regarding your infrastructure spendings.

[![isaac-arnault-watsonx-data-20.png](https://i.postimg.cc/d07h4nPH/isaac-arnault-watsonx-data-20.png)](https://postimg.cc/wtpxBXBL).

**Important feature**<br>
Go back to **Infrastructure Manager**.
At the top right click on **Add component** > **Add Database**
You'll see that many database types can be integrated to your **watsonx data** environment from relational to document-based databases.

### Infrastructure deletion
Go to **Infrastructure Manager** and for each provisioned component `Engine` `Catalog` `Buckets` `Databases` select the component and click on **Delete**.

[![isaac-arnault-watsonx-data-21.png](https://i.postimg.cc/P5JJ5KxX/isaac-arnault-watsonx-data-21.png)](https://postimg.cc/WdRT9GgC)

<hr>

## Official documentation
**watsonX data** Official documentation is available at: https://cloud.ibm.com/docs/watsonxdata.
**watsonX data** Start here: https://www.ibm.com/products/watsonx-data or here: https://cloud.ibm.com/docs/watsonxdata?topic=watsonxdata-getting-started
Do not forget to follow our tutorial for passing the promo code otherwise you'll have incurring costs while trying the platform.

## Official terms
`RU` = Running Units
`DDL` = Data Definition Language

<hr>

## Author

**Isaac Arnault for HUBIA ** - Introducing IBM products Watsonx data, Watsonx ai, Watsonx governance

## License

All public gists https://gist.github.com/HUBIA-io<br>
Copyright 2024, HUBIA<br>
MIT License, http://www.opensource.org/licenses/mit-license.php
