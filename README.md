# ip-details-
Python in pydroid 3








import requests
import pprint
ip=input("enter your ip address:----")
url=f"https://ipapi.co/{ip}/json/"
r=requests.get(url)
pprint.pprint(r.json())
