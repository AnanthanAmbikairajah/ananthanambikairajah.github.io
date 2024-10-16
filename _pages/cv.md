---
title: "CV"
author: "Dr Ananthan Ambikairajah"
fontawesome: yes
output:
  pdf_document:
    latex_engine: pdflatex
    template: rap-latex-cv.tex
  word_document: default
fontfamilyoptions: sc, osf
fontsize: 10pt
geometry: margin=1in
jobtitle: Neuroscientist. Educator. Science Communicator.
linkcolor: blue
nocite: '@*'
fontfamily: mathpazo
email: ananthan.ambikairajah@canberra.edu.au
urlcolor: blue
web: ananthanambikairajah.com
header-includes:
- \usepackage{censor}
---
```{r include=FALSE}

# Publications
date <- "27th September, 2024"
number_of_papers <- 14
number_of_first_authored_papers <- 9
google_scholar_number_of_citations <- 502
google_scholar_h_index <- 8

scival_stats_years <- "2019 to 2024"
scival_fat_mass_meta_analyses_FWCI <- 6.64
scival_average_FWCI <- 2.2
number_of_publications_in_top_10_percent_most_cited_publications_worldwide_citescore <- 36.4
Q1_publications_citescore <- 81.8
Q1_Q2_publications_citescore <- 100

# Professional experience in presenting/communication
number_of_podcast_episodes <- 55
number_of_podcast_plays <- 7374

# Service to research - peer review
number_of_peer_reviewed_articles <- 25
total_number_of_peer_reviews <- 36

number_of_BMJ_peer_reviews <- 7
BMJ_quartile <- "Q1"
BMJ_ranking_in_general_medicine <- "15/329"

number_of_Neuroscience_and_Biobehavioural_Reviews <- 1
Neuroscience_and_Biobehavioural_Reviews_quartile <- "Q1"
Neuroscience_and_Biobehavioural_Reviews_ranking_cognitive_neuroscience <- "3/115"

web_of_sciencepeer_review_to_publication_ratio <- "2.5:1"

number_of_honours_theses_reviewed_2021 <- 3
number_of_honours_theses_reviewed_2022 <- 4
number_of_honours_theses_reviewed_2023 <- 4

# GenAI
number_of_FoH_GENAI_CoP_members <- 51
```

# CAREER OBJECTIVE
My career objective is to work in an intellectually challenging environment that combines my passion for research, teaching and science communication, as well as enriched opportunities to be a lifelong learner.

# MISSION STATEMENT

I am determined and committed to: 

* Conduct high quality research investigating genetic, environmental and lifestyle factors which influence ageing, brain health and disease, with a particular focus on sex-specific determinants, cardiometabolic factors and the potential for risk reduction in dementia.
* Enhance student motivation and engagement to promote positive learning experiences and outcomes which foster a love of learning and facilitates a journey of personal growth and self-discovery.
* Communicate science with a focus on making it accessible, understandable and interesting, which can spark public engagement, facilitate critical thinking and encourage respectful discourse. 
* Integrate principles of openness and a data-centred approach, leveraging tools and technology, including R, git, Linux and Generative Artificial Intelligence (GenAI), to enhance the capabilities, efficiency and impact of teaching, research and service.  

# EDUCATION

**Doctor of Philosophy (PhD)** \hfill 2018 to 2022

