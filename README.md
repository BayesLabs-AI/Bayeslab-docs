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

# 👻 Welcome to Bayeslab

Welcome to **Bayeslab**, an AI-first data workbench designed for everyone—whether you're a solo entrepreneur, a business analyst, or just someone looking to work smarter with data. Bayeslab is here to empower you to analyze, visualize, and harness the power of your data without needing a full-fledged data team.

Start here: [https://bayeslab.ai](https://bayeslab.ai)

## Why Bayeslab

Data has become the backbone of decision-making, but the tools we use haven’t always kept up. For many, working with data often means wrestling with spreadsheets, jumping between tools, or waiting for data engineers to clean and prepare datasets.

_Bayeslab changes the way._



Whether you’re an analyst, manager or operations, Bayeslab helps you go further, faster—without needing a Ph.D. in data science.

See the video below to get a quick start:

{% embed url="https://www.youtube.com/watch?v=P1w7aLvFBRw" %}
Introduction to Bayeslab
{% endembed %}

## Editing Experience

Bayeslab is a notebook style editor which follows [Literate Programming](https://en.wikipedia.org/wiki/Literate_programming) principles. Meaning it's:

* **Natural language based**
  * Use natural language to describe what you'd like to do, and explain the results
  * Special context reference to help AI accurately understand
  * AI will help to do what you describe,  such as run/analyze/interpret
    * For more details of how to write prompt with content reference, see [Writing Prompt](basics/prompt.md)

<figure><img src=".gitbook/assets/image (12).png" alt=""><figcaption></figcaption></figure>

* **Block based**
  * The notebook is organized into a sequence of blocks representing step by step exploration nature of data analysis. (If you've used [Jupyter](https://jupyter.org/) before, this should be almost identical)

<figure><img src=".gitbook/assets/image (22).png" alt=""><figcaption><p>Sample of an AI block</p></figcaption></figure>



And it's specialized for **data analysis scenarios**, meaning:

*   **Handle various kind of data natively**

    * Import [data files](connect-to-data/data-table.md#import-from-file) or connect to [external data sources](connect-to-data/external-sources.md).
    * Schema definition built-in and automatically provide to Gen-AI as context


* **Provide fine-tuned AI help across** [**entire analysis flow**](analyze-visualize/your-analysis-flow.md)
  * Including cleaning, analysis/chart ideas, result interpretation, report generation...etc
  * Latest Generative-AI model with well-designed context for data analysis
  * Smart identification of result variable for use in later editing

{% hint style="info" %}
Currently we're using a mixture of GPT-4o, O1 and Claude 3.5 Sonnet. This will evolves in the future as base model evolves.
{% endhint %}

<figure><img src=".gitbook/assets/image (25).png" alt="" width="158"><figcaption><p>Sample Copilot Response</p></figcaption></figure>

* **Enable self-editing at every step to get better results**
  * Full editing experience for underline python/sql/data/chart to suite your own needs
  * Unified SQL to join/process all data sources

<figure><img src=".gitbook/assets/image (24).png" alt=""><figcaption><p>Built-in Code Editing Experience</p></figcaption></figure>

For a more detailed feature explanation please view [first glance](basics/quick-start-must-see.md).

### When to use Bayeslab?

In modern data stack(though lots of different versions),  it's **hard to see** where Bayeslab is landed exactly:

<figure><img src=".gitbook/assets/image (23).png" alt=""><figcaption><p>source:<a href="https://a16z.com/emerging-architectures-for-modern-data-infrastructure/">https://a16z.com/emerging-architectures-for-modern-data-infrastructure/</a></p></figcaption></figure>

This also says for itself the **complex situation** that real data analysis scenarios resides in. &#x20;



We design Bayeslab firstly towards the end user side which has **tabular data**,  need to get results quickly that **doesn't fit in excel**, and without hard-core data team **always ready** for disposal.

#### **Tabular data**

Bayeslab works best with tabular data. It can be exported from any business system or by email, or can be from any database/data lake.&#x20;

Currently we don't plan to support processing of raw data that requires hand-tweaked deep learning models or videos.

{% hint style="info" %}
Bayeslab can process non-structured data like image/pdf/pure text using OCR + Generative-AI, into data table for analysis later. See [here](connect-to-data/working-with-files.md).
{% endhint %}

#### **Beyond Excel**

Excel has many good ways such as flexible cells/pivot table/format/formulas.  It's the most popular "data analysis" tool and will continues to be so in quite some time.

While we all know it's limitations:

* Limited Data Size
  * Bayeslab can handle hundreds of millions of rows, GB level data with ease.
* Cross join with other data source
  * Bayeslab unifies different data source under single SQL and unified schema.
* Professional Charts
  * Bayeslab provides professional [data charts](analyze-visualize/chart.md), customizable.
* Advanced Modeling
  * Bayeslab provides [machine learning](analyze-visualize/machine-learning.md) so simple, you just need to say a few words
* Formular/VBA
  * Bayeslab uses natural language to describe logic, while still editable for finer detail
* AI Help
  * Strangely Excel has not come with a good copilot for now.&#x20;
  * Bayeslab provide specific copilot for[ every step of analysis flow](analyze-visualize/your-analysis-flow.md).

When excel has done it's first couple of operations and more serious analysis is required, Bayeslab is what you need.

#### Self-Sufficient

To analyze data efficiently and with correct result, often we need quite a lot of skills, or helps from others that have that skill.&#x20;

The skills include but not limit to:

* Programming
  * Python
  * SQL
* Statistics/Math
* Domain knowledge
* Library
  * Plotly/sklearn/numpy/scipy/pandas....etc

With Bayeslab, you can complete analysis **without** any , some even **all of the skills** above.  Bayeslab with AI can fill in any skill as necessary , acting as a good intern/analyst/engineer.&#x20;

At the same time you can still use your own skill to produce maximum results, since all underline details are available to you and customizable.



## Design Principles

### **AI-First**

What does it mean to be an AI-first product? It’s about embracing the strengths of AI to augment human capabilities, not just automate tasks. At Bayeslab, we focus on:

1. **Context Is Everything:** AI hallucinations (or errors) often stem from missing context. By grounding our platform in your real-world data and workflows, we ensure accurate, trustworthy insights.
2. **Autonomy Where It Matters:** Bayeslab acts as an agent, tackling technical details(python/sql/pandas/sklearn/plotly…etc) so you can focus on what and why. Think of it as the perfect partner: tireless, thorough, and always scanning for solutions you might have missed.
3. **Empowering 10x Employees:** With Bayeslab, you don’t need a dedicated data team to achieve data-driven success. It’s about making individuals 10x more efficient—freeing your data engineers to work on data quality and infra, and empowering you to act as your own analyst.

### **Security You Can Trust**

Handling sensitive data comes with responsibility. Bayeslab is built with security as a priority, ensuring your data is safe, private, and handled with care. Whether you're managing customer data or internal reports, you can trust Bayeslab to keep your information secure.

### **Shaping the Future of Data Work**

We’re in the early days of AI-first products. Just as early graphical user interfaces shaped how we interact with computers, AI-first tools are shaping how we interact with data.&#x20;

It’s not just about getting the best result in a single task—it’s about making data analysis accessible, reliable, and intuitive for everyone.

**Welcome to Bayeslab—your AI-first data workbench. Let’s get to work.**

