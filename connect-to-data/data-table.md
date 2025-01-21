---
coverY: 0
layout:
  cover:
    visible: false
    size: full
  title:
    visible: true
  description:
    visible: true
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
---

# Data Table🔮

## What is data table

A data table is a **typed, structured two-dimensional table** that serves as the basis for data analysis.&#x20;

It can be simply understood as similar to a database table or a structured excel table (no merging rows, skipping rows, etc.).

<figure><img src="../.gitbook/assets/image (58).png" alt=""><figcaption></figcaption></figure>

### Column Type

In Bayeslab, we keep a simple type structure:&#x20;

* Text
  * for short or long strings.
* Number
  * for integer types
* Real
  * For decimal/money types
* Date
  * For various type of dates regardless of format



## Import from file

When you import your data into Bayeslab, you can use excel or csv files to do so, or directly reference [external sources](external-sources.md).

<figure><img src="../.gitbook/assets/image (59).png" alt=""><figcaption></figcaption></figure>

Then upload files or choose from what you already uploaded to this project

<figure><img src="../.gitbook/assets/image (60).png" alt=""><figcaption></figcaption></figure>

Seeing a preview of your files data, click next

<figure><img src="../.gitbook/assets/image (62).png" alt=""><figcaption></figcaption></figure>



You'll see Bayeslab automatically analyze the data, assign correct Type and generate corresponding descriptions.&#x20;

<figure><img src="../.gitbook/assets/image (61).png" alt=""><figcaption></figcaption></figure>

Also, it generates an assessment of the data quality and provide recommendations to do if the quality is not so good.



Click Confirm and you'll see your table is now added.

<figure><img src="../.gitbook/assets/image (63).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
All data table are accessible from all projects.  If you'd like to remove this table from current project but keep for others, use "Unbind" to remove.
{% endhint %}

## Writeback

By default, AI would not try to write anything back to data table.&#x20;

If you'd like to do so, simply add **"write back"** or anything similar as part of your prompt.

<figure><img src="../.gitbook/assets/image (95).png" alt=""><figcaption></figcaption></figure>

## Preview Data

Click anywhere with that table name, you'll see data preview on the right.&#x20;

See [here](../analyze-visualize/data-preview.md) for more details on this panel.

<figure><img src="../.gitbook/assets/image (64).png" alt=""><figcaption></figcaption></figure>

## Table Copilot

By clicking "AI" in Data Preview, you're now in one of the most interesting feature of Bayeslab: Table Copilot

<figure><img src="../.gitbook/assets/image (65).png" alt=""><figcaption></figcaption></figure>

You'll see firstly it automatically analyze the data in various aspects (schema, data quality.. etc).

Then it follows with recommendations, sample questions, and some ready to do actions.

<figure><img src="../.gitbook/assets/image (66).png" alt=""><figcaption></figcaption></figure>

Each of the actions here are uniquely put into your current data's context, and provide pinpointed recommendations.

<figure><img src="../.gitbook/assets/image (67).png" alt=""><figcaption></figcaption></figure>

Pay special attention to "Editor", which represents you can directly send this back to editor as an AI block and try run it!



For example, "automatic explore" would send back to editor as below:

<figure><img src="../.gitbook/assets/image (69).png" alt=""><figcaption></figcaption></figure>

Click "Run" will give AI a chance to explore on it's own and produce several interesting results.

<figure><img src="../.gitbook/assets/image (70).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
Try this on every data table, have fun!
{% endhint %}
