# Help\! The 911 System Has Fallen and Can’t Get Up\!

## *Systemic Deficits of the U.S. 911 System*

## Abstract

The US 911 system emerged in the 1970s from a need to standardize and simplify emergency response. Despite the national movement, implementation occurred at a county-level. As a result, response times, agency coverage, level of life support, and patient outcome have varied greatly over the nation’s numerous rural towns and bustling cities. This project aims to examine the variance of response times and identify so-called “911 help deserts,” where the time between calling 911 and getting help is significantly too long, or the quality of care is comparably low. There will be an analysis of how patient outcomes, including life or death, might be different in these deserts, compared to other well-resourced geographies. Finally, there will be a network-allocation analysis to suggest how to more optimally place ambulances, and how to improve the response, care, and outcome for all patients.

## Research Questions

1) How does 911 response time vary across the US?  
2) Where are there “help deserts”  
   1) Where response times are over the national average  
   2) Where there is only one agency or minimal agency coverage  
3) Where might there be “help oases”  
   1) Where there’s an abundance of resources  
   2) Response times are above national average  
4) What are the outcomes of these “help deserts vs oases” Are they statistically different than at the national or state level?

## Dataset

The data consists of the NEMSIS dataset. According to the website, “The National Emergency Medical Services Information System (NEMSIS) is the national system used to collect, store, and share EMS data from the U.S. States and Territories. NEMSIS develops and maintains a national standard for how patient care information resulting from prehospital EMS activations is documented. This information is voluntarily submitted to the National EMS Data Repository at NEMSIS by State and Territory EMS Officials.”

The data includes millions of lines, each representing an anonymized Patient Care Report (PCR). The PCR’s contain detailed information, including chief complaint, response time, treatment, and patient outcome. What interests us is patient outcome and county \- can we draw correlations between patient outcome and other variables?

## Analysis

* Discover the help deserts  
* A comparative analysis of response times, agency coverage, and patient outcomes in areas with varying levels of emergency service accessibility.   
* Network analysis of providers  
* How might patient outcome vs different factors such as response time, bls vs als equipped, treatment, etc.

## Limitations

This dataset is a convenience sample, not a population sampling, as the data is voluntarily submitted by agencies in all 50 states. As such, there is the possibility of disproportionate data reporting in higher-resourced areas. The data is not necessarily representative of 911 areas in the nation. However, it is expected that the data is at least illustrative of the state of emergency response.

Moreover, the data is event-based. Thus, certain agencies may have numerous reports for just one patient, and numerous agencies may report of the same event. 

Finally, locational data is obfuscated for agency and patient privacy. This imposes the greatest challenge – the inability to discover where certain help deserts are, stops us from understanding how geography is a factor. However, there’s the possibility to talk with the NEMSIS team and talk to various states to discuss further ways to handle this sensitive data.   
