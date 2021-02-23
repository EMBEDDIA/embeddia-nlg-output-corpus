# A corpus of computer generated news texts

This is a small corpus of computer generated news texts. The texts were generated using a rule-based automated journalism system built within the [EMBEDDIA research project](http://embeddia.eu/). The Embeddia research project is supported by the European Union’s Horizon 2020 research and innovation program undergrant agreement No 825153, project EMBEDDIA (Cross-Lingual Embeddings for Less-Represented Languages in European News Media). 

The texts are based on data from EuroStat, the statistical agency of the European Union. **We make no quarantees regarding the correctness of the information in the texts.**

The corpus contains texts in two languages, Finnish and English. For both languages, the texts discuss three distinct topics: consumer price indices (`cphi`), healthcare funding (`health_funding`) and healthcare spending (`health_cost`), all discussed on the national level within Europe. Each text has a focus country (as indicated by the filename, e.g. Norway for `full-fi-health_cost-NO.txt`) but can contain information about other countries as well when relevant to the text as per the understanding of the underlying NLG system.

For the underlying data (updated since text generation), see the following resources:
- https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=ei_cphi_m&lang=en
- https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=hlth_sha11_hf&lang=en
- https://appsso.eurostat.ec.europa.eu/nui/show.do?dataset=hlth_sha11_hc&lang=en
