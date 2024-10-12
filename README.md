## install all required libraries using following command from your project directory     
```bash
pip install -r requirements.txt
```

## how to run

### 1) directly
```bash
python pinterest.py
```

### 2) using import
```python
from pinterest import PinterestImageScraper
p_scraper = PinterestImageScraper()
is_downloaded = p_scraper.make_ready("messi")
```
