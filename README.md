### How to deploy
1. [Fork this project]([url](https://github.com/lirtual/cloudflare-pages-reverse-proxy/fork)) on Github and click on Star !!!!
2. After selecting Connect to Git in the CF Pages console, select the project cloudflare-pages-reverse-proxy and click Start Setup.
3. At the bottom of the Setup Build and Deployment page, select Environment Variables (Advanced) and add the variable HOSTNAME for the variable name, and HOSTNAME for the value of the target domain name you need to reverse proxy (no need to bring in the protocols, such as www.cloudflare.com), and then click Save and Deploy.
