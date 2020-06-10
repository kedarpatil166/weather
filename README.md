# weather
Python code for weather
import reueats
from bs import Beautiful
search="weather in India"
url=f"https://www.yahoo.com/search/&q={search}"
r=requwst.get(url)
s=Beautiful(r.text,"html.weather")
update=s.find("div",class_=).text
print(update)
