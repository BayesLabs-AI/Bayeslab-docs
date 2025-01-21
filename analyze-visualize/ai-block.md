# AI Block🔮

## UI

<figure><img src="../.gitbook/assets/image (82).png" alt=""><figcaption></figcaption></figure>

AI block is consist of several parts:

* **Prompt** Box
  * Contains user prompt
* **Toolbar**
  * **Run**
    * Execute this block, see [Run](run.md) for more details
  * **Data Reference**
    * Reference table or file, see [Data Table](../connect-to-data/data-table.md) for more details
  * **Code Show/Hide**
    * Show/Hide underline code for viewing/editing, see [Coding](../developer/coding.md) for more details
  * **More**
    * **Copy Block**
      * See [here](ai-block.md#copy-and-paste-block) for more details
    * **Regenerate**
      * See [here](ai-block.md#regenerate) for explanation
    * **Delete**
      * Note this is **not undoable**
* **Log**
  * Output of the executed code, including [Charts](chart.md)
* **Result**
  * Contains AI identified data or ML model that can be referenced in later blocks.

## Regenerate

In some cases, you can use regenerate for AI to do its work again without changing any of your prompt.&#x20;

This is mainly used when:

1. Prompt is clearly stated and doable, but results are not correct
2. Many requirements in your prompt, and a few is not satisfied
3. Random error

## Copy and Paste Block

You can copy and paste block to any page/project. &#x20;

<figure><img src="../.gitbook/assets/image (93).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Note the referenced Result would not automatically copy to another page/project. Be sure to also copy the block that generate the specific Result param you referenced.
{% endhint %}
