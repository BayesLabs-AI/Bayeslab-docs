# Chart🔮

Bayeslab provide various kinds of charts base on [Plotly](https://plotly.com) with some customizations.&#x20;



<figure><img src="../.gitbook/assets/image (86).png" alt=""><figcaption></figcaption></figure>

For what charts are available, please take a reference at [https://plotly.com/javascript/](https://plotly.com/javascript/)

<figure><img src="../.gitbook/assets/image (87).png" alt=""><figcaption></figcaption></figure>



{% hint style="info" %}
Although plotly supports having multiple charts in the same plot, it has certain issue like missing colors or slow rendering or broken lines

We recommend using single chart when possible.
{% endhint %}

## Interaction

The charts are fully interactive. Try zoom in/out, pan or download as picture.

<figure><img src="../.gitbook/assets/image (96).png" alt=""><figcaption></figcaption></figure>

### Export Chart Data

You can download raw data for this chart via this button\


<figure><img src="../.gitbook/assets/image (97).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The exported data here is what directly used for chart to display,  not original data that used to compute what's to display.
{% endhint %}

## Interpretation

We automatically provide a chart interpretation for it's data/trend/insights, and you can continue chatting with Chart Copilot later.

<figure><img src="../.gitbook/assets/image (91).png" alt=""><figcaption></figcaption></figure>

## Editing

When mouse hovering over the chart, you'll see Edit button.

<figure><img src="../.gitbook/assets/image (89).png" alt=""><figcaption></figcaption></figure>

You can change the display options of this chart here.&#x20;

<figure><img src="../.gitbook/assets/image (88).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
The options modified here are stored together with this block.&#x20;

If the block's code is regenerated again, the options would NOT be merged to avoid any confliction.
{% endhint %}

## Chart Copilot

Clicking "Explain" or "Chat" would bring up this Chart Copilot:

<figure><img src="../.gitbook/assets/image (90).png" alt=""><figcaption></figcaption></figure>

It automatically analyze and explain the chart using latest Generative AI model, and provides follow up questions.&#x20;

You can then generate some report paragraph to go together with this chart in your report:

<figure><img src="../.gitbook/assets/image (92).png" alt=""><figcaption></figcaption></figure>
