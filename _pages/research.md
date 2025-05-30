---
layout: archive
title: "Research"
permalink: /research/
author_profile: true
---

[Sheltering from Climate Risks](http://nrickard.github.io/files/NatalieRickard_JMP.pdf) (JMP)

Using administrative data on flood insurance, I document pervasive heterogeneity in the adaptive investments of American households. In response to increasing climate risks, affluent home-owners tend to elevate their properties whereas poorer households rely on higher levels of insurance. I develop a climate risk model with heterogeneous agents, housing insurance and investment in adaptation that can account for these findings. Counterfactual simulations reveal that as climate risk rises, financially constrained households avoid investing in adaption in favour of insurance subsidised by the government. As a result, the poorest households hold an increasing share of the housing stock most exposed to climate risks.

<sub>*Presented: LBS, NYU Student Lunch*</sub>

[Non-essential Business Cycles](http://nrickard.github.io/files/AndreolliRickardSurico_NEBC.pdf), with Michele Andreolli and Paolo Surico

This paper documents three main regularities on post-WWII data for the United States: (i) spending on non-essentials is more sensitive to the business-cycle than spending on essentials; (ii) earnings in non-essential sectors are more cyclical than earnings in essential sectors; (iii) non-essential industries employ a larger share of hand-to-mouth workers. We develop and estimate a two-sector New-Keynesian model with non-homothetic preferences, hand-to-mouth workers and sectoral labour force heterogeneity that is consistent with these findings. We use the model to revisit the transmission of stabilisation policies. A main finding is that the interaction of cyclical product demand composition and cyclical labour demand composition greatly amplifies the effects of monetary policy, which in our economy can be equivalently implemented by a mix of consumption and labour taxes. However, a VAT change applied only to non-essentials (only to essentials) has a far larger (smaller) impact than a uniform VAT change of the same size.

<sub>*[Online Appendix](http://nrickard.github.io/files/AndreolliRickardSurico_NEBC_OnlineAppendix.pdf)*</sub>,<sub>*[VOXEU Summary](https://cepr.org/voxeu/columns/how-spending-rich-drives-income-poor-and-why-matters-business-cycle)*</sub>

<sub>*Media coverage: [JP Morgan Private Bank Insights](https://privatebank.jpmorgan.com/nam/en/insights/markets-and-investing/how-will-the-rate-cutting-cycle-impact-economic-activity-and-market-returns)*</sub>

<sub>*Presented:  PSE Macro Days, Barcelona School of Economics Summer Forum\*, CREi/UPF\*, Boston College\*, LBS, Norges Bank\*, EWMES, SEA\*, RES\*, ECB ChaMP Conference\*, Midwest Macro, NASM of the Econometric Society\*, SED, NBERSI (Monetary Economics)\*, Oslo Macro Conference, Princeton\**</sub>

[The Green Energy Transition in a Putty-Clay Model of Capital](http://nrickard.github.io/files/GreenTransitionPuttyClay_GilchristMartinezRickard.pdf), with Simon Gilchrist and Joseba Martinez

We develop an integrated assessment model (IAM) that incorporates a putty-clay technology for capital accumulation in both the energy and final goods sectors. Final-goods production requires energy inputs that are produced by either a fossil-fuel burning sector or a clean energy sector. Following the IAM literature, fossil fuel usage leads to an accumulation of carbon that reduces aggregate production through a climate damage function that is external to the choices made by households and firms. The putty-clay features of the model imply delayed adjustment of fossil-fuel use to carbon taxes. Because of these delays, the carbon tax must be forty percent larger in the putty-clay model relative to a more standard model of vintage capital to meet the same carbon stock goals over a thirty year horizon. Green energy subsidies are also effective in reducing carbon stocks in the medium run but have a lower impact on longer-term fossil fuel use compared to carbon taxes of comparable size.

<sub>*Recipient of a grant from the [Wheeler Institute, supported by the Sui Foundation](https://wheelerinstituteresearch.org/project/putty-clay-and-the-green-transition/)*</sub>

<sub>*Presented: NYU Stern Macro lunch\*, CREi/UPF\*, Imperial\*, Maryland\*, Chicago\**</sub>

\* = Presentations by co-authors


{% if author.googlescholar %}
  You can also find my articles on <u><a href="{{author.googlescholar}}">my Google Scholar profile</a>.</u>
{% endif %}

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% endfor %}
