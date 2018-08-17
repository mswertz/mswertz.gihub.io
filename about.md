---
title: about
intro: We are a driven group of developers and data scientists on a mission to deliver great infrastructure for life sciences
layout: green
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

Primary MOLGENIS support is currently coordinated by the Genomics Coordination Center (GCC) hosted at the Dept of Genetics of University Medical Center Groningen. GCC provides hosting of MOLGENIS services, project based development and routine analysis.

Contact: Prof.Dr. Morris Swertz  (m.a.swertz@rug.nl)

MOLGENIS is used and financially supported by:

{% for link_hash in page.partners %}
  {% for link in link_hash %}
<a href="{{ link[1] }}" _target="blank">
  <img src="/images/{{ link[0] }}" alt="{{ link[1] }}" style="max-width: 200px; padding: 20px" class="partner">
</a>
  {% endfor %}
{% endfor %}