*Australian National University - Research School of Population Health*

  > [Thesis - Women's brain health: disentangling the role of menopause and ageing](https://ananthanambikairajah.com/files/Thesis%20Material%20-%20Ananthan_Ambikairajah_PhD_Thesis.pdf)

**Master of Teaching (Secondary) Science Double Method Specialisation** \hfill 2016 to 2017

*University of New South Wales - School of Education*

 > Weighted Average Mark: 85.78 (High Distinction Average)

**Bachelor of Science (Neuroscience)** \hfill 2012 to 2015

*University of New South Wales - School of Medical Science*

 > Weighted Average Mark: 75.81 (Distinction Average)

# EMPLOYMENT

**Lecturer** \hfill 2021 to date

*University of Canberra - Faculty of Health, Discipline of Psychology*

# OTHER CURRENT ROLES AND AFFILIATIONS

**Centre for Ageing Research and Translation (CARAT) Core Member** \hfill 2024 to date

*University of Canberra*

**Chair of Faculty of Health Generative Artificial Intelligence Community of Practice** \hfill 2023 to date

*University of Canberra - Faculty of Health*

**Review Editor** \hfill 2023 to date

*Frontiers in Aging Neuroscience - Alzheimer's Disease and Related Dementias*

**Fellow (FHEA)** \hfill 2023 to date

*Advance Higher Education*

**Visiting Fellow** \hfill 2022 to date

*Australian National University - College of Health and Medicine*

**Teacher and Developer - Software, Data and Library Carpentry** \hfill 2020 to date

*The Carpentries*

**Podcast Presenter** \hfill 2018 to date

*[Midnight Conversations](https://open.spotify.com/show/4SwmOkuSjlXLTzfMkjcPRh?si=06eb73c1063c4519)*
 
# PUBLICATIONS

My PhD was awarded and conferred on the 14th of July, 2022. As of `r date`, I have published `r number_of_papers` papers (`r number_of_first_authored_papers` first authored), which have been cited `r google_scholar_number_of_citations` times (H-index `r google_scholar_h_index`, Google Scholar), one of which with a FWCI of `r scival_fat_mass_meta_analyses_FWCI` (average `r scival_average_FWCI`, `r number_of_publications_in_top_10_percent_most_cited_publications_worldwide_citescore`% of publications in top 10% most cited publications worldwide, `r Q1_publications_citescore`% Q1, `r Q1_Q2_publications_citescore`% Q1/Q2, from `r scival_stats_years`, SciVal). 

```{r, echo=FALSE}
my_counter_publications <- 0
```

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. Alateeq, K., Walsh, E.I., **Ambikairajah, A.** & Cherbuin, N. (2024). Association between dietary magnesium intake, inflammation, and neurodegeneration. *European Journal of Nutrition*, 1-12 [doi: https://doi.org/10.1007/s00394-024-03383-1](https://doi.org/10.1007/s00394-024-03383-1)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. **Ambikairajah, A.**, Khondoker, M., Morris, E., de Lange, A. M. G., Saleh, R. N. M., Minihane, A. M.,& Hornberger, M. (2024). Investigating the synergistic effects of hormone replacement therapy, apolipoprotein E and age on brain health in the UK Biobank. *Human Brain Mapping*, *45*(2), e26612. [doi: https://doi.org/10.1002/hbm.26612](https://doi.org/10.1002/hbm.26612)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. Cherbuin, N.; Patel, H.; Walsh, E.I.; **Ambikairajah, A.**; Burns, R.; Brüstle, A. & Rasmussen, L.J. (2024). Cognitive Function Is Associated with the Genetically Determined Efficiency of DNA Repair Mechanisms. *Genes*, *15*, 153. [doi: https://doi.org/10.3389/fgwh.2023.1320640](https://doi.org/10.3390/genes15020153)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. Schindler, L. S., Subramaniapillai, S., **Ambikairajah, A.**, Barth, C., Crestol, A., Voldsbekk, I., Beck, D., Gurholt, T. P., Topiwala, A., Suri, S., Ebmeier, K. P., Andreassen, O. A., Draganski, B., Westlye, L. T., & de Lange, A. M. G. (2023). Cardiometabolic health across menopausal years is linked to white matter hyperintensities up to a decade later. *Frontiers in Global Women's Health*, *4*, 1320640.[doi: 10.3389/fgwh.2023.1320640](https://doi.org/10.3389/fgwh.2023.1320640)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. Namsrai, T., **Ambikairajah, A.** & Cherbuin, N. (2023). Poorer sleep impairs brain health at midlife. *Scientific Reports*, *13*(1), 1-10. [doi:10.1038/s41598-023-27913-9](https://doi.org/10.1038/s41598-023-27913-9)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. **Ambikairajah, A.**, Walsh, E.I., & Cherbuin, N. (2022). A review of menopause nomenclature. *Reproductive Health*, *19*(1), 1-15. [doi:10.1186/s12978-022-01336-7](https://doi.org/10.1186/s12978-022-01336-7)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. **Ambikairajah, A.**, Tabatabaei-Jafari, H., Hornberger, M., & Cherbuin, N. (2021). Age, menstruation history, and the brain. *Menopause*, *28*(2), 167-174. [doi:10.1097/GME.0000000000001688](https://doi.org/10.1097/GME.0000000000001688)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. **Ambikairajah, A.**, Ambikairajah, R., & Ambikairajah, E. (2021). The impact of improving feelings of relatedness on motivation and engagement for tertiary students. *International Journal of Mathematical Education in Science and Technology*, *52*(5), 721-730. [doi:10.1080/0020739X.2019.1703149](https://doi.org/10.1080/0020739X.2019.1703149)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. **Ambikairajah, A.**, Tabatabaei-Jafari, H., Walsh, E., Hornberger, M., & Cherbuin, N. (2020). Longitudinal changes in fat mass and the hippocampus. *Obesity*, *28*(7), 1263-1269. [doi:10.1002/oby.22819](https://onlinelibrary.wiley.com/doi/abs/10.1002/oby.22819)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. **Ambikairajah, A.**, Walsh, E., & Cherbuin, N. (2019). Lipid profile differences during menopause: a review with meta-analysis. *Menopause*, *26*(11), 1327-1333. [doi:10.1097/GME.0000000000001403](https://doi.org/10.1097/GME.0000000000001403)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. **Ambikairajah, A.**, Walsh, E., Tabatabaei-Jafari, H., & Cherbuin, N. (2019). Fat mass changes during menopause: a metaanalysis. *American Journal of Obstetrics & Gynecology*, *221*(5), 393-409. [doi:10.1016/j.ajog.2019.04.023](https://doi.org/10.1016/j.ajog.2019.04.023)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. **Ambikairajah, A.**, & Tisdell, C. C. (2019). E-Examinations and the Student Experience Regarding Appropriateness of Assessment and Course Quality in Science and Medical Science. *Journal of Educational Technology Systems*, *47*(4), 460-478. [doi:10.1177/0047239518822016](https://doi.org/10.1177/0047239518822016)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. Low, J. K., **Ambikairajah, A.**, Shang, K., Brown, D. A., Tsai, V. W., Breit, S. N., & Karl, T. (2017). First behavioural characterisation of a knockout mouse model for the transforming growth factor (TGF)-$\beta$ superfamily cytokine, MIC-1/GDF15. *PloS one*, *12*(1), e0168416. [doi:10.1371/journal.pone.0168416](https://doi.org/10.1371/journal.pone.0168416)

`r my_counter_publications<-my_counter_publications+1; my_counter_publications`. **Ambikairajah, A.,** Devenney, E., Flanagan, E., Yew, B., Mioshi, E., Kiernan, M. C., Hodges, J. R., & Hornberger, M. (2014). A visual MRI atrophy rating scale for the amyotrophic lateral sclerosis-frontotemporal dementia continuum. *Amyotrophic Lateral Sclerosis and Frontotemporal Degeneration*, *15*(3-4), 226-234. [doi:10.3109/21678421.2014.880180](https://doi.org/10.3109/21678421.2014.880180)

# CONFERENCE ORAL PRESENTATIONS

## INTERNATIONAL

```{r, echo=FALSE}
my_counter_international_presentations <- 0
```

`r my_counter_international_presentations<-my_counter_international_presentations+1; my_counter_international_presentations`. **Ambikairajah A.**, Tisdell C. (2020). Algorithms and software - Using Maple in humanities related assessment: Exploring beyond mathematical boundaries in education. Presentation accepted for the *Maple Conference*, Online.


`r my_counter_international_presentations<-my_counter_international_presentations+1; my_counter_international_presentations`. **Ambikairajah A.**, Tisdell C. (2018). The Effects of E-Examinations on Student Satisfaction Regarding Appropriateness of Assessment and Course Quality in Science and Medical Science. Presentation accepted for the *International Mobile Learning Festival*, Mobile Learning, STEM and Transdisciplinary Education, Singapore. 

## NATIONAL

```{r, echo=FALSE}
my_counter_national_presentations <- 0
```

`r my_counter_national_presentations<-my_counter_national_presentations+1; my_counter_national_presentations`. **Ambikairajah A.**, Khondoker M., Morris E., de Lange  A., Saleh R., Minihane A., Hornberger M. (2024). Investigating the Synergistic Effects of Hormone Replacement Therapy, APOE and Age on Brain Health. Presentation accepted for the *Canberra Health Annual Research Meeting (CHARM)*, University of Canberra 

`r my_counter_national_presentations<-my_counter_national_presentations+1; my_counter_national_presentations`. **Ambikairajah A.** (2024). Faculty of Health Generative Artificial Intelligence: Exploring usage, needs and expertise. Invited speaker for the *Faculty of Health Learning and Teaching Symposium*, University of Canberra. 

`r my_counter_national_presentations<-my_counter_national_presentations+1; my_counter_national_presentations`. **Ambikairajah A.**, Khondoker M., Morris E., de Lange  A., Saleh R., Minihane A., Hornberger M. (2023). Investigating the Synergistic Effects of Hormone Replacement Therapy, APOE and Age on Brain Health. Presentation accepted for the *21st National Conference of Emerging Researchers in Ageing*, Online. 

`r my_counter_national_presentations<-my_counter_national_presentations+1; my_counter_national_presentations`. **Ambikairajah A.**(2023). Genetics, hormones and brain health - the curious case of the null result. Ask the ERA Brains Trust Presentation accepted for the *21st National Conference of Emerging Researchers in Ageing*, Online. 

`r my_counter_national_presentations<-my_counter_national_presentations+1; my_counter_national_presentations`. **Ambikairajah A.** (2018). Being Courageous: Exploring new approaches to improve and expand learning experiences - A Practical Framework for Courageousness in Teaching. Presentation accepted for the *Learning and Teaching Forum, Partners in Learning: Connecting Communities*, University of New South Wales, Australia.

`r my_counter_national_presentations<-my_counter_national_presentations+1; my_counter_national_presentations`. **Ambikairajah A.** (2018). Being Courageous: Exploring new approaches to improve and expand learning experiences - A Practical Framework for Courageousness in Teaching. Presentation accepted for the *Learning and Teaching Forum, Partners in Learning: Connecting Communities*, University of New South Wales, Australia.

`r my_counter_national_presentations<-my_counter_national_presentations+1; my_counter_national_presentations`. **Ambikairajah A.** (2017). Inspired Learning by Inspired Teaching - Quality student relationships can predict excellence in leaning and teaching. Presentation accepted for the *Learning and Teaching Forum, Educational Excellence: Transforming Futures*, University of New South Wales, Australia. 


# CONFERENCE ABSTRACT AND POSTER PUBLICATIONS

```{r, echo=FALSE}
my_counter_international_abstractposter <- 0
```

## INTERNATIONAL

`r my_counter_international_abstractposter<-my_counter_international_abstractposter+1; my_counter_international_abstractposter`. Schindler L., Subramaniapillai S., **Ambikairajah  A.**, Barth  C., Voldsbekk  I., Beck  D., Gurholt  T., Topiwala  A., Suri  S., Ebmeier  K., Draganski  B., Andreassen  O., Westlye  L., de Lange  A. (2023). Body Composition Changes Across The Menopause Transition And Their Association With White Matter Hyperintensities: A Longitudinal Study. Abstract and poster accepted for the *48th Annual Conference Psychologie & Gehirn*, University of Tübingen, Germany. 

`r my_counter_international_abstractposter<-my_counter_international_abstractposter+1; my_counter_international_abstractposter`. Cherbuin N., Namsrai T., **Ambikairajah A.** (2022). Good sleep, healthy brain, and sharp mind all dream together. Abstract and poster accepted for the *28th Annual Meeting of the Organisation for Human Brain Mapping*, OHBM, Scotland. 

## NATIONAL

```{r, echo=FALSE}
my_counter_national_abstractposter <- 0
```

`r my_counter_national_abstractposter<-my_counter_national_abstractposter+1; my_counter_national_abstractposter`. Isbel S., Gibson D., D'Cunha N., Dawda P., Kosari S., Pearce C., Fearon A., Sabeti F., Hewitt J., Kellett J., Naunton M., Southwood H., Logan P., Subramanian R., Chadborn N., Davey R., Bail K., Goss J., **Ambikairajah A.**, Lincoln M., Wiseman L. (2025). Enhancing allied health services to people in residential aged care; The EAHOP trial. Abstract accepted for the Australian Association of Gerontology *The 57th AAG Conference*, Tasmania, Australia.

`r my_counter_national_abstractposter<-my_counter_national_abstractposter+1; my_counter_national_abstractposter`. Isbel S., Gibson D., D'Cunha N., Dawda P., Kosari S., Pearce C., Fearon A., Sabeti F., Hewitt J., Kellett J., Naunton M., Southwood H., Logan P., Subramanian R., Chadborn N., Davey R., Bail K., Goss J., **Ambikairajah A.**, Lincoln M., Wiseman L. (2025). A protocol for an allied health service intervention for people with dementia in residential aged care. Poster accepted for the Australian Association of Gerontology *The 57th AAG Conference*, Tasmania, Australia.

`r my_counter_national_abstractposter<-my_counter_national_abstractposter+1; my_counter_national_abstractposter`. Pike A., Cherbuin N., **Ambikairajah A.**, Lawlis N., Rattray B., Northey J. (2024). Physical activity intensities, cognition and brain volumes in men with prostate cancer. Abstract and poster accepted for the *Clinical Oncology of Australia Annual Scientific Meeting*, Queensland, Australia

`r my_counter_national_abstractposter<-my_counter_national_abstractposter+1; my_counter_national_abstractposter`. **Ambikairajah A.**, Tisdell C. (2016). Changing how we think about teaching - A reflection of the Pilot Active Learning Spaces (PALS) initiative. Abstract accepted for the *Learning and Teaching Forum, Towards 2025: Inspiring Learning*, University of New South Wales, Australia.


# STUDENT SUPERVISION

## PHD

```{r, echo=FALSE}
my_counter_phd_students <- 0
```

`r my_counter_phd_students<-my_counter_phd_students+1; my_counter_phd_students`. \censor{**Tergel Namsrai**} - Associate supervisor \hfill 2022 to date 

$\quad \quad$ *Australian National University*

`r my_counter_phd_students<-my_counter_phd_students+1; my_counter_phd_students`. \censor{**Tianqi Zhang**} - Associate Supervisor \hfill 2021 to date

$\quad \quad$ *Australian National University*

## MASTERS

```{r, echo=FALSE}
my_counter_masters_students <- 0
```

`r my_counter_masters_students<-my_counter_masters_students+1; my_counter_masters_students`. \censor{**Tergel Namsrai**} - Co-supervisor \hfill 2020

$\quad \quad$ *Australian National University*

>> Thesis mark: 80; Final Grade Point Average: 6.69 (Distinction)

## HONOURS

```{r, echo=FALSE}
my_counter_honours_students <- 0
```

`r my_counter_honours_students<-my_counter_honours_students+1; my_counter_honours_students`. \censor{**Caleb Walk**} - Primary supervisor \hfill 2024

$\quad \quad$ *University of Canberra*

`r my_counter_honours_students<-my_counter_honours_students+1; my_counter_honours_students`. \censor{**Deahne Hurditch**} - Primary supervisor \hfill 2024

$\quad \quad$ *University of Canberra*

`r my_counter_honours_students<-my_counter_honours_students+1; my_counter_honours_students`. \censor{**Emily Clay**} - Primary supervisor \hfill 2024

$\quad \quad$ *University of Canberra*

`r my_counter_honours_students<-my_counter_honours_students+1; my_counter_honours_students`. \censor{**Sebastian Armstrong**} - Primary supervisor \hfill 2024

$\quad \quad$ *University of Canberra*

`r my_counter_honours_students<-my_counter_honours_students+1; my_counter_honours_students`. \censor{**Siena Montgomery**} - Primary supervisor \hfill 2023

$\quad \quad$ *University of Canberra*

>> Thesis Mark: 91; Final grade: 91 (High Distinction Honours I)

`r my_counter_honours_students<-my_counter_honours_students+1; my_counter_honours_students`. \censor{**Georgina Todd**} - Primary supervisor \hfill 2023

$\quad \quad$ *University of Canberra*

>> Thesis Mark: 78; Final grade: 78 (Distinction Honours IIa)

`r my_counter_honours_students<-my_counter_honours_students+1; my_counter_honours_students`. \censor{**Letetia Mackenzie**} - Primary supervisor \hfill 2022

$\quad \quad$ *University of Canberra*

>> Thesis Mark: 88; Final grade: 90 (High Distinction Honours I)

>> 2022 Australian Psychological Society Prize Winner

`r my_counter_honours_students<-my_counter_honours_students+1; my_counter_honours_students`. \censor{**Mateus Viana Dos Santos**} - Primary supervisor \hfill 2022

$\quad \quad$ *University of Canberra*

>> Thesis Mark: 72; Final grade: 78 (Distinction Honours IIa)

`r my_counter_honours_students<-my_counter_honours_students+1; my_counter_honours_students`. \censor{**Tarun Sharma**} - Primary supervisor \hfill 2022

$\quad \quad$ *University of Canberra*

>> Thesis Mark: 70; Final grade: 73 (Credit Honours IIb)

# GRANTS AND AWARDS

I am the recipient of 3 competitive seed/project grant funding awards totalling \$`r sprintf("%.0f", (6000 + 14997 + 10000))`, 3 scholarships, including an AGRTP scholarship totalling \$`r sprintf("%.0f", (83946 + 13991))` and 2 others totalling \$`r sprintf("%.0f", (2000 + 500))`, 3 research presentation awards totalling \$`r sprintf("%.0f", (250 + 250 + 500))`, in addition to awards for excellence in teaching and academics totalling \$`r sprintf("%.0f", (1000))`.

**UC ReD IGNITE Program** \hfill 2024 - 2025

*University of Canberra*

I was accepted for the highly competitive UC ReD IGNITE (University of Canberra Researcher Development: Instilling Growth and Nurturing Innovation through Training and Education) Program, which includes a $10,000 research grant to support my research program, in addition to formal mentorship and research training.

**Outstanding New Researcher Highly Commended Award** \hfill 2024

*Canberra Health Annual Research Meeting (CHARM)*

I received the [Outstanding New Researcher Highly Commended Award](https://www.act.gov.au/health/conducting-health-research/charm/charm-2024) from the ACT Minister for Health. This was part of the CHARM Rising Star Awards which aimed to recognise and showcase the achievements of developing Canberra health researchers and contribute to a positive research culture which supports and acknowledges progress and development in research capacity and capability.

**Rapid Fire Research Presentation Award** \hfill 2024

*University of Canberra - Faculty of Health*

I was awarded $500 (1st place) for my research presentation titled "Genetics, hormones and brain health, the curious case of the null result".

**Faculty of Health Seed Grant** \hfill 2024

*Univerity of Canberra - Faculty of Health*

I am co-investigator B on a Faculty of Health seed grant (totalling $14,997) led by Chief Investigator Associate Professor Aisling (Ash) Smyth titled "The feasibility, acceptability and effectiveness of a pressure-injury prevention system (PIPS) in Residential Aged Care." *Smyth, A., Bail, K., Ambikairajah, A. & McGuirk, D.*

**Award for Excellence in Teaching - Student Award** \hfill 2023

*University of Canberra - Faculty of Health*

I received an award for excellence in teaching, which was a student nominated award. This award included $1000 and recognises individuals who have excelled in their teaching and who have made outstanding contributions to learning and teaching at the University of Canberra.

**Nomination for Early Career Researcher Award** \hfill 2023

*University of Canberra - Faculty of Health*

I received a nomination for the Early Career Researcher Award, which is awarded to an individual early career researcher who has developed a purposeful and coherent research portfolio since their PhD and whose research has achieved impact. The award recognises individuals who have shown outstanding performance in research relative to opportunity.

**Project Funds** \hfill 2023 to 2024

*University of Canberra - Faculty of Health*

I was successful in receiving $6,000 of funding from the Faculty of Health to cover the cost of a 1 year extension to access the UK Biobank dataset for the completion of an existing research project.

**Best ERA 2023 Oral Presentation by a member of the Australian Association of Gerontology** \hfill 2023

*21st National Conference of Emerging Researchers in Ageing*

I was awarded a prize to the value of $250 and a certificate as my conference presentation was considered by the judging panel to be the best oral presentation by a member of the Australian Association of Gerontology at the 21st National Conference of Emerging Researchers in Ageing. 

**Rapid Fire Research Presentation Award** \hfill 2023

*University of Canberra - Faculty of Health*

I was awarded $250 (3rd place) for my research presentation titled "Genetics, hormones and brain health, the curious case of the null result".

**Commendation for Excellence in Teaching - Student Award** \hfill 2022

*University of Canberra - Faculty of Health*

I received a commendation for excellence in teaching, which was a student nominated award. This award recognises individuals who have excelled in their teaching and who have made outstanding contributions to learning and teaching at the University of Canberra.

**Excellence in Learning and Teaching Indigenising the Curriculum** \hfill 2022

*University of Canberra - Faculty of Health*

As part of the Discipline of Psychology Team, I contributed to the Indigenisation of the Psychology Curriculum through collaboration with colleagues and Indigenous Australians via a series of yarning circles.

**Nominated for the ANU Medical School Education Award for Excellence in Tutoring** \hfill 2020

*Australian National University*

Anonymous nomination comment: "Ananthan's vibrant and interactive tutoring style made it easy and fun to learn. He takes an active interest in students’ lives, teaches with humour and fosters open and non-judgemental discussion, encouraging learning for all. He made the content understandable and interesting, re-invigorating our interest in population health. He allowed us to self-direct our learning, facilitated our discussions, and created welcoming and enjoyable tutorials. This helped us to consolidate our knowledge and memories of our fun conversations helped immensely when recalling content throughout exams. He was an outstanding tutor, even throughout the difficulties of online learning, and we cannot recommend him enough for this award. His passion for teaching made learning a lot easier and interesting!"

**Complex Human Data Summer School Scholarship** \hfill 2019

*University of Melbourne*

The Complex Human Data Summer School (CHDSS) Scholarship was a one off payment, valued at $500, which covered the cost of travel and/or accomodation. Across 6 consecutive days, the CHDSS covered topics that included programming in R, reproducibility and open science, GitHub, bayesian data analysis, best practices for running online studies, experience sampling, probabilistic models of cognition, exploratory data analysis and generalised linear models. 

**Research to Impact Scholarship** \hfill 2018

*Canberra Innovation Network* 

The Research to Impact Scholarship was a one off payment, valued at $2,000, which covered the cost of 4 half-day workshops that covered areas such as (1) innovation essentials and finding market need, (2) Value propositions for big impact, (3) Business models, value chain and collaboration and (4) Pitching for outcomes and building your pitch-deck. In addition to this, the program involved intensive self-study before each workshop and a one on one follow up session.

**Australian Government Research Training Program Domestic Scholarship** \hfill 2018 to 2021

*Australian National University* 

The Australian Government Research Training Program (AGRTP) Domestic Scholarship was a fortnightly payment leading to a sum of $83,946, over 3 years, with an additional \$13,991 top up for 6 months. The AGRTP Fee-Offset Scholarship covers the full tuition fees for 3 years.

**Dean’s List for Academic Excellence** \hfill 2017

*University of New South Wales - Faculty of Arts and Social Sciences* 

The Dean’s List for Academic Excellence is awarded to students that have maintained a High Distinction Weighted Average Mark.  

# RESEARCH GROUP/LAB MEMBERSHIPS

**Centre for Ageing Research and Translation (CARAT) Core Member** \hfill 2024 to date

*University of Canberra*

**Brain Imaging Interest Group (BIIG)** \hfill 2024 to date

*University of Sydney - Faculty of Medicine and Health*

**FemiLab Associated Team Member** \hfill 2022 to 2024

*Lausanne University Hospital* 

**Head of Ambikairajah Lab** \hfill 2021 to date

*University of Canberra - Faculty of Health* 

**Ageing Research Group Core Member** \hfill 2021 to date

*University of Canberra*

**Australian Association of Gerontology Member** \hfill 2019 - 2020; 2022 to date

*Australian Association of Gerontology*

**NeuroIMaging and Brain Lab (NIMBL) Member** \hfill 2017 to date

*Australian National University - Centre for Research on Ageing, Health and Wellbeing*

**ForeFront - Frontier Member** \hfill 2012 to 2015; 2022 to date

*Neuroscience Research Australia*

# PROFESSIONAL EXPERIENCE IN RESEARCH

**Lecturer** \hfill 2021 to date

*The University of Canberra - Faculty of Health, Discipline of Psychology*

At the University of Canberra, I am employed as a Lecturer. In this role I am responsible for:

* Developing an active research program including seeking external funding, conducting research and publishing. 
* Supervising students' research projects at honours and postgraduate levels.

**Researcher for Burns Group** \hfill 2020

*Australian National University - Centre for Research on Ageing, Health and Wellbeing*

With Dr Richard Burns, my role was to work conduct a literature review for a consultancy report for *Exhale*, which focused on domains related to mental and physical health and wellbeing. In this role I was responsible for:

* Conducting a literature review on domains related to health and wellbeing.
* Writing a report that explained the findings of the review in a digestible and understandable way to a non-scientific audience. 

**Researcher for Cherbuin Group** \hfill 2017 to 2020

*Australian National University - Neuroimaging Brain Lab (NIMBL)*

With Professor Nicolas Cherbuin, my role was to work collaboratively with a team on a systematic review and meta-analysis. This project allowed me to develop fundamental research skills required by a first year PhD student, including:

* Collating papers through a systematic search of online databases.
* Conducting title, abstract and full text screening.
* Extracting and analysing data, using the statistical package, R. 

**Researcher for Tisdell Group** \hfill 2016

*University of New South Wales - Science Learning and Teaching Unit*

With Professor Chris Tisdell, my role was to conduct self-directed work on a pre-established education project, which investigated the effectiveness of electronic examinations on the student learning experience. This project led to a first-author paper publication. In this role, I was responsible for: 

* Analysing the data.
* Writing a manuscript for the research project.

**Research Volunteer for Piguet Group** \hfill 2014 to 2015

*Neuroscience Research Australia - Neurodegenerative Diseases*

My work with Professor Olivier Piguet enabled me to develop my research skills and knowledge of frontotemporal dementia (FTD). In this role, I worked with the Piguet Group on a number of research projects for my Bachelor of Science (Neuroscience) degree, which allowed me to:

* Conduct literature reviews and obtain quality feedback on my writing skills. 
* Engage in personalised meetings and develop from professional mentorship, which helped further my understanding of dementia research and brain imaging techniques, such as Voxel-Based Morphometry (VBM) and develop experience with the grant writing process.
* Work in a collaborative team environment, attend group meetings and contribute to academic discussions.
* Gain exposure in utilising a wide array of research techniques and statistical methods for analysis of behavioural and imaging data.

**Research Volunteer for Karl Group** \hfill 2013

*Neuroscience Research Australia - Mental Health*

With Professor Tim Karl, my role was to work collaboratively on a 3 month intensive animal research project, which investigated the role of MIC-1/GDF15 on behavioural domains of male and female knockout mice including locomotion, exploration, anxiety, cognition, social behaviours and sensorimotor gating. This project led to a paper publication. In this role, I was responsible for:

* Completing an animal care and ethics course at UNSW, which I obtained a mark of 94% (High Distinction).
* Appropriate, careful and safe handling and care of the mice, to ensure minimal pain and distress.
* Conducting behavioural research on mice including tests such as the elevated plus maze, open field test, continuous spontaneous alternation in the Y-maze, social interaction test, fear conditioning and the prepulse inhibition test. 
* Recording behavioural data from all experiments.
* Conducting formal analysis on the collected data, using the statistical software package, SPSS.

**Research Volunteer for Hornberger Group** \hfill 2012

*Neuroscience Research Australia - Neurodegenerative Diseases*

My work with Professor Michael Hornberger was initially intended to be a learning experience, however, due to my strong work ethic and eagerness to learn, I was encouraged to work on a research project, which investigated the use of a novel visual rating scale that would help clinicians reliably distinguish between ALS, ALS-FTD and bvFTD atrophy patterns on an MRI scan. This project led to a first-author paper publication. In this role, I was responsible for:

* Undertaking self-directed reading and reviewing of the literature. 
* Viewing coronal MRI scans and implementing the rating scale to assess different regions of the brain. 
* Collaborating with collaborators to analyse and interpret the results.
* Writing a manuscript for the research project.
* Working with research collaborators to address reviewer comments on the paper.

# PROFESSIONAL EXPERIENCE IN TEACHING (UNIVERSITY) 

**Lecturer** \hfill 2021 to date

*The University of Canberra - Faculty of Health, Discipline of Psychology*

At the University of Canberra, I am employed as a Lecturer. In this role I am responsible for:

* Coordinating and convening units and courses in Psychology and statistics.
* Designing, developing, delivering and coordinating innovative and engaging lectures, tutorials, laboratory classes and workshops as required. 
* Undertaking marking and the development of assessment materials at the undergraduate and postgraduate levels.

**Teacher and Developer - Software, Data and Library Carpentry** \hfill 2020 to date

*The Carpentries*

In this role, I am responsible for:

* Teaching R, shell, Git and software engineering skills to scientists and engineers at bootcamps and online sessions. 
* Developing new instructional content.
* Developing and maintaining The Carpentries GitHub repositories.

**Teacher and Coordinator - CRAHW R Statistics Workshops** \hfill 2019 to 2020

*Australian National University - Centre for Research on Ageing, Health and Wellbeing*

In this role, I was responsible for:

* Developing and delivering high quality, engaging workshops about linear/generalised linear models to PhD candidates and early career researchers. 
* Developing practice questions using R code.
* Administrative tasks necessary for the successful operations of the course. 

**Teacher - Statistics Workshops in R** \hfill 2019 to 2020

*Australian National University - Biological Data Science Institute*

In this role, I was responsible for:

* Developing and delivering high quality, engaging workshops about linear/generalised linear models, linear mixed models, model selection, graphing, R Markdown and GitHub to PhD candidates and early career researchers. 
* Designing the curriculum.

**Sessional Teacher - POPH8919: Life Course Approaches to Human Ageing** \hfill 2018 to 2020

*Australian National University - Research School of Population Health*

In this role, I was responsible for:

* Developing and delivering high quality, engaging lectures and tutorials to students.
* Designing assessment tasks. 
* Marking assessment tasks and providing prompt, valuable and insightful feedback.

**Sessional Teacher - 1st and 2nd year Doctor of Medicine and Surgery degree** \hfill 2018 to 2020

*Australian National University - Centre for Research on Ageing, Health and Wellbeing*

In this role, I was responsible for:

* Delivering high quality, engaging problem based learning tutorials to students.
* Teaching fundamental statistical concepts in an interesting, relevant and understandable way.

**Convenor and Sessional Science Teacher - ANUC1107: Logic and Critical Reasoning** \hfill 2017

*Australian National University College*

In this role, I was responsible for:

* Developing and delivering high quality, engaging lectures and tutorials to students.
* Designing and implementing assessment tasks, including assignments and final exam papers. 
* Marking assessment tasks and providing prompt, valuable and insightful feedback.
* Addressing student concerns and issues.

**Sessional Teacher - SCIF1121: Professional Perspective and Practice	** \hfill 2016 to 2017

*University of New South Wales - Science Learning and Teaching Unit *

I have been consistently rated highly by students on feedback questionnaires, including CATEI and MyExperience (reports available upon request), with an average score of 5.83 out of 6 for all assessment categories. In this role, I was responsible for:

* Delivering high quality, engaging tutorials to students.
* Implementing innovative teaching strategies to enhance student-learning experience. 
* Collaborating with faculty members, to shape the design of the course, based on student feedback.
* Addressing student concerns and issues. 
* Conducting analysis on teaching practices, which have led to conference presentations. 

**Casual Science Teacher - Biology** \hfill 2015 to 2016

*University of New South Wales Global*

In this role, I was responsible for:

* Delivering high quality, engaging tutorials to students.
* Conducting laboratory demonstrations.

# PROFESSIONAL EXPERIENCE IN TEACHING (HIGH SCHOOL) 

**Science Teacher (PE2 Placement - 9 Weeks)** \hfill 2016

*South Sydney High School*

At South Sydney High School, I taught a range of students (including Year 8, 10 and 12), from varying socioeconomic backgrounds. The diversity of learners provided me with an opportunity to 1) adapt my teaching style to match the students’ learning needs and 2) implement innovative teaching strategies to engage students in science. Two detailed reports of my performance on this placement are available, upon request. An overview of my contributions to the school include:

* Designing lesson plans and delivering high quality, engaging lessons. 
* Organising and developing an engineering workshop for Year 8 students.
* Contributing to the development of an action research project, which incorporated online quizzes and examinations for student assessment tasks and formative learning activities.
* Setting high behavioural expectations and implementing effective classroom management techniques and strategies to facilitate a productive learning environment for students. 
* Contributing to student mentoring programs.

**Science Teacher (PE1 Placement - 4 Weeks)** \hfill 2016

*Randwick Girls High School*

At Randwick Girls High School, I taught a Year 11 class and a special needs Year 8 class. A detailed report of my performance on this placement is available, upon request. An overview of my contributions to the school include:

* Designing lesson plans and delivering high quality, engaging lessons. 
* Implementing weekly quizzes, to enhance student feedback and learning.
* Incorporating differentiation into the classroom, to address the learning needs of students. 

**Sessional Science Teacher** \hfill 2014 to 2017

*Matrix Education*

At Matrix Education, I have primarily taught Biology for Year 12 students. I have helped students develop and implement effective learning strategies, which have enabled them to achieve success in their Higher School Certificate (HSC). In this role, I was responsible for: 

* Designing lesson plans and delivering high quality, engaging lessons. 
* Marking student quizzes, to provide detailed feedback.
* Consulting with the CEO on the operations and educational initiatives within the faculty of science. 

# PROFESSIONAL EXPERIENCE IN PRESENTING/COMMUNICATION

**Podcast Presenter** \hfill 2018 to date

*Midnight Conversations*

Midnight Conversations is a podcast that discusses published, peer-reviewed scientific papers in an understandable and engaging way. The primary aim of the podcast was to foster a public interest in current scientific research to promote public engagement and provide a forum for critical and productive scientific discourse. As of `r date`, Midnight Conversations has `r number_of_podcast_episodes` episodes which have accrued `r number_of_podcast_plays` plays. In this role I am responsible for:

* Discussing scientific papers in an interesting and understandable way by highlighting the relevance and importance of key findings.
* Editing the podcast.
* Managing the operations of social media channels for the podcast.

**Science Communicator** \hfill 2015

*Neuroscience Research Australia*

My neuroscience background, combined with my writing and presenting skills enabled me to be successfully employed as a science communicator at Neuroscience Research Australia (NeuRA). In this role, I was responsible for:

* Translating technical scientific research into easily digestible information for media organisations and the general public.
* Establishing strong professional relationships and openly communicating with various media outlets and journalists to promote research conducted at NeuRA.
* Writing media releases, magazine articles and blog posts to create public traction for research. 
* Creating engaging podcasts to enhance public interest in neuroscience research.
* Creating video content to explain key neuroscience research areas to the public. 
* Providing intensive training sessions for scientists, to help them explain their research to the public. 
* Writing quarterly board reports for relevant stakeholders.

**Marketing Director** \hfill 2014

*Warrane College’s The Big Picture Program*

The Big Picture Program is a 5 day camp, which helps students shape their professional and personal direction in life. Due to my passion for mentoring students and longstanding involvement as a volunteer for the program, I was asked to be the director of marketing in 2014. My contributions included:

* Identifying specific areas of weakness in the marketing strategies for the program, and creating a core team of expertise to specifically focus on and address these limitations. 
* Enhancing student outreach by speaking at a large number of schools across NSW and ACT. This initiative, in addition to other strategies, led to a three-fold increase in the number of enrollments from the previous year (i.e. from 20 to 60 students), which was the largest intake the program had experienced.
* Establishing strong professional connections with businesses, entrepreneurial companies and universities in NSW, to provide students with educational experiences including, guest lectures, engineering and science demonstrations and campus tours. 

**Science Student Ambassador** \hfill 2013 to 2016

*University of New South Wales - Faculty of Science*

As a science student ambassador, I was actively involved in outreach to high school and primary school students to stimulate engagement and interest in science. Due to my experience in presenting and public speaking, my responsibilities included:

* Teaching primary and high school students about science.
* Interviewing scientists for UNSW’s video content.
* Speaking at public events for the science faculty.
* Being outsourced as a presenter for the centralised university outreach division, which resulted in ad-hoc presenting roles and guest speaking invitations at public events, both on and off campus. 

**Radio Show Host for The Pod** \hfill 2013

*Arc at University of New South Wales*

The Pod was a campus radio show at UNSW. In this role I was responsible for:

* Creating engaging and entertaining podcasts for students.
* Writing interview questions and hosting the show. 
* Organising guests for the show, including Australian comedians such as Wil Anderson, Fiona O’Loughlin and Sammy J. 
* Editing the podcast. 
* Managing a volunteer base of students.

# SERVICE TO UNIVERISTY

**Faculty of Health Digital Health Working Group**  \hfill 2024 to date

In this role, I am responsible for contributing my GenAI knowledge and expertise to the Digital Health Working Group. 

*University of Canberra*

**Faculty of Health representative for the Performance Expectations for Academic Staff (PEAS) Working Group**  \hfill 2024 to date

In this role, I am responsible for representing the Faculty of Health in the revision of the Performance Expectations for Academic Staff. 

*University of Canberra*

**Chair of Faculty of Health Generative Artificial Intelligence Community of Practice**  \hfill 2024 to date

In this role, I am responsible for leading the Faculty of Health in upskilling staff and students on GenAI to enhance their learning, teaching, research and professional practice, in addition to producing future ready graduates and tertiary educators. Some milestone achievements include:

* Establishing the terms of reference, which lists the objectives and proposed activities for the group to progress this year.
* Population of Teams site with resources and discussions.
* Growth of group to `r number_of_FoH_GENAI_CoP_members` staff members.
* Collaborative partnership with University of Technology Sydney (UTS) GenAI ENHANCE Community of Practice (CoP), including its chair, Professor Bronwyn Hemsley. Other partnerships include Alex Steel from UNSW who is the Director of AI Strategy Education and Susie Macfarlane who chairs the GenAI CoP at Deakin University.
* Coffee catch up sessions, which have provided a forum for discussion about GenAI amongst CoP members.
* Development and implementation of a survey of Faculty of Health Staff (May/June, 2024) to understand the current usage, needs and expertise related to GenAI. This has helped identify how GenAI is being integrated into learning, teaching, research and professional practice and understand how we can develop the GenAI expertise of the Faculty. This survey was completed by 71 staff members (approximately 25% response rate)
* Organising the GenAI session at the Faculty of Health Learning and Teaching Symposium (June, 2024), which included presentations from Professor Bronwyn Hemsley, Professor Alex Steel and myself, in addition to a panel discussion regarding GenAI. My presentation at this forum discussed how GenAI models work and shared the results from a survey of FoH staff which investigated the usage, needs and expertise relating to GenAI
* Invited as a guest speaker to the UTS GenAI ENHANCE CoP in July, 2024.
* Developed and taught a 4-hour workshop in October for FoH staff to help upskill staff regarding GenAI in teaching and assessment. The workshop was attended by academics across all disciplines, institutes and centres within the Faculty of Health and by academics from all levels (A to E). 
* Invited as a guest speaker to the Tertiary Counsellors Meeting at UC Medical and Counselling in September, 2024.
* Organised a GenAI session in November, 2024, which included a presentation from Susie Macfarlane to discuss Deakin University's approach and principles for the use of AI and examples of best practice for AI use in learning and teaching. 

*University of Canberra - Faculty of Health*

**Manager of University of Canberra Chess Club on Chess.com**  \hfill 2023 to date

*Chess.com*

**Faculty of Health Running Club**  \hfill 2023 to date

*University of Canberra - Faculty of Health*

**Coordinator for NeuroIMaging and Brain Lab (NIMBL) Meetings** \hfill 2018 to 2020

*Australian National University - Centre for Research on Ageing, Health and Wellbeing*

## COMMITTEES

**Faculty of Health Education Committee** \hfill 2023 to 2025

*University of Canberra - Faculty of Health*

**Courses and Units Sub-Committee (CUSC)** \hfill 2022 to 2023

*University of Canberra - Faculty of Health*

**IARU Research Meeting - Organising Committee Member** \hfill 2019

*International Alliance of Research Universities*

**RSPH Strategic Plan - Beneficiaries Working Group Member** \hfill 2019

*Australian National University - Research School of Population Health*

**Postgraduate Research Student Committee - Deputy Chair** \hfill 2019

*Australian National University - Research School of Population Health*

**Postgraduate Research Student Committee - Student Representative** \hfill 2018

*Australian National University - Research School of Population Health*

**Learning and Teaching Committee - Postgraduate Student Representative** \hfill 2016 to 2017

*University of New South Wales*

**Student Representative for PHAR3202: Neuropharmacology** \hfill 2014

*University of New South Wales*

# SERVICE TO RESEARCH

## PEER REVIEW
I have peer reviewed `r number_of_peer_reviewed_articles` research articles (totalling `r total_number_of_peer_reviews` peer reviews). Of those, `r number_of_BMJ_peer_reviews` reviews were for the
British Medical Journal (BMJ - `r BMJ_quartile`, ranked `r BMJ_ranking_in_general_medicine` in general medicine) and `r number_of_Neuroscience_and_Biobehavioural_Reviews` was for
Neuroscience and Biobehavioural Reviews (`r Neuroscience_and_Biobehavioural_Reviews_quartile`, ranked `r Neuroscience_and_Biobehavioural_Reviews_ranking_cognitive_neuroscience` in Cognitive Neuroscience). My peer review to publication ratio is `r web_of_sciencepeer_review_to_publication_ratio` (Web of Science). I have also reviewed `r number_of_honours_theses_reviewed_2021 + number_of_honours_theses_reviewed_2022 + number_of_honours_theses_reviewed_2023` honours theses since working as a Lecturer in 2021.

**Review Editor** \hfill 2023 to date

*Frontiers in Aging Neuroscience - Alzheimer's Disease and Related Dementias*

**Judge - Rapid Fire Research** \hfill 2024

*Canberra Health Annual Research Meeting (CHARM)*

**Reviewer for Education Conference Support Funding** \hfill 2024

*University of Canberra - Faculty of Health*

# SERVICE TO COMMUNITY

**Founder of the Big Brother Scholarship** \hfill 2018 to 2021

*Sydney Technical High School*

**Shirty Science with Canberra Girls Grammar** \hfill 2018

*Shirty Science*

**Youth STEM Conference** \hfill 2018

*Centre for Innovation and Learning*

**Sri Lanka Work Camp Volunteer** \hfill 2012

*Warrane College*

**Volunteer** \hfill 2011 to 2017

*Room to Read*

**Senior Prefect** \hfill 2011

*Sydney Technical High School*

## MEDIA OUTREACH

I regularly engage with media and my research has been covered by major media outlets including [ABC news](https://tinyurl.com/zhae9m9f), [Nine news](https://www.youtube.com/watch?v=klb-PZuiIW4&t=2s), [Sydney Morning Herald](https://tinyurl.com/9u3atmap), [Australian Financial Review](https://tinyurl.com/2s36n8ye), The Australian and ABC Radio. Links to all media outreach, including television, print, radio/podcast, in addition to invited talks, guest
lectures and public speaking events can be found [here](https://ananthanambikairajah.com/files/Ananthan_Ambikairajah_Media_Outreach.pdf).

# ACCREDITATION/PROFESSIONAL DEVELOPMENT

**UC Management Essentials Program** \hfill 2024

*University of Canberra*

**Higher Degree Research Supervisor** \hfill 2022

*University of Canberra*

**Complex Human Data Summer School Scholarship** \hfill 2019

*University of Melbourne*

**ANU Graduate Short Course Award in Science Communication** \hfill 2018

*Australian National University - Centre for The Public Awareness of Science*

**Research to Impact Program** \hfill 2018

*Canberra Innovation Network*

**Working with Vulnerable People - General Registration** \hfill 2023 to 2028

*ACT*

**Literacy and Numeracy Test for Initial Education Students** \hfill 2016

*Australian Council for Educational Research*

**Anaphylaxis Training** \hfill 2016

*Australasian Society of Clinical Immunology and Allergy*

**Diploma of Educational Studies** \hfill 2013

*College of Teachers, London*

**Animal Care and Ethics Course** \hfill 2013

*University of New South Wales*

## MENTORSHIP

**Canberra Health Services Research Mentoring Program** \hfill 2024 to date

*Canberra Health Services*

In this program, I mentored \censor{**Josie Goodyer**}. The mentorship program aims to support development of Canberra Health Services (CHS) staff to (1) increase research capability and activity, (2) develop networks in CHS and across the Australian Capital Territory and (3) improve career progression, confidence and satisfaction.

**Big Brother Scholarship Mentor** \hfill 2018 - 2021

*Ananthan Ambikairajah*

**Science Peer Mentor** \hfill 2015

*University of New South Wales*

**Ambassador and Mentor** \hfill 2012 to 2017

*Warrane College’s The Big Picture Program*

## MENTEESHIP

**Teaching Excellence Mentoring Program ** \hfill 2024 to date

In this program, I was mentored by Professor Nick Ball. The mentorship focuses on my application for the University of Canberra Teaching Excellence Award. 

*University of Canberra - Faculty of Health*

**Higher Education Academy Mentoring Program** \hfill 2023 to date

*University of Canberra*

In this program, I am mentored by Adjunct Professorial Associate Peter Copelan. The mentorship focused primarily on my Fellowship application submission to the Higher Education Academy. Upon successful admission as a HEA Fellow, the mentorship now focuses on my Senior Fellowship application. 

**Faculty of Health Mentoring Program ** \hfill 2021 to present

In this program, I was mentored by Professor Douglas Boer and am currently mentored by Associate Professor Phillip Newman. The mentorship focuses on my university portfolio (i.e. research, teaching, service and engagement), in addition to opportunities for professional development and pathways for promotion. 

*University of Canberra - Faculty of Health*

# OTHER INTERESTS

**Running** \hfill 2020 to date

- Canberra Times Marathon (42.2km) \hfill 2024 to date

- Sydney Marathon (42.2km) \hfill 2024 to date

- Indigenous Marathon Reconciliation Week Fun Run (10km) \hfill 2022 to 2023

- Dementia Australia Memory Walk and Jog (10km) \hfill 2020, 2023 to date

*Total Funds Raised for Dementia Australia via Running* = \$`r sprintf("%.0f", (355 + 389))`

**Rock Climbing** \hfill 2020 to date

**Performing Stand-up Comedian** \hfill 2013 to 2018

**Bamboo Flautist** \hfill 	2001 to 2016

**Chess** \hfill 2002 to date

**Tennis** \hfill 1999 to date

# REFEREES

Provided on request
