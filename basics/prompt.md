# Prompt🔮

## Prompting

The most important part of using Bayeslab is to write your prompt so AI knows what you'd like to do.&#x20;

<figure><img src="../.gitbook/assets/image (12).png" alt=""><figcaption><p>Prompt Sample</p></figcaption></figure>

A prompt is consist of 2 type of components:

* **Quotes ( Use // to reference, enter to select)**
  * Reference of different objects for AI to accurately pinpoint what you mean.
  * You can reference **data table/file/params/results** and **built-in tools** for different cases.
  * See [here](prompt.md#quotes) for more details.

<figure><img src="../.gitbook/assets/image (21).png" alt=""><figcaption></figcaption></figure>

<mark style="color:red;">**\[should be a gif above, showing input of // and input of a name, then enter]**</mark>

* **Requirements**
  * the natural language for what you'd like to do with the data, can be clean/transform/chart/building machine learning model....etc.



By naturally combine these  2 parts in any order, you can describe what you do in a most natural way:

> With Data A join Data B,  do some logic,  draw chart, then send chart to x@x.com

## Tips for Writing Prompts

Although it's natural expression, we do find helpful to follow the following rules and get most success rate

1. Clearly say your requirements using **actions words**
   1. avoid maybes, wrong names, too much generic/abstract expressions
   2. avoid "give me best result", "analyze it all"
2. Keep requirements **simple** in one prompt
   1. do not ask 10 things at the same time
3. Use **logical words**
   1. like if, then, first, finally
4. Use **sample** to convey complex logic
   1. for example: how you'd like to split/extract parts of string
      1. Extract year-month part of date column,  like for 2024.3.24, extract 2024-03

## Quotes

Quotes are special parts of prompt that reference specific data/object and bring in **context** of that data/object for better AI understanding.

{% hint style="info" %}
**Context** is everything.  When you reference a data table, it's not only the table name, but also the **schema/sample data/statistics** of that table goes with your requirement into AI.  Same goes for other referenced objects.



It's crucial for AI to know enough context before it can function correctly.&#x20;
{% endhint %}

<mark style="color:red;">\[image]</mark>

## Using Template Params

There's a special type of quotes called **Params**, currently only **text and number** are supported.&#x20;

These are **place holders** for AI to consider when generating code, and then user can change it without re-generating entire code.&#x20;

It's suitable for simple parameter editing in an complex logic prompt, to avoid unstable AI output.



For example, you would write something like:

<figure><img src="../.gitbook/assets/image (40).png" alt=""><figcaption></figcaption></figure>

after running it, you can click the param and change abc to bcd

<figure><img src="../.gitbook/assets/image (41).png" alt=""><figcaption></figcaption></figure>

and run again, you'll see it's quick to just run and skip entire AI generation part

<figure><img src="../.gitbook/assets/image (42).png" alt=""><figcaption></figcaption></figure>

{% hint style="warning" %}
These template params are just replacing without any real logic change. If the content of param would impact the whole logic, it should NOT be used as params.



For example,  rules text like "larger than 3"/"less than average" should NOT be put as params as it would impact how computation logic is going to run, thus requires AI to generate.
{% endhint %}



