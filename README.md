# DNasfS

### What is DNS?

DNS is an acronym for `Domain Name System`, and it is a Internet technology that enables internet applications and their users to name things that require a globally unique name. It's much easier to remember a unique name for a web page rather than a long string of numbers or code.

### How does the DNS work?

In short, DNS is very much like the US Postal Service. If you are on `google.com` and you're trying to get to `amazon.com`, the DNS query will go through quite a few steps:
  - type in a DNS query by entering in `amazon.com` into your URL field
  - your computer sends the query to the nearest DNS caching server (this is the equivalent of the nearest Post Office after you've dropped mail in the mail slot)
  - When your query arrives at the caching server, there's a good chance it knows the address of your query if it has received that query before - if it doesn't, then it sends you on to another caching server
  - When your query arrives at a caching server that knows the address, then the caching server will send the requested data back to your local computer.
