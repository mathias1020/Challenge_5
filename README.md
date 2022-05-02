# Challenge_5

# **Financial planning evaluation of emergency funds and likely investment outcomes for portfolio allocations**

This notebook is a planning tool that evaluates the emergency preparedness of unions members as well as forecasts likely outcomes based on how the assets are allocated. It performs the following:

-Displays the member's emergency fund allowing them to understand their level of preparedness  
-Provides a breakdown of holdings by asset class   
-Performs Monte Carlo simulations to visualize the statistically likely outcomes based on the provided allocation  

---

# **Technologies**

This application is a Jupyter Notebook and makes use of the Alpaca SDK as well as python-dotenv llibraries. These can be installed with the following commands: 

```python
pip install alpaca-trade-api
pip install python-dotenv
```

---

# **Installation Guide**

Before running the application you need to import the following modules:
```python
import os
import requests
import json
import pandas as pd
from dotenv import load_dotenv
import alpaca_trade_api as tradeapi
from MCForecastTools import MCSimulation

%matplotlib inline
```

---

# **Contributors**

Developed by:

Matthew Crater

[Linked In](https://www.linkedin.com/in/matt-crater/)

---

# **License**

MIT