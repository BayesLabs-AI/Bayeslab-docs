# Editor

<figure><img src="../../.gitbook/assets/组 7419@1x.jpg" alt=""><figcaption><p>Editor UI</p></figcaption></figure>



There're different sections in editor:

* **Table of Content**
  * Show structure of current page by Headings(document block). Click to quickly navigate.
* **Data Table**
  * Manage a list of data tables used in current project.  See [Data Table](../../connect-to-data/data-table.md) for more details.
* **Main Editing Panel**
  * Add/Remove/Rearrange all **blocks**
  * See [Intro to Blocks](./#intro-to-blocks) for more details.
* **Toolbar**
  * **Run All**
    * Execute all blocks on current page from top to bottom.
  * **Machine Status**
    * View/Reset the running machine this page will be executed on. See [Environment](../../developer/environment.md) for more details.
  * **Variables**
    * \[Developer]  View current session's variables name/value. See [Variables](../../developer/variables-panel.md) for more details.
  * **Sharing**
    * Share page/project with others. See [Sharing](../../collaboration/sharing.md) for more details.
  * **Help**
    * Provide samples of AI block for various scenarios. Click to insert at end of page.
  * **Page Settings**
    * Rename/Copy and change various setting of current page.
  * **Account**
    * Show current quota and plan.
* **Other**
  * **All Pages**
    * Show/Switch all pages of current project
  * **Files**
    * Manage files of current project. See [Working with Files](../../connect-to-data/working-with-files.md) for more details.

## Intro to Blocks

Blocks are building elements of a page, there're several type of blocks:

### AI Block

<figure><img src="../../.gitbook/assets/image (22).png" alt=""><figcaption><p>AI Block</p></figcaption></figure>



AI Block is the key element that transform your prompt requirement into execution and results.&#x20;

First please input your prompt and reference data you'd like to analyze/process in this block as part of&#x20;

### Document Blocks

<figure><img src="../../.gitbook/assets/image (14).png" alt=""><figcaption><p>Document Blocks</p></figcaption></figure>

There're several different document blocks including text/headings, image and videos.  The text/headings blocks supports partial markdown syntax.&#x20;

### Code Block

<figure><img src="../../.gitbook/assets/image (13).png" alt=""><figcaption><p>Code Block</p></figcaption></figure>

Code Block gives developer a free style Python coding experience much like Jupyter.&#x20;

Please see [Coding](../../developer/coding.md) for more details.

## Adding Blocks

<figure><img src="../../.gitbook/assets/image (19).png" alt=""><figcaption><p>Add block</p></figcaption></figure>

You can add block to any location using "+" button at the left between blocks. Or directly use the buttons to add to the end.

<figure><img src="../../.gitbook/assets/image (20).png" alt=""><figcaption><p>Add block via button</p></figcaption></figure>

## Arrange Blocks

Block can be sorted using drag and drop:

<figure><img src="../../.gitbook/assets/image (15).png" alt=""><figcaption><p>Drag and Drop block</p></figcaption></figure>

{% hint style="info" %}
When clicking "run all",  the page is executed sequentially from first block to the last.
{% endhint %}

## Copy & Paste Block

You can also copy and paste block by clicking "copy" on block's toolbar

<figure><img src="../../.gitbook/assets/image (17).png" alt=""><figcaption></figcaption></figure>

And paste anywhere:

<figure><img src="../../.gitbook/assets/image (18).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You can past to different pages, even different project.
{% endhint %}

{% hint style="info" %}
You can even paste the content of block to another person using IM or email for troubleshooting or quick showing, while the data referenced in this block will NOT be shared this way.



If you'd like more complete sharing of the page/project, please see [Sharing](../../collaboration/sharing.md).
{% endhint %}
