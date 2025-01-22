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

# Quick Start - Must See🔮

**Let's begin!**

After login, you'll see below:

<figure><img src="../.gitbook/assets/组 7418@1x.jpg" alt=""><figcaption><p>Main Page</p></figcaption></figure>

The main functions are:

* Getting Started
  * Create/View all my projects
* Library
  * Sample projects from Bayeslab and community
* Data Table
  * Connect/Import/List all of tabular data across all projects.
* Integrations
  * Manage integration with external systems.
* Tutorial
  * Official tutorials of Bayeslab including editing/visualization/statistics/machine learning.
* Account
  * Manage [account and billing](broken-reference) plans.
* Switch Language
  * Change UI and AI language.

{% hint style="success" %}
You can use any language to prompt , though we recommend using the same language as your data.
{% endhint %}

{% hint style="info" %}
When switching language,  not only UI will change,  but also AI will reply in the language you choose. &#x20;



For example, you can switch the language to Japanese and still use English to prompt,  AI will try the best to reply in Japanese.
{% endhint %}

## First Try

Every fun starts with creating a project by clicking "New Project", and input the project name.

<figure><img src="../.gitbook/assets/image (29).png" alt=""><figcaption></figcaption></figure>

A **project** is consist of **pages** and a page is consist of **blocks**. &#x20;

Blocks are the base building elements of an analysis flow, representing a single step or document paragraph. See [here](editor/literate-programming.md) for more explanation.

<figure><img src="../.gitbook/assets/image (26).png" alt=""><figcaption><p>Relationship of Project/Page/Block</p></figcaption></figure>



Then you'll start with a single page in editor, as below:

<figure><img src="../.gitbook/assets/image (28).png" alt=""><figcaption><p>Editor UI</p></figcaption></figure>

* for more details, please see [Editor](editor/).

### Import Data

Then you can import data using data table from excel:

<figure><img src="../.gitbook/assets/image (30).png" alt=""><figcaption></figcaption></figure>

Upload your own csv/excel and click **next**

<figure><img src="../.gitbook/assets/image (31).png" alt=""><figcaption></figcaption></figure>

You can see AI automatically analyze and assign correct type/description for your data, along with recommendations on data quality.&#x20;

<figure><img src="../.gitbook/assets/image (32).png" alt=""><figcaption></figcaption></figure>

* for more details, please see [Data Table](../connect-to-data/data-table.md)

By clicking Confirm you can see the table is correctly imported and referenced in current block

<figure><img src="../.gitbook/assets/image (33).png" alt=""><figcaption></figcaption></figure>

### Data Preview

You can now click this table (in block or on the left list of tables) to preview it's data\


<figure><img src="../.gitbook/assets/image (34).png" alt=""><figcaption></figcaption></figure>

* for more details, please see [Data Preview](../analyze-visualize/data-preview.md)

### Write Prompt

Then you can continue write a prompt like "Average Revenue for lifecycle, bar chart"

<figure><img src="../.gitbook/assets/image (35).png" alt=""><figcaption></figcaption></figure>

{% hint style="success" %}
You can reference this data in another block using double back slash ( // ) , and input the table name.

![](<../.gitbook/assets/image (36).png>)
{% endhint %}

### Run

Then click run or use Ctrl+Enter (Command +Enter), AI will parse the requirement and try execute.

<figure><img src="../.gitbook/assets/组 7420@1x.jpg" alt=""><figcaption><p>AI Block with Result</p></figcaption></figure>

The result consists of several parts:

* **Output**
  * Detail logs of AI executing. Please see [AI Block](../analyze-visualize/ai-block.md) for more details.
* **Chart**
  * Interactive chart if user want to visualize in chart format. You can edit the chart display right here.
  * Please see [Chart](../analyze-visualize/chart.md) for more details.
* **Result**
  * A list of AI identified result that can be viewed or referenced for further processing in later blocks.

{% hint style="success" %}
You can use double backslash ( // ) to reference any previous **Result** in later blocks.&#x20;

![](<../.gitbook/assets/image (38).png>)



This is extremely useful when later block need to further process previous block's result data.
{% endhint %}

### Copilot

Clicking **Chat** or **Explain** on chart would take you to **Chart Copilot**, where you can ask any follow up **questions** about the chart or get **recommendation** on next steps.

<figure><img src="../.gitbook/assets/image (39).png" alt=""><figcaption></figcaption></figure>

Please see [Copilot](../analyze-visualize/chart.md#copilot) for more details.



## Next Step

Congratulations! You've done first analysis. Get in more details of editing by viewing[ Analysis Flow](../analyze-visualize/your-analysis-flow.md).

Or understand data in Bayeslab more by seeing details in [Data Table](../connect-to-data/data-table.md).



