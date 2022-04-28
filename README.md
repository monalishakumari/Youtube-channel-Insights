# Youtube-channel-Insights
Overview
```python
from googleapiclient.discovery import build
```


```python
# importing libraries
import pandas as pd
import seaborn as sns
```


```python
# Youtube api key and  created youtube service

api_key= 'AIzaSyArd2byl6crUvFe-2Mzb3tIhiszF500bTA'
channel_ids = ['UCNU_lfiiWBdtULKOw6X0Dig', #KrishNaik
              'UC7cs8q-gJRlGwj4A8OmCmXg', #Alex the analyst
              'UC8uU_wruBMHeeRma49dtZKA', #chandoo
              'UCeVMnSShP_Iviwkknt83cww', #CodeWithHarry
              'UCmXZxX_qexEZxhb5_vQKPCw' #Aman dhattarwal
             ] 
