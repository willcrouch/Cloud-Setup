# Google Cloud Shiny Server Setup
Setup for Google Cloud VM instance with Shiny Server and a reverse proxy for your personal website.

Basically, I wanted to build my own shiny server, and it became a much larger process than I expected.

### Issues I ran into and solved:
1. Setting up a Shiny server on Google Cloud and not AWS, which was what I found for most walkthroughs
2. Getting Shiny to work on the compute engine with SQL & APIs
3. Getting Shiny to run through a reverse proxy since the native shiny server is only http and required a :3838
4. Getting polygons and some map features to work

### Order of files:
1. Google Cloud Setup
2. Shiny Server NGINX Setup
3. Shiny Setup
4. Additional Setup

## Call for packages that I frequently use: </br>
<a href= https://github.com/willcrouch/RPackageList>R Packages</a>

## Helpful Links
<a href=https://docs.rstudio.com/shiny-server/1.4.4/index.pdf>Shiny Server Admin Guide</a> </br>
<a href=https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/>NGIX Reverse Proxy Guide </a></br>
<a href=https://shiny.rstudio.com/>Shiny</a>
