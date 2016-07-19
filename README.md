# webpowerpy
Python wrapper around WebPower SOAP-v5.1 API

### Installation

```python
pip install webpowerpy
```

### Usage 

```python
from webpowerpy import WebPowerClient
client = WebPowerClient(wsdl, username, password)
```

### Example

```python
  campaign_id = 1
  groups_id = [1,2,3]
  recipient_data = {
      'email': u'pasqual.guerrero@dooplan.com',
      'lang': u'es',
      'nombre': u'Pasqual',
      'apellidos': u'Guerrero Menéndez',
      ...
  }
  client.addRecipient(campaign_id, groups_id, recipient_data)
```
