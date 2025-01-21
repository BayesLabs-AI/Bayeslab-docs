# Working with Files



{% hint style="warning" %}
We recommend use data table for all csv/excel, see [here](data-table.md).



For other file types, continue read along.
{% endhint %}

## Manage files in Project

<figure><img src="../.gitbook/assets/image (49).png" alt=""><figcaption></figcaption></figure>

You can upload/delete/rename files and folders using this panel on the lower-left corner.

Maximum single file size supported is 200MB.

## Reference files in AI Block

Same with data table and others, you can reference file/folder using double backslash (//)

<figure><img src="../.gitbook/assets/image (50).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
You can only reference file when machine is connected.
{% endhint %}

## Sample Use Cases

### Merge Excel/CSV Files

<figure><img src="../.gitbook/assets/image (51).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Note please keep every file's first sheet in the same format, same columns. Or you might get unexpected results.
{% endhint %}

### Bulk OCR

<figure><img src="../.gitbook/assets/image (52).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Tips: also use double backslash(//) to reference the internal OCR function
{% endhint %}

### JSON Files

<figure><img src="../.gitbook/assets/image (53).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Be sure to provide JSON schema as currently we do not read JSON schema automatically.



Also keep every json file's using the same schema, or you might get unexpected results.
{% endhint %}

### PDF Table

<figure><img src="../.gitbook/assets/image (54).png" alt=""><figcaption></figcaption></figure>

{% hint style="info" %}
Only simple table is doable in this way, for complex tables like financial reports or receipts, we're planning to provide specific built-in tool for that.&#x20;



Please contact us via crew@bayeslab.ai if you're interested.
{% endhint %}

