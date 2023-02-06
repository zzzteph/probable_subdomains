# Probable (sub)domains


Online tool: [https://weakpass.com/generate/domains](https://weakpass.com/generate/domains)


<p align="center">
  <img src="https://github.com/zzzteph/probable_subdomains/blob/main/generate.gif?raw=true">
</p>




## TL;DR


During bug bounties, penetrations tests, red teams exercises, and other great activities, there is always a room when you need to launch amass, subfinder, sublister, or any other tool to find subdomains you can use to break through - like **test.google.com**, **dev.admin.paypal.com** or **staging.ceo.twitter.com**.
Within this repository, you will be able to find out the answers to the following questions:

1. What are the most [popular subdomains](https://github.com/zzzteph/probable_subdomains/tree/main/wordlists/subdomains)?
2. What are the most [common words](https://github.com/zzzteph/probable_subdomains/tree/main/wordlists/levels) in multilevel subdomains on different levels?
3. What are the most [used words](https://github.com/zzzteph/probable_subdomains/tree/main/wordlists/words) in subdomains?


And, of course, [wordlists](https://github.com/zzzteph/probable_subdomains/tree/main/wordlists) for all of the questions above!


## Methodology

As sources, I used lists of subdomains from public bugbounty programs, that were collected by [chaos.projectdiscovery.io](https://chaos.projectdiscovery.io/), [bounty-targets-data](https://github.com/arkadiyt/bounty-targets-data/) or that just had responsible disclosure programs with a total number of **6831** domains! If subdomains appear more than in 5-10 **different** scopes, they will be put in a certain list. For example, if **dev.stg** appears both in **\*.google.com** and **\*.twitter.com**, it will have a frequency of 2. It does not matter how often **dev.stg** appears in **\*.google.com**. That's all - **nothing more, nothing less**.







## Lists


### Subdomains

In these lists you will find most popular subdomains **as is**.

| Name | Words count  | Size |
|---|---|---|
| [subdomains.txt.gz](https://download.weakpass.com/probable/2023/02/subdomains.txt.gz) | 24837884 | 522MB |
| [subdomains_top100.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/subdomains/subdomains_top100.txt) | 100 | 655B  |
| [subdomains_top1000.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/subdomains/subdomains_top100.txt) | 1000 | 6.9KB  |
| [subdomains_top10000.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/subdomains/subdomains_top100.txt) | 10000 | 72KB  |

### Subdomain levels

In these lists, you will find the most popular words from subdomains split by levels. F.E - **dev.stg** subdomain will be split into two words **dev** and **stg**. **dev** will have level = 2, **stg** - level = 1. You can use these wordlists for combinatory attacks for subdomain searches. There are several types of level.txt wordlists that follow the idea of subdomains.




| Name | Words count  | Size |
|---|---|---|
| [level_1.txt.gz](https://download.weakpass.com/probable/2023/02/level_1.txt.gz) | 7703788 | 148MB |
| [level_2.txt.gz](https://download.weakpass.com/probable/2023/02/level_2.txt.gz) | 11379683 |  131MB |
| [level_3.txt.gz](https://download.weakpass.com/probable/2023/02/level_3.txt.gz) | 1158515 | 14MB  |
| [level_4.txt.gz](https://download.weakpass.com/probable/2023/02/level_4.txt.gz) | 179719 |  2.7MB |
| [level_5.txt.gz](https://download.weakpass.com/probable/2023/02/level_5.txt.gz) | 73384 |  860KB |
| [level_1_top100.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_1_top100.txt) | 100 | 620B  |
| [level_1_top1000.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_1_top1000.txt) | 1000 | 6.3K  |
| [level_2_top100.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_2_top100.txt) | 100 | 550B  |
| [level_2_top1000.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_2_top1000.txt) | 1000 | 5.8KB  |
| [level_3_top100.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_3_top100.txt) | 100 | 553B  |
| [level_3_top1000.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_3_top1000.txt) | 1000 | 5.2KB  |
| [level_4_top100.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_4_top100.txt) | 100 | 530B  |
| [level_4_top1000.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_4_top1000.txt) | 1000 | 5.1KB  |
| [level_5_top100.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_5_top100.txt) | 100 | 444B  |
| [level_5_top1000.txt](https://raw.githubusercontent.com/zzzteph/probable_subdomains/main/wordlists/levels/level_5_top1000.txt) | 1000 | 5.1KB  |


### Popular splitted subdomains


In these lists, you will find the most popular splitted words from subdomains on all levels. For example - **dev.stg** subdomain will be splitted in two words **dev** and **stg**. 

| Name | Words count  | Size |
|---|---|---|
| [words.txt.gz](https://download.weakpass.com/probable/2023/02/words.txt.gz) | 20305456 |  293MB  |
| [words_top100.txt](https://github.com/zzzteph/probable_subdomains/blob/main/wordlists/words/words_top100.txt) | 100 | 596B  |
| [words_top1000.txt](https://github.com/zzzteph/probable_subdomains/blob/main/wordlists/words/words_top1000.txt) | 1000 | 5.6KB  |
| [words_top10000.txt](https://github.com/zzzteph/probable_subdomains/blob/main/wordlists/words/words_top10000.txt) | 10000 | 62KB  |



### Dropbox


You can download all the files from [Dropbox](https://www.dropbox.com/sh/isa3dvufdpznc1v/AACop3PJJ73TMA4ZM_Ln9JgYa?dl=0)





## Attributions

- [berzerk0](https://github.com/berzerk0) for the inspiration with the great work [Probable-Wordlists](https://github.com/berzerk0/Probable-Wordlists)
- [chaos.projectdiscovery.io](https://chaos.projectdiscovery.io/)
- [bounty-targets-data/](https://github.com/arkadiyt/bounty-targets-data/)
- Based on some previous iteration of the same idea - https://github.com/zzzteph/substats



## Thanks!


## Updates

#### 01.2023 

- Sources 4095 
- Subdomains 21901389

#### 02.2023 


- Sources 6831 
- Subdomains 24837884
