# Tabular data

Tabular data is data that is in tables. This is one of the most prevalent forms of data in industry, yet underrepresented in research. Things like information about real estate, bank accounts, user profiles, spreadsheets etc... are usually stored in tables.

| site\_name | state | elevation | MMI | EPT\_PTAX | data\_source | agency |
| :--- | :--- | :--- | :--- | :--- | :--- | :--- |
| Flat Creek | OR | 1571 | 26.31 | 21.62 | WSA | EPA |
| Barlow Creek | OR | 1010 | 79.12 | 53.49 | WSA | EPA |
| Stevens Creek | WA | 1051 | 61.31 | 61.54 | WSA | EPA |

Fast.ai features a very handy library to create and train models based on tabular data, import it as follows:

```text
from fastai.tabular import *
```

## Categorical and Continuous data

Tabular data usually consists of two different kinds of data. Categorical data is represents data that can be divided into unique groups. Food types, gender, marital status etc...

Continuous data is data which exists at all points of an interval. For example, the price of a stock:

![The stock price fluctuates continuously](../.gitbook/assets/image%20%2814%29.png)

These two types of data have to be treated differently. If you were to treat food type as a continuous datatype, then your model might classify your red strawberry ice-cream image as an ice-steak.

The fast.ai library makes this easy:

```text
cat_names = ['workclass', 'education', 'marital-status',  'relationship', 'race']
cont_names = ['age', 'salary', 'square-footage-house']

# and then you just indicate the datatypes to the TabularList function 
data = TabularList.from_df(cat_names=cat_names, cont_names=cont_names)
```

 The _data_ object can then be fed directly into your model.

