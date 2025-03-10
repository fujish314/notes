## CRISPR/Cas9がノーベル賞を獲った記念回
### 何を話すのか問題
- 簡単なCRISPR研究の歴史
- 簡単なゲノム編集の歴史
- CRISPR (clustered regularly interspaced short palindromic repeats) ... Jansen et al. Mol Microbiol (2002)
- The Streptococcus thermophilus CRISPR/Cas system provides immunity in Escherichia coli. https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3241640/ Nucleic Acids Res. 2011 Nov; 39(21): 9275–9282.
- そもそもゲノム編集がなぜ必要で、人々はなぜゲノム編集を求めていたのか（ヒトゲノム計画GP-ReadからGP-Writeの時代へ）
- ゲノム編集 (SpCas9)がどうやって起こるのか

## Soh, memo
- Cas9-crRNA ribonucleoprotein complex mediates specific DNA cleavage for adaptive immunity in bacteria (PNAS, 2012) Siksnys論文
  - https://pubmed.ncbi.nlm.nih.gov/22949671/
- A programmable dual-RNA-guided DNA endonuclease in adaptive bacterial immunity. (Science 17 Aug 2012)
  - Cas9はcrRNA (CRISPR RNA)とtracrRNA (trans-activating crRNA)によってガイドされるDNAエンドヌクレアーゼである
  - 2つのヌクレアーゼドメインはDNAの２つのストランドをそれぞれ切断する
  - tracrRNAとcrRNAは標的への結合と切断に必須である
  - Cas9-tracrRNA:crRNA複合体の形成によってR-loopが標的との間に形成される
  - Cas9はa single chimeric RNAによってプログラムすることが可能である
  - これによって、Doudna+Emmanuelle. a single chimeric RNAによる簡便なゲノム編集（バクテリア）の実現
  - https://science.sciencemag.org/content/337/6096/816.long
- Scientifc Background on the Nobel Prize in Chemistry 2020 A TOOL FOR GENOME EDITING https://www.nobelprize.org/uploads/2020/10/advanced-chemistryprize2020.pdf 
- 哺乳動物細胞への応用 (Feng and Church, published 15 Feb 2013; online 2013/01/03かな？; Doudnaたちの半年後)
  - [Multiplex Genome Engineering Using CRISPR/Cas Systems. Cong et al., Science 2012](http://science.sciencemag.org/content/339/6121/819.long)これと
  - [RNA-Guided Human Genome Engineering via Cas9. Mali et al., Science 2012](http://science.sciencemag.org/content/339/6121/823.long) Churchのは図とかみるとFengのよりもかなり雑で、相当急いでいたのかなーという印象。基礎的な詳細なデータはFengのやつのほうが多くて充実している。
  - Doudnaたちは哺乳動物細胞の実験の経験がなかったそう（Sohの股聞き）... 先を越されてしまい、同じ内容の論文がeLifeに。https://elifesciences.org/articles/00471 Jan 29, 2013

### ノーベル賞
- A Tool for Genome Editing: The Royal Swedish Academy of Sciences has decided to award Emmanuelle Charpentier and Jennifer A. Doudna the Nobel Prize in Chemistry 2020, for the development of a method for genome editing.
- ポイントは以下: 
  - In 2012, Charpentier and Doudna reported “that the Cas9 endonuclease can be programmed with guide RNA engineered as a single transcript to cleave any double-stranded DNA sequence” [28]. Their discovery has led to widespread applications of the CRISPR-Cas9 system as a powerful and versatile tool in genome editing.
  - 一方、Siksnysらは以下のように評価されている： "However, the researchers did not notice the crucial importance of tracrRNA for sequence-specific cleavage of target DNA [29]." なので、ここから後の最小コンポーネントとしての"a single chimeric RNA"にはつながらないという理解なのかな。
- TALENはやっぱり合成が難しくて簡便で爆発的な利用という観点から外されたよう。  
