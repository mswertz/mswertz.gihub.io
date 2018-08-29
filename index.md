---
title: MOLGENIS
intro: Flexible software for scientific data
layout: blue
partners:
- bbmri-nl-bw.png: http://bbmri.nl
- bbmri-eric-bw.png: http://bbmri-eric.eu
- umcg-bw.png: http://geneticsgroningen.nl
- rd-connect-bw.png: http://rd-connect.eu
- lifelines-bw.png: http://lifelines.net
- trait-bw.png: http://ctmm-trait.nl
- bioshare-bw.png: http://bioshare.eu
- biomedbridges-bw.png: http://biomedbridges.eu
- panacea-bw.png: http://www.wageningenur.nl/en/Expertise-Services/Chair-groups/Plant-Sciences/Laboratory-of-Nematology/Projects/PANACEA.htm
- tifn-bw.png: http://www.tifn.nl
- rug-bw.png: http://www.rug.nl/gbic
- energysense-bw.png: http://www.energyacademy.org/research/energysense
- dtl-bw.png: http://dtls.nl
- nfu-bw.png: http://www.nfu.nl/publicaties/data4lifesciences
- e-rare-bw.png: http://www.erare.eu/financed-projects/insaid
---

# Get molgenis
MOLGENIS data platform: [docs](https://molgenis.gitbooks.io/molgenis/content/), [war](https://molgenis.gitbooks.io/molgenis/content/quickstart/guide-tomcat.html), [docker](https://github.com/molgenis/docker), [code](https://github.com/molgenis/molgenis), [releases](https://github.com/molgenis/molgenis/releases)

MOLGENIS compute platform: [docs](https://rawgit.com/molgenis/molgenis-compute/master/molgenis-compute-core/README.html),[releases](https://github.com/molgenis/molgenis-compute/releases), [code](https://github.com/molgenis/molgenis-compute).

Pipelines: DNA pipeline [docs](https://molgenis.gitbooks.io/ngs_dna/), [code](https://github.com/molgenis/NGS_DNA), [RNA pipeline](https://github.com/molgenis/NGS_RNA), [easybuild for automatic installation](https://github.com/molgenis/easybuild-easyconfigs)

# Partners
MOLGENIS is developed in collaboration with and funded by:

{% for link_hash in page.partners %}
  {% for link in link_hash %}
<a href="{{ link[1] }}" _target="blank" style="float:left">
  <img src="/images/{{ link[0] }}" alt="{{ link[1] }}" style="max-width: 100px; padding: 20px" class="partner">
</a>
  {% endfor %}
{% endfor %}
