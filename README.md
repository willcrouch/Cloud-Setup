# Cloud-Setup
Setup for Google Cloud with Shiny Server and a reverse proxy.

I wanted to build my own shiny server, and it began a much larger process than I expected.

Issues I ran into and solved:
1. Setting up a Shiny server on Google Cloud and not AWS, which was what I found for most walkthroughs
2. Getting Shiny to work on the compute engine with SQL & APIs
3. Getting Shiny a reverse proxy since the native shiny server is only http and required a :3838
