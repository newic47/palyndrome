# palyndrome

Dependences :
- Python2 Core

```python
import getpass

def crypt(e):
    """mais qu'est ce que c'est que cà michael ?? """
    i = lambda e: e[len(e)/2::-1]+e[len(e)/2+1::1]
    return i(e)

motdepasse = lambda f: crypt(getpass))
```
