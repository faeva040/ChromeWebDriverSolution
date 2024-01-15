# Chrome WebDriver Solution
there is a problem using chrome webdriver in your pycharm if your browser version is more than 119
If Chrome Web driver doesnt work, you can use this code to get Chrome webdriver in your code directly
```bash
from selenium import webdriver

from selenium.webdriver.chrome.service import  Service as ChromeService
from webdriver_manager.chrome import ChromeDriverManager
driver = webdriver.Chrome(service=ChromeService(ChromeDriverManager().install()))
```
