# Trust in Government Statistics

## United Nations

Fundamental Principles of 
Official Statistics, **Principle 3**:

> *Accountability and Transparency*
To facilitate a correct interpretation of the data, 
the statistical agencies are to present information 
according to scientific standards on the sources, 
methods and procedures of the statistics [^UNprinciples]

[^UNprinciples]: [United Nations Fundamental Principles of Official Statistics](https://unstats.un.org/unsd/dnss/gp/FP-New-E.pdf)

## National Academies

Principles and Practices for a Federal Statistical Agency, **Principle 2**: 

> Credibility among Data Users
A federal statistical agency must have credibility
with those who use its data and information [^CNSTAT]

[^CNSTAT]: National Academies of Sciences, Engineering, and Medicine. 2017. Principles and Practices for a Federal Statistical Agency: Sixth Edition. Washington, DC: The National Academies Press. <https://doi.org/10.17226/24810>.

## OMB

"... flow of
objective, **credible** statistics to support
the decisions of individuals,
households, governments, businesses,
and other organizations."


## OMB

Statistical Policy Directive No. 1, 4:

"Any **loss of trust** in the
integrity of the Federal statistical system
and its products could lessen
respondent cooperation with Federal
statistical surveys, decrease the quality
of statistical system products, and foster
uncertainty about the validity of
measures our Nation uses to monitor
and assess its performance and progress."


## Agency efforts

::::{.columns}

:::{.column width="50%"}

[U.S. Census Bureau](https://www.census.gov/about/trust-and-safety.html)

:::

:::{.column width="40%"}

![U.S. Census Trust and Safety Center](images/census-trust-safety.png)

:::

::::

## Joint Statement

[Joint Statement on Commitment to Scientific Integrity and Transparency](https://www.census.gov/content/dam/Census/about/about-the-bureau/policies_and_notices/scientificintegrity/Scientific_Integrity_Statement_of_the_Principal_Statistical_Agencies.pdf)

- **Principle 2**: a Federal statistical agency must have credibility with those who use its data and information;
- **Principle 3**: a Federal statistical agency must have the trust of those whose information it obtains; 

## Waning trust

[Pew Research](https://www.pewresearch.org/politics/2022/06/06/2-public-views-about-the-federal-government/)

::::{.columns}

:::{.column width="50%"}

![Democrats on withholding data](images/pew-2024-withhold-democrat.png)

:::

:::{.column width="50%"}

![Republicans on withholding data](images/pew-2024-withhold-republican.png)

:::

::::

## Computational Reproducibility and Official Statistics

::::{.columns}

:::{.column width="50%"}

Agencies do provide **detailed information on sources**

- Surveys
- Administrative data

:::

:::{.column width="50%"}

![](images/image4-1.png)

:::

::::

## Computational Reproducibility and Official Statistics

::::{.columns}

:::{.column width="50%"}

But: **Availability of "computing instructions"**?

- *Code* for cleaning, aggregation, imputation
- Including for *disclosure avoidance*

:::

:::{.column width="50%"}

![](images/image4-2.png)

:::

::::

## Computational Reproducibility and Official Statistics

::::{.columns}

:::{.column width="50%"}

But: Availability of **reliable, trusted data archives**

- Of released data – for audience 1 & 2 – ability to reproduce downstream uses
- Of source data – for audience 2 – ability to reproduce released data

:::

:::{.column width="50%"}

![](images/image4-5.png)

:::

::::

## The analogy {transition="fade" transition-speed="fast"}

![](images/image4-5.png)

## The analogy {transition="fade" transition-speed="fast"}

![](images/image4-3.png)

## The analogy {transition="fade" transition-speed="fast"}

![](images/image4-4.png)


# Some principals from the academic world

Which are starting to be infused into the federal system

## FAIR Principles

::::{.columns}

:::{.column width="50%"}

FAIR:

- **F**indable
- **A**ccessible
- **I**nteroperable
- **R**eusable

:::

:::{.column width="50%"}

![](images/FAIR-data-principles.png)

:::

::::

## Data Citation Principles

::::{.columns}

:::{.column width="50%"}

![](images/force11-dc.png)

:::

:::{.column width="50%"}

To make it **findable**,

![](images/force11-dc-logo.jpg)

Data Citation Synthesis Group: Joint Declaration of Data Citation
Principles. Martone M. (ed.) San Diego CA: FORCE11; 2014
<https://www.force11.org/group/joint-declaration-data-citation-principles-final>

:::

::::

# An example from ERS

![](images/ers-rugged-cover-page.png) [^ERS-rugged]

[^ERS-rugged]: <https://ers.usda.gov/data-products/area-and-road-ruggedness-scales/>

## Website

![Website](images/ers-rugged-website.png)

## Sources

![High-level description of sources](images/ers-rugged-data-sources.png)

## Sources

![Sources are cited!](images/ers-rugged-data-citation.png)

## Methods

![High-level description of methods, but no (obvious) code](images/ers-rugged-methods.png)

## Methods

![Some methods - R code - is cited](images/ers-rugged-software-citations.png)

## Own citation?

![Own citation does not even include a URL](images/ers-rugged-citation.png)

## Findability?

::::{.columns}

:::{.column width="50%"}

![Data.gov is not great](images/data-gov-ruggedness.png)

:::

:::{.column width="50%"}

![In fact, ERS is not even on the list](images/data-gov-agencies.png)

:::

::::

## Findability?


::::{.columns}

:::{.column width="50%"}

![Google Dataset Search is worse](images/ers-rugged-google-dss.png)

:::

:::{.column width="50%"}

Not even close.

:::

::::

## Repeatability of downloads?

URL is 

**https://ers.usda.gov/webdocs/DataFiles/107356/RuggednessScale2010tracts.xlsx?v=6316.8**

- What will the 2020 tract-based data URL look like?

## Reproducibility?

- Most of the data inputs seem to be public data, or commercially available (ESRI)
- If the code were provided, others should be able to reproduce the analysis

