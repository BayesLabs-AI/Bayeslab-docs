# Coding🔮

We know many of you knows Python coding from heart, and we know AI is not perfect  by a long shot.&#x20;

Thus we provide a full Python editing experience right along with our AI experience for any tweaking needed.&#x20;



There're 2 places that you can write/modify code:

## Coding in AI Block

<figure><img src="../.gitbook/assets/image (47).png" alt=""><figcaption></figcaption></figure>

After running for the first time, you'll see all the code generated is accessible via "Code" button on tool bar.&#x20;

You can change the code as you wish but be aware:

1. Modify code does not sync back to original prompt
2. Modify of the prompt will regenerate entire code again,  removing any changes you make

So it's best to modify this code for small bugs or behaviors that is not specified in your prompt.

{% hint style="info" %}
For completely different logic, we recommend to modify prompt first and run to get a version for start.
{% endhint %}



Several code section worth explaining and noticed during your modification:

### Package install/Reference

```python
!pip install pandas plotly

import pandas as pd
from plotly.subplots import make_subplots
import plotly.graph_objects as go
```

Bayeslab automatically generates code to install and reference required libraries for each block.  If package already exists, it will just continue.&#x20;

Please do not remove since each block might be executed individually without previous block.

### Chart Display

```python
# Display the chart
display(JSON({"type": "plotly", "config": json.loads(json.dumps(fig.to_dict(), cls=PlotlyJSONEncoder))}))
```

Bayeslab uses display function to transfer chart option/data to frontend.  Currently only plotly charts are supported.

### Result Display

```python
try:
    from actionbook import VariableToPreview, displayVariable
    displayVariable([VariableToPreview("average_revenue_by_lifecycle", average_revenue_by_lifecycle, "Average Revenue by Lifecycle DataFrame"),VariableToPreview("fig", fig, "Average Revenue by Lifecycle Bar Chart"),VariableToPreview("df", df, "Queried Data DataFrame")])
except:
    pass
```

The final part of code shows a try-except section with displayVariable function. This is AI generated for particular variable be shown as "Result" and can be referenced in other block again.&#x20;

Please do not change/remove. You can change the variable name string though.

## Code Block

<figure><img src="../.gitbook/assets/image (48).png" alt=""><figcaption></figcaption></figure>

Code block is just like a normal Jupyter code cell, it contains python code and execute, displaying result  under this block.

Use this block if you got ready to use python code , or feel more comfortable start coding from scratch.

