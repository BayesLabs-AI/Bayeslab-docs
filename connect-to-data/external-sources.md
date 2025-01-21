---
coverY: 0
---

# External Sources

Bayeslab supports directly query from external sources using SQL,  without having to sync the data.&#x20;

## Database

<figure><img src="../.gitbook/assets/image (55).png" alt=""><figcaption></figcaption></figure>

When creating table, you can create from Database

<figure><img src="../.gitbook/assets/image (56).png" alt=""><figcaption></figcaption></figure>

Currently only MySQL and PostgreSQL are supported, we're going to add more DB types soon.



Be sure to add more description to your columns(data schema), so our AI can better generate results for you.

You can also edit the schema later in Data Preview

<figure><img src="../.gitbook/assets/image (57).png" alt=""><figcaption><p>View and edit data schema</p></figcaption></figure>



{% hint style="warning" %}
Write back to external database is not supported now.
{% endhint %}

## More Integrations

There're more data source that we'll unify under a **single SQL accessible interface**, and enables cross joins.

We're planning to add:

* Amazon Redshift
* Apache Cassandra&#x20;
* Apache Hive&#x20;
* Apache Iceberg
* Clickhouse
* Elasticsearch
* Google BigQuery&#x20;
* Google Sheets&#x20;
* MariaDB&#x20;
* Microsoft SQL Server&#x20;
* MongoDB
* Oracle
* Prometheus
* Redis
* Snowflake&#x20;

{% hint style="warning" %}
Coming soon!
{% endhint %}
