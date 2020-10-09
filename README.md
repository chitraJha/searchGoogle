# searchGoogle
try:
    from googlesearch import search 
except ImportError:
    print("No module named 'google' found") 
query = "Afghanistan USA-Soviet Russia Relations in 1950 to 1980s"
  # tld = domain, num = number of searches, stop = stop at 10 links. pause = will print after 5 sec 
for j in search(query, tld="co.in", num=15, stop=10, pause=5): 
    print(j)
