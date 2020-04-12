# pythuadetector
Python library for detecting User Agents.

# My user agent is Unknown!
Go to Issues and put in an issue with this format please:
```
User agent: UnknownUserAgent
Expected output: Browser Name on Platform Name
Actual output Browser Name/Unknown Browser on Platform Name/Unknown Platform
```

# Usage
```python
import pythuadetector

USERAGENT = "Mozilla/5.0 (Windows NT 10.0; Win64; x64; rv:75.0) Gecko/20100101 Firefox/75.0"

# Output should be Mozilla Firefox on Microsoft Windows 10
pythuadetector.uadetect(USERAGENT)
```
