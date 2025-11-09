**Jean-Sébastien Marier**

**November 5, 2025**<br>
**MPAD2003A Introductory Data Storytelling (WKS) Fall 2025**<br>
**Amanda Kourtakos, Kennason Boudreault, Sean Halaby, Chimdalu Umeh**<br>
**Presented to Jean-Sébastien Marier**<br>


# Exploratory Data Analysis (EDA) & Pitch
## Ottawa’s Language Divide: How Geographic Location Influences Fields of Study

* [The template repository for this assignment in case you delete something by mistake](https://github.com/jsmarier/jou4100_jou4500_mpad2003_project2_template)

## 1. Introduction

The dataset presents the 2021 Canadian Census data for the city of Ottawa, organized by its 24 municipal wards. It includes a wide range of demographic and socio-economic variables such as age, gender distribution, family status, and education. For this analysis, our group is focusing on education, specifically comparing undergraduate degrees in STEM (science, technology, engineering, and mathematics) to those in Arts and Communications (humanities, social sciences, and media studies). We aim to explore how these two fields differ across Ottawa’s wards, as well as what these differences might reveal about local educational trends.

We used data from the City of Ottawa’s Open Data Portal, available here:

CVS file: <a href="https://raw.githubusercontent.com/jsmarier/files-for-course-assignments/refs/heads/main/2021_Long_Form_Census_-_Ward_Data.csv" target="_blank">CVS file of long-form census</a><br>

Original: <a href="https://open.ottawa.ca/datasets/ottawa::2021-long-form-census-ward-data/explore" target="_blank">Original long-form census link</a><br> 

The main sections of our report include: *Getting Data*, *Cleaning Data*, *Understanding Data (VIMO Analysis)*, *Exploratory Data Analysis*, *Potential Story*, and *Conclusion*.

## 2. Getting Data

We began by downloading a CSV copy of the 2021 Long Form Census – Ward Data from the Ottawa Open Data portal. To make it easier to analyze, we imported it into Google Sheets by selecting File → Import → Upload → Insert new sheet → Import data.

The dataset contained 2,602 rows and 26 columns, with each row representing a demographic indicator (e.g., total population, average income, or education level) and each column representing a geographic area (the city total plus 24 wards such as Kanata North, Stittsville, and Rideau-Rockcliffe).

At first glance, the dataset was extensive and required significant scrolling and filtering. Some column headers were long (e.g., “Total - Knowledge of official languages - English and French”), making them harder to interpret. While most data consisted of numerical counts and percentages, a few cells contained missing or zero values, possibly due to rounding or privacy restrictions. Despite this, the data is still credible and reliable, providing detailed information about Ottawa’s population.



![](Raw_data.png)<br>
*Figure 1: Screenshot of the raw dataset after importation.*

 Raw Google Sheet link: <a href="https://docs.google.com/spreadsheets/d/1Et5na0iqNPqnuylpLyU0DKL2hpSekxjYrOdPQDwxh68/edit?gid=256964509#gid=256964509" target="_blank">Original Google Sheet</a><br> 

### Specific Observations

- **Kanata North (Ward 4):** Leads in residents pursuing STEM fields (~25,220 individuals), aligning with its strong tech industry (Discover Technata, n.d.).  
- **Stittsville (Ward 6):** Shows 11,135 individuals pursuing STEM or technical studies, likely due to proximity to Kanata’s technology corridor (Ottawa Community Voice, n.d.).  
- **Somerset (Ward 14):** Features higher proportions of residents with university degrees, typical of downtown areas near universities and government offices (Statistics Canada, 2021).

### Hypothesis

We hypothesize that **where a person grows up in Ottawa influences their educational choices**. Specifically, western wards are expected to show higher STEM concentrations, while central wards lean toward Arts and Communications.


**Here are examples of functions and lines of code put in grey boxes:**

1. If you name a function, put it between "angled" quotation marks like this: `IMPORTHTML`.
1. If you want to include the entire line of code, do the same thing, albeit with your entire code: `=IMPORTHTML("https://en.wikipedia.org/wiki/China"; "table", 5)`.
1. Alternatively, you can put your code in an independent box using the template below:

``` r
=IMPORTHTML("https://en.wikipedia.org/wiki/China"; "table", 5)
```
This also shows how to create an ordered list. Simply put `1.` before each item.

## 3. Understanding Data

### 3.1. VIMO Analysis
Use three hashtag symbols (`###`) to create a level 3 heading like this one. Please follow this template when it comes to level 1 and level 2 headings. However, you can use level 3 headings as you see fit.

Insert text here.


Understanding Data 
VIMO Analysis

Before concluding our dataset, we conducted a VIMO analysis, an assessment of Valid, Invalid, Missing, and Outlier data to ensure that our findings were reliable and accurately represented Ottawa’s population. The dataset is based on the 2021 Census of Population, specifically the long-form census, which surveys about 25% of residents. Although it is a sample, it remains highly credible and representative of the city’s demographic and educational landscape.

Valid data refers to whether the information accurately measures what it intends to. In this case, the dataset captures educational fields across Ottawa’s wards, focusing on STEM and Arts degrees. Because the data comes from the long-form census, which provides detailed information on education levels and fields of study, it is a valid source for understanding how education varies geographically. For example, higher STEM concentrations in Kanata North align with that area’s population of professionals working in science and technology, confirming the data’s validity.

Invalid data involves possible misclassifications or interpretive errors. To reduce this, we established clear definitions: STEM fields include sciences, engineering, math, and technology, while Arts and Communications include humanities, visual arts, and social sciences. These consistent groupings helped prevent bias and ensured accurate comparisons between wards.

Missing data was minimal, with only small gaps due to rounding or confidentiality. We treated blank or zero values as very low counts rather than absences, confirming that the dataset remained complete and consistent enough for analysis.

Outliers such as Kanata North’s high STEM rates or Somerset’s high Arts concentrations were not errors but reflections of real social and educational trends. These outliers helped reveal patterns showing how different communities foster different types of learning and career interests.

Together, this VIMO process confirmed that our dataset is credible and representative, allowing us to confidently explore our story: where you grow up can influence what you choose to study or pursue in life. The data showed that residents of Ottawa’s western wards (such as Kanata and Stittsville) are more likely to hold STEM degrees. In contrast, residents of central wards (such as Capital and Rideau-Vanier) are more likely to hold Arts and Communication degrees. This pattern reflects how community values, local schools, and neighborhood environments shape people’s educational and career paths, something we also recognized through our own personal experiences growing up in different areas of the city.



Support your claims by citing relevant sources. Please follow [APA guidelines for in-text citations](https://apastyle.apa.org/style-grammar-guidelines/citations).

**For example:**

As Cairo (2016) argues, a data visualization should be truthful...

### 3.2. Cleaning Data

Insert text here.

### 3.3. Exploratory Data Analysis (EDA)

Insert text here.

**This section should include a screen capture of your pivot table, like so:**

![](pivot-table-screen-capture.png)<br>
*Figure 2: This pivot table shows...*

**This section should also include a screen capture of your exploratory chart, like so:**

![](chart-screen-capture.png)<br>
*Figure 3: This exploratory chart shows...*

## 4. Potential Story

Insert text here.

## 5. Conclusion

Insert text here.

## 6. References

Include a list of your references here. Please follow [APA guidelines for references](https://apastyle.apa.org/style-grammar-guidelines/references). Hanging paragraphs aren't required though.

**Here's an example:**

Bounegru, L., & Gray, J. (Eds.). (2021). *The Data Journalism Handbook 2: Towards A Critical Data Practice*. Amsterdam University Press. [https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153](https://ocul-crl.primo.exlibrisgroup.com/permalink/01OCUL_CRL/hgdufh/alma991022890087305153)
