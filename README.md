# pythuadetector
Python library for detecting User Agents.

# Usage
```python
import pythuadetector

USERAGENT = "Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:75.0) Gecko/20100101 Firefox/75.0"

# Output should be Mozilla Firefox on Microsoft Windows 10
pythuadetector.uadetect(USERAGENT)
```
