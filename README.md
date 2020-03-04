# Enrich-analysis.pl
Enrich_analysis.pl, a perl script for enrich analysis of differentially expressed genes.</br>
Transcriptome data analysis is facing a major challenge to dig out research related information and provide professional interpretation. Enrichment analysis put forward rational option. In this article, a perl script Enrich_analysis.pl was written for analyzing differentially expressed gene product annotations in biology. And the statistical test is Fisher's exact test. Enrich analysis performed domain aggregation by combining gene expressions before testing for the differentially expressed. It helps investigators to assign biological meaning to some group of genes.</br></br>
如何从庞大的基因表达数据库里挖掘出有价值的信息，并做出科学的生物学诠释，是基因表达分析领域的重要挑战。富集分析为解决这一问题提出了合理的方案。用Perl语言写了一个脚本——Enrich_analysis.pl，可根据基因注释信息进行基因富集分析，并利用Fisher's Exact Test做检验。富集分析先根据生物学知识将基因归类，然后进行基因差异表达分析，提高数据的可解释性。</br></br>

## License
Academic users may download and use the application free of charge according to the accompanying license. Commercial users must obtain a commercial license from Xukai Li. If you have used the program to obtain results, please cite the following paper:</br>
> 李旭凯*，王钇杰，王俊杰. Enrich_analysis.pl，差异表达基因富集分析的perl脚本, 生物信息学, 2018, 16(3):178-183.</br></br>
> https://kns.cnki.net/KCMS/detail/detail.aspx?dbcode=CJFD&dbname=CJFDLAST2018&filename=XXSW201803007&v=MzA4ODdlWmVkbUZ5bmhXcjNKUFRYWWViRzRIOW5Nckk5Rlk0UjhlWDFMdXhZUzdEaDFUM3FUcldNMUZyQ1VSTE8=</br>
</br>
## Getting started
Put __`Enrich_analysis.pl`__ and annotation.txt, DEGlist.txt files in a same dir, then run:</br>
```
    perl  Enrich_analysis.pl  annotation.txt  DEGlist.txt  >  Result.txt
```
</br>
