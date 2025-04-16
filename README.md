# The 100 Queries Project

## Background

We, Maarten Sprenger and Carsten Schnober, investigated the quality and usability of the search results provided by Google for a hundred different search queries by children aged eight to twelve for ‘*Slim Zoeken’*.

With this project we want to demonstrate that, on the one hand, it is a waste of time and misleading for children to just let them *google* something (without further guidance).
On the other hand, we want to make a start on systematically answering the question of what web search is worth at the moment, both from the perspective of the supply on the web and from what is retrieved by Google.

With this we would like to connect to a revival that we see in the critical approach to web search for users.

The underlying idea is that in terms of observation (expert opinion) an estimated 90% of the result pages have a commercial component, varying from content as a vehicle for advertisements to product descriptions and blogs that should lead to more traffic to the websites in question, under the SEO motto ‘Content is king’. This combined with the experience that at the same time about 80% of the results pages for primary school children seem to be (too) difficult to access. Up until now, this was mainly anecdotal evidence from Maarten's more than fifteen years of experience in working with online information for children (see also M. Sprenger, Children's Informatie Who cares?, 2014).

## Who are we?

### Maarten Sprenger

Maarten Sprenger is an information professional, educational editor and author of two *Slim Zoeken* books for 8-14 year olds. He is currently working on [Slim3](https://www.slimzoeken.nu/slim3uitleg), understandable information about web search for school, study or work. Two versions are available, one for primary education and one for all others.

From 2019 to the present, Maarten advised at various times in the context of the *Actualisatie van de nieuwe Kerndoelen* ("Actualization of the new national Core Education Objectives"), for the subjects Dutch and for Digital Literacy.

[slimzoeken.nu,](https://www.slimzoeken.nu/) [linkedin.com/in/msprenger](https://www.linkedin.com/in/msprenger/?locale=nl_NL)

### Carsten Schnober

[Carsten](https://carschno.github.io/) is a software engineer and researcher in Natural Language Processing (NLP), Information Retrieval, Machine Learning.

Carsten works for the NL eScience Center, where he develops advanced technological research software for researchers in the Humanities and Social Sciences.

## The Study

We provide a comprehensive description of the methodology on our [Notion page](https://slimzoeken.notion.site/Onderzoeksverslag-100-Queries-e24772ddefb4467ba7d0f167171875cf) in Dutch.
Find an overview in English below.

## Design

For this study, we selected one hundred queries from a list of two hundred random, authentic searches by primary school pupils.
The queries originate from [Wizenoze bv](https://www.wizenoze.com/), with thanks to Thijs Westerveld.

Queries, result pages and associated sources are stored in three databases, in which all records were provided with labels on metadata, relevance, quality and parent companies.
A fourth database for parent companies was added later to gain a better picture of the clustering of content providers.

## Methodology

### Query selection

The selection of queries was made as follows:

- Dutch language
- Primary school age (8-12 years)
- Period 1 year (2022)
- Random samples
- Delivered in a set of 200; manually reduced to a working set of 100 with a balanced distribution of topics, including dirty words and brand names. Evidently incomplete text and vague typos (haaaaaaaaao) and repetitions ('Ronaldo', 'Cristiano Ronaldo') were omitted.
- All raw data and annotations are [available here](./data/)

## Output

- This [notebook](https://github.com/SlimZoeken/100queries/blob/main/notebooks/analysis.ipynb) shows the raw data analyses.
- Presentation of *100 Queries* at the i&i spring conference: <https://ieni.github.io/april2024/honderd-queries>
- Presentation at the [HSN Conference 2024](https://hsnbundels.taalunie.org/bijdrage/zoeken-onderzocht-het-100-queries-project/).
- Paper "[100 Queries: What do Dutch Children See on the Web?](100_queries_romcir.pdf)" published at the [5th Workshop on Reducing Online Misinformation through Credible Information Retrieval (ROMCIR)](https://romcir.disco.unimib.it/)
