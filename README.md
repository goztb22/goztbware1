# gamesense.is_CRACKED
GAMESENSE CRACK / GAMESENSE.IS / Join My Discord: https://discord.gg/gBsC839Dne / Join My WebSite https://h4xr0x.cc #NEVERLOSE.CC=NOOBS

ORIGIN IP: 
94.130.72.121/ ORIGIN SERVER HOSTNAME: static.121.72.130.94.clients.your-server.de

FrontEnd Librarys for CDN: 
https://api.cdnjs.com/libraries?

Mailgun Magnificent API Keys:
44c539b5-c536-4979-a553-23b91d5f007b / 542ff402-d9e8-4f86-8bbd-752b72093b1c

![image](https://user-images.githubusercontent.com/65768277/124374959-ed3d7400-dc64-11eb-9e24-cdab8653c064.png)

DNS records are misconfigured and it leaks their origin IP  as seen in the screenshot below:
it was this; but someone must of told them that; because they changed this recently. Probaby to hide that they were on a server that they used for 2 years; selling a GameSense themed paste. Abyse. Below is my awesome art work and SS of the JS, as it shows gamesense.is enabled CORS requests; even citing in this SS how you can use: https://easyxdm.net/wp/  to exploit it. Allowing CORS , cross origin resources sharing, we can use custom headers requests to app.js that they allow CORS to because they have 3 different Endpoints, to have transactional API calls to features; such as purchase the cheat cheat; they White List, IP's to open up parts of the website.

![image](https://user-images.githubusercontent.com/65768277/124374191-c4b27b80-dc5e-11eb-9d5b-003c80234402.png)

now read that; carefully and understand why im mirroring the site @ https://gamesense.software/forums/GameSense.html  Custom header and it acts as the site whitelisted; and I 
was sending same site requests cross origin. I got access to some the entire site source like this.

![image](https://user-images.githubusercontent.com/65768277/124374241-51f5d000-dc5f-11eb-939d-5b533c7899a4.png)
![image](https://user-images.githubusercontent.com/65768277/124374262-73ef5280-dc5f-11eb-8750-58ecf8fcea40.png)

Now lets ping them; and see the IP of the origin server due to their misconfiguration on cloudflare, and because they recently moved the mailserver to the ORIGIN SERVER; this costed them everything; every transactional record; databases, cheat. Lucky, for you guys; im a RED HAT and I wont be scamming kids, engaging in blackhat activities or hurting innocent people, but you shouldn't be hosting anything; much less having access to peoples personal & financial information because your unable to protect it.

![image](https://user-images.githubusercontent.com/65768277/124374330-03950100-dc60-11eb-9a59-76db5bb78c36.png)

now remember I said there was 3 endpoints; and if you read the docs(https://cli.vuejs.org/) theres a reason for this. 1 for the cdn/cloudflare(cdnjs.com) 1 for origin server 94.130.72.121 ; which is where the website is hosted on; and 1 for their LocalHost which uses app.js to allow CORS by generating CSRF tokens for Authentication through login. You can see that in the SS's below or goto this shodan link: https://www.shodan.io/host/94.130.72.121

![image](https://user-images.githubusercontent.com/65768277/124374539-b9148400-dc61-11eb-8065-27595850549a.png)
![image](https://user-images.githubusercontent.com/65768277/124374557-da757000-dc61-11eb-8ffc-722d82ef196e.png)

doing an openssl scan on the origin server on port 587 which is what mail is delivered to; we can see that the misconfiguration of the DNS records is the reason they DOX their origin IP. they didnt make a CNAME record for the mail server. Normally this is OK because the mail servers are hosted on a different address and generally only need a MX record. But they moved the mail server (was 18.184.226.115) to the ORIGIN SERVER; and thats why we can ping mail.gamesense.is and get its IP.
![image](https://user-images.githubusercontent.com/65768277/124375118-0266d280-dc66-11eb-89f9-281213a6a5a9.png)
API KEY ![image](https://user-images.githubusercontent.com/65768277/124375191-7bfec080-dc66-11eb-9ff5-864daa7f46fb.png)

They really messed up on the mail server; they use https://www.mailgun.com/ for api on the mailserver; now remember I said they messed up on it? here you can all download their api key for it. Meaning you can have access to everything! Read these full docs to use https://documentation.mailgun.com/en/latest/  or see how to send transactional emails in nodejs https://www.mailgun.com/blog/how-to-send-transactional-email-in-a-nodejs-app-using-the-mailgun-api/ 

![image](https://user-images.githubusercontent.com/65768277/124375354-5b833600-dc67-11eb-9cfe-1d714d3a55d2.png)
![image](https://user-images.githubusercontent.com/65768277/124375209-a3558d80-dc66-11eb-8a83-32c55aa1bff8.png)

The MainGun was known for issues just like this in the past. by doing a GET request on the mail servers DNS records they misconfigured; it gives you an API key. (heres a link of this happening before to other mailgun customers: https://www.mailgun.com/blog/how-to-send-transactional-email-in-a-nodejs-app-using-the-mailgun-api/ 
CONCLUSION: We can make api calls to confirm we bought the cheat; bypass 2factor auth on someone elses account; reset their passwords; send an api request for transactional records such as POS, obtain personal financial records such as customers or their crypto wallets.

![image](https://user-images.githubusercontent.com/65768277/124374771-b31fa280-dc63-11eb-94f4-d79ebefffc13.png)
![image](https://user-images.githubusercontent.com/65768277/124374685-16f59b80-dc63-11eb-8c03-1b458c8bd226.png)
![image](https://user-images.githubusercontent.com/65768277/124374763-a438f000-dc63-11eb-9c85-dabd137ad0fd.png)

Next time the neverlose staff and the best " reverse engineers in the world" they might want to first learn how to configure DNS records #h4xr0x gg
Give me a little bit and I will host these skids cheat for free on gamesense.software join my discord for more information on this and other cracks such as gamesense.pub.
https://discord.gg/gBsC839Dne



