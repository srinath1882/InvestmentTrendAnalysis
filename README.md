# InvestmentTrendAnalysis

XYZ, an asset management company, wants to make investments in a few companies. The CEO of XYZ wants to understand the global trends in investments so that she can take the investment decisions effectively.

**The Business Objective**: The objective is to identify the best sectors, countries, and a suitable investment type for making investments. The overall strategy is to invest where others are investing, implying that the 'best' sectors and countries are the ones 'where most investors are investing'.

XYZ has two minor constraints for investments:
  1. It wants to invest between 5 to 15 million USD per round of investment

  2. It wants to invest only in English-speaking countries because of the ease of communication with the companies it would invest in. For our analysis, consider a country to be English speaking only if English is one of the official languages in that country. (List of English Speaking country has been manually created in the form of a dictionary in the notebook)
  
**Goals of data analysis**: Your goals are divided into three sub-goals:
  - Investment type analysis: Comparing the typical investment amounts in the venture, seed, angel, private equity etc. so that XYZ can choose the type that is best suited for their strategy.
  
  - Country analysis: Identifying the countries which have been the most heavily invested in the past.
  
  - Sector analysis: Understanding the distribution of investments across the eight main sectors. (Note that we are interested in the eight 'main sectors' provided in the mapping file. The two files — companies and rounds2 — have numerous sub-sector names; hence, you will need to map each sub-sector to its main sector.)

There are three dataset:
  1. Companies: This dataset is provided in the form of a link which contains the data in plain text format. It contains basic data of companies. From this site we need to load the data.
  2. round2.csv: This contains the funding amount, iinvestment type and many other features related to each company.
  3. mapping.csv: This file maps the numerous category names in the companies table (such 3D printing, aerospace, agriculture, etc.) to eight broad sector names. The purpose is to simplify the analysis into eight sector buckets, rather than trying to analyse hundreds of them.
