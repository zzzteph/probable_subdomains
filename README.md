# Probable (sub)domains

Online tool: [https://weakpass.com/generate/domains](https://weakpass.com/generate/domains)

## TL;DR



During bug bounties, penetrations tests, red teams exercises, and other great activities, there is always a room when you need to launch amass, subfinder, sublister, or any other tool to find subdomains you can use to break through - like **test.google.com**, **dev.admin.paypal.com** or **staging.ceo.twitter.com**.
Within this repository you will be able to find out the answers to the next questions:

1. What are the most popular subdomains?
2. What are the most common words in multilevel subdomains on different levels?
3. What are the most used words in subdomains?


And, like with the passwords -  masks, lengths, and character distributions!  

And, of course WORDLISTS for all of questions above!


## Methodology

If subdomains appear more than in 5-10 **different** scopes, they will be put in the certail list.For example, if **dev.stg** appears both in **\*.google.com** and **\*.twitter.com**, it will have frequency will be 2. It does not matter how often **dev.stg** appears in **\*.google.com**.  That's all -  **nothing more, nothing less**. 

## Attributions

- berzerk0 for the inspiration with the great work https://github.com/berzerk0/Probable-Wordlists
- https://chaos.projectdiscovery.io/ 
- Based on some previous iteration of the same idea - https://github.com/zzzteph/substats



## Thanks!
