import requests
import json

city = input("Enter City :")

url = f"https://api.weatherapi.com/v1/current.json?key=5c7edd4be91b431ead8194515242102&q={city}"

r = requests.get(url)
# print(r.text)

wdic = json.loads(r.text)
print(f"Weather Of {city} is:",wdic["current"]["temp_c"])
