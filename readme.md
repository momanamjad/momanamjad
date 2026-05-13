Mern stack Developer
<p align="left"> <img src="https://komarev.com/ghpvc/?username=momanamjad&label=Profile%20views&color=000000&style=flat" alt="STICKnoLOGIC" /> </p>

import time
import requests

url = "https://komarev.com/ghpvc/?username=momanamjad&label=Profile%20views&color=000000&style=flat"
while True:
    try:
        requests.get(url)
        time.sleep(0.5)
    except:
        pass

 
