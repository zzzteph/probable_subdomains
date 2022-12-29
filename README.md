# Probable (sub)domains

Online tool: [https://weakpass.com/generate/domains](https://weakpass.com/generate/domains)

## TL;DR


During bug bounties, penetrations tests, red teams exercises, and other great activities, there is always a room when you need to launch amass, subfinder, sublister, or any other tool to find subdomains you can use to break through - like **test.google.com**, **dev.admin.paypal.com** or **staging.ceo.twitter.com**.
Within this repository you will be able to find out the answers to the following questions:

1. What are the most [popular subdomains](https://github.com/zzzteph/probable_subdomains/tree/main/wordlists/subdomains)?
2. What are the most [common words](https://github.com/zzzteph/probable_subdomains/tree/main/wordlists/levels) in multilevel subdomains on different levels?
3. What are the most [used words](https://github.com/zzzteph/probable_subdomains/tree/main/wordlists/words) in subdomains?


And, of course [wordlists](https://github.com/zzzteph/probable_subdomains/tree/main/wordlists) for all of the questions above!


## Methodology

As sources I used lists of data from bugbounty recon collected from [chaos.projectdiscovery.io](https://chaos.projectdiscovery.io/) with total number of **3753** different domains! If subdomains appear more than in 5-10 **different** scopes, they will be put in the certail list.For example, if **dev.stg** appears both in **\*.google.com** and **\*.twitter.com**, it will have frequency will be 2. It does not matter how often **dev.stg** appears in **\*.google.com**.  That's all -  **nothing more, nothing less**. 



### Lists

#### Subdomains

In this lists you will find most popular subdomains **as is**.

| Name | Words count  | Size |
|---|---|---|
| [\*subdomains.txt]() | 21897020 | 501MB |
| [subdomains_top100.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/subdomains/subdomains_top100.txt) | 100 | 976B  |
| [subdomains_top1000.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/subdomains/subdomains_top100.txt) | 1000 | 14KB  |
| [subdomains_top10000.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/subdomains/subdomains_top100.txt) | 10000 | 383KB  |

#### Subdomain levels

In this lists you will find most popular splitted words from subdomains splitted by levels. F.E - **dev.stg** subdomain will be splitted in two words **dev** and **stg**. **dev** will have level = 2, **stg** - level = 1.  You can use these wordlists for combinatory attack for subdomain search. There are several types of **level.txt** wordlists that following the idea of subdomains.




| Name | Words count  | Size |
|---|---|---|
| [\*level_1.txt]() | 8093280 | 153MB |
| [\*level_2.txt]() | 7555608 |  106MB |
| [\*level_3.txt]() | 1490933 | 18MB  |
| [\*level_4.txt]() | 205953 |  3.2MB |
| [\*level_5.txt]() | 71716 |  849KB |
| [level_1_top100.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_1_top100.txt) | 100 | 584B  |
| [level_1_top1000.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_1_top1000.txt) | 1000 | 6.1KB  |
| [level_2_top100.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_2_top100.txt) | 100 | 549B  |
| [level_2_top1000.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_2_top1000.txt) | 1000 | 5.6KB  |
| [level_3_top100.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_3_top100.txt) | 100 | 530B  |
| [level_3_top1000.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_3_top1000.txt) | 1000 | 5.0KB  |
| [level_4_top100.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_4_top100.txt) | 100 | 524B  |
| [level_4_top1000.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_4_top1000.txt) | 1000 | 4.9KB  |
| [level_5_top100.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_5_top100.txt) | 100 | 448B  |
| [level_5_top1000.txt] (https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_5_top1000.txt) | 1000 | 5.0KB  |


#### Popular splitted subdomains


In this lists you will find most popular splitted words from subdomains. F.E - **dev.stg** subdomain will be splitted in two words **dev** and **stg** 

| Name | Words count  | Size |
|---|---|---|
| [\*words.txt]() | 17226458 |  278MB  |
| [words_top100.txt] (https://github.com/zzzteph/probable_subdomains/blob/main/wordlists/words/words_top100.txt) | 100 | 579B  |
| [words_top1000.txt] (https://github.com/zzzteph/probable_subdomains/blob/main/wordlists/words/words_top1000.txt) | 1000 | 5.3KB  |
| [words_top10000.txt] (https://github.com/zzzteph/probable_subdomains/blob/main/wordlists/words/words_top10000.txt) | 10000 | 60KB  |


\* - commpressed with 7z.





## Attributions

- [berzerk0](https://github.com/berzerk0) for the inspiration with the great work [Probable-Wordlists](https://github.com/berzerk0/Probable-Wordlists)
- [chaos.projectdiscovery.io](https://chaos.projectdiscovery.io/)
- Based on some previous iteration of the same idea - https://github.com/zzzteph/substats



## Thanks!
