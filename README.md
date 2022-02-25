# KarnatakaGovtMarketPrice
An csv and a json file for the product and their price urls


### This file will give urls for all the products and their prices across all markets where the product is majorly sold in karnataka 

## Base url = ```http://www.krishimaratavahini.kar.nic.in/```

# Note

### Please replace the `DATEHERE` query with the present date 

ex

```bash
from datetime import date

todayDate = date.today().strftime("%d/%m/%Y")

...
url = data['url'].replace('DATEHERE',todayDate)
```
