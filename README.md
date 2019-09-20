### virtualenvwrapper
---
https://github.com/bernardobarreto/virtualenvwrapper

https://pypi.org/project/virtualenvwrapper/


```py
// tests/testtemplate/mytemplates/main.py

import logging
import os

log = logging.getLogger(__name__)

def template(args):
  print()
  project, project_dir = args
  filename = os.path.join(project_dir, 'TEST_FILE')
  print('Writing to %s' % filename)
  output = open(filename, 'w')
  try:
    output.write('\n'.join(args))
  finally:
    output.close()
  return



```

```
```

```
```
