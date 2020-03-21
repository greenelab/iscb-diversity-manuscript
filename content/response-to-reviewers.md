# Response to Reviewers

The text of these reviews was copied from <https://github.com/greenelab/iscb-diversity-manuscript/issues/37>.
Add responses to this document.

## Review 1

> The paper describes an analysis of origin honorees and keynote speakers in the main bioinformatics conferences compared with the publication in three related journals using a number of methods to assign the names of the main authors to a gender and geographical origin (honors as the term used  is debatable in this context)
> 
> At the technical level the paper describes, first; a significant effort to recover the names of speakers and awardees from the conferences and second; a number of methods to assign names to gender and geographical origin.
> 
> There have been quite a lot of discussion on the methodological weakness of this paper  following its release on bioRxiv. The Race and Ethnicity chapter was particularly controversial, for example mixing it with religious terms was clearly an important error. Therefore, even if interesting, the technology proposed in the paper has still to mature to produce reliable results.

We agree with the reviewer that the names of the groups of countries were not appropriate as some were by country, some were by region, and others were by religion.
In this revision, we have retained the data-driven groupings but selected more appropriate names for the name origin groups.
Importantly, to complement the existing analysis, we performed an analysis of author affiliations to detect the affiliated countries for authors and honorees.
This is a major improvement of the study because, in the past work, an author's affiliation and name origin have some chance of being interlinked.
Now we can directly examine geographic discrepancies.
Within the most represented country (i.e., the US), we can also examine differences by name origin to remove the geographic confounder.
We found that both components (geography and name origin) still play a role.
By integrating different methods we hope to mitigate the existing biases and discover insightful findings that correctly reflect the current representation diversity at conferences.
Please see further discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/38>.

> Furthermore, classifying names might reveal an origin but not a nationality and certainly not where the work was carried out. All these consideration seems to scape the analysis (i.e. considering the scientists with a greek name - that is easy to recognise as such- and got some of the ISCB award recently represent a minority when they have developed almost all their profesional time in the USA is very unclear).

Our new affiliation analysis has addressed this point.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/39>.

> It is also unclear why this is the right strategy for the identification of the origin of the awardees/speakers. Direct searches for the names in bibliographic databases or in the society affiliations could be alternative possibilities.

Our new affiliation analysis has addressed this point.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/40>.

> A second problem with this approach is the use of the first/corresponding author of papers as background. Honors are given to scientists with significant contributions, where significant can be highly quoted, or original, or correspond to a long trajectory. Aspects, that might not be necessarily correspond to publications in the mentioned three journals. Indeed, many keynote invitations are to authors in related fields not necessarily published in bioinformatics journals. The logic of the comparison is unclear to say the least.

We selected these journals to establish a field-specific baseline (two ISCB partner and one field-specific) to represent the field of bioinformatics and computational biology.
We agree that this baseline is not perfect and invited speakers certainly publish in other journals, we wanted to test whether contribution of minoritized scientists in these journals are recognized (at conferences and when named Fellows).
Further, we expect a similar increasing trend of minoritized scientists' contribution in related fields.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/41>.

> Additionally, the two main conclusions of the paper are so obvious that is difficult to understand the need of the paper. First, conferences and societies in the field are doing an effort to maintain a healthy gender balance, even if clearly far from perfect the interpretation of the results seems to show a positive trend. Instead of analysing the results he authors go into a very long discussion of the causes and consequences,  a discussion that is potentially more appropriate for an opinion paper than for a scientific paper in the conference. The second aspect, is the geographical bias. Yes, it is obvious that most of the speakers are white, the important question to understand the origin of the bias is if there are other more influential authors in the literature that the ones that have been selected in these conferences . The paper does not provide the necessary data to assess is this is the case. To assume that the ideal situation will be to have a number of invitations/honors  proportional to the number of papers by region does not make any sense from a scientific or from the conference organisation point of view.

We agree that the lack of diversity has been readily apparent for some time.
Our paper's corresponding author curated the list of honorees in 2018 and shared the issues with ISCB board of directors members, but we did not observe any changes for 2019 despite these private attempts to influence diversity.
Since our paper's release, ISCB has released the [2020 set of Fellows](https://www.iscb.org/iscb-fellows), which is two times larger than most years and includes two scientists with affiliations in Asia including the first ever with an affiliation in China.
The [Award Winners](https://www.iscb.org/iscb-news-items/4249-2020-feb14-iscb-congratulates-2020-award-winners) also seem more diverse than past years.
We believe the paper provides rigorous analysis in a public setting to back up what has been apparent to anyone who cared: the primary society that aims to represent us as computational biologists needs to do better.
Now that this paper exists, changes have begun to appear.

Our new affiliation analysis helps address the other points related to geographic disparities.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/42>.

> In summary, at the scientific level the problem of normalizing names in terms of gender and origin is interesting and even if this paper makes some progress it is still not sufficient for a publication. As an opinion paper, the topic is obviously relevant and the conclusions known (gender balance is difficult and other biases are even more challenging) but the selection of the background (published papers in three bioinformatics journals) is misleading respect to the goal, i.e. selection of speakers and awardees, that is based on other criteria.

While diversity and parity is difficult to achieve in a short period of time, we strongly believe that acknowledging these disparities is an important first step toward justly recognizing contributions from minoritized scientists.
Our study does just that.
Now that changes have started to appear in the field of Computational Biology and Bioinformatics, we hope to see similar trend beyond the field and that minoritized scientists' contributions will be properly recognized in the long term.
Please see further discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/43>.


## Review 2

> The paper has an eye-catching title, partly because of the nature of the content and partly due to
> its implication to  ISMB as the flagship conference of ISCB.
> 
> Most of the technical content is around associating names to genders/geographic origin or curating publications.
> 
> Figs 1 and 2 does not strongly support the title. The over-representation and under-representation has
> not been quantified, with the appropriate statistical measures.

We have added statistical measures at different analysis steps, including the comparison of gender prediction, race prediction and affiliation analysis between authors and iscb honorees.
Please see further discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/44>.

> A few questions:
>
> 1\. Nationality/region definition: Mixing of religion and geographic regions is somewhat
> confusing for the uninitiated.
> I would have certainly benefited by understanding a basis for this classification.
> Even in "Nameprism" that the authors cite, the basis is unclear.

We agree with the reviewer that the names of the groups of countries were not appropriate as some were by country, some were by region, and others were by religion.
In this revision, we have retained the data-driven groupings but selected more appropriate names for the name origin groups.
Importantly, to complement the existing analysis, we performed an analysis of author affiliations to detect the affiliated countries for authors and honorees.
This is a major improvement of the study because, in the past work, an author's affiliation and name origin have some chance of being interlinked.
Now we can directly examine geographic discrepancies.
Within the most represented country (i.e., the US), we can also examine differences by name origin to remove the geographic confounder.
We found that both components (geography and name origin) still play a role.
By integrating different methods we hope to mitigate the existing biases and discover insightful findings that correctly reflect the current representation diversity at conferences.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/45>.

> 2\. I was not able to parse the subtle implications of
> "We suggest that considering equity may be more appropriate than strictly diversity" that the authors
> offer in the Conclusion section.

Discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/46>

> Any comments on LGBTQ, disability representation in STEM or the field of computational biology ?
> Finally, while I think the paper is interesting addressing the social/demographics of the
> ISCB community, it is outside the scope of the technical program of ISMB.

These are important topics, but we do not have a way to assess them within the paper.
To our knowledge, currently, ISCB does not have a robust program to obtain from its members the necessary information to study these elements and provide it to researchers in an anonymized way.
Hence, any comments on these topics are out of the scope of the present paper.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/47>.


## Review 3

> This is an important reflective effort to undertake, and I am glad that it was performed. The analysis on the whole seems reasonable.  It would be good to see more citations of this type of work in other disciplines and a comparison of the results here to what has been found in other scientific organizations. It also seems that the work could have been a bit more statistically rigorous in spots, and it would be nice to see more analysis of non-Asian ethnicities.

We agree with the reviewer that it is important to perform analyses of non-Asian ethnicities. 
We did break down the analysis for other groups in one [analysis notebook](https://greenelab.github.io/iscb-diversity/10.predict-race.html#sup_fig_s2), but it is difficult to come to a definite conclusion due to the small sample size.
However, our new affiliation analysis at the country level helps complement the previous analyses.
We have also cited the relevant literature we could find on the topic.
Many papers on academic diversity of various disciplines, as we discussed in the Discussion section, focus on the underrepresentation of women in different academic settings (e.g. invited by journals to submit papers less often, suggested as reviewers less often, or cited less often), but only a few focus on race (e.g. proposals by Asian, black or African-American applicants were less likely to be funded).
We have also added overall statistical measures at each analysis step as described point-by-point below.
Please see further discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/48>.

> Some specific comments below.
> 
> p. 1, last paragraph: I feel that this first paragraph of the introduction is not the strongest and doesn't add much to the paper overall.  I would suggest removing or reworking.

Discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/49>

> p. 3, paragraph 2: research advisors don't seem to be the best proxy for senior faculty who would be invited for keynotes or honored as fellows

We did not make this point clear.
What we meant was that, as authors on a specific paper, compared to their trainees, research advisor would be more likely to be invited for keynotes or honored as Fellows.
In the revised manuscript, we have clarified this point at the beginning of the subsection **Corresponding author extraction**:

"We assumed that, in the list of authors for a specific paper, corresponding authors (often research advisors) would be those most likely to be invited for keynotes or to be honored as Fellows."

Please see further discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/50>.

> p. 3, penultimate paragraph: if the breakdown is approximately 40/60 on first/last authors being corresponding, why take a majority rule?  Seems more rigorous to randomize the selection process according to this "weighted die"

We agree that an alternative method is to randomly select corresponding author (first or last) according this proportion.
However, this method, in general, will have lower accuracy compared to our hard assignment of where the majority of corresponding authors fall.
In other words, if we let $p$ denote the majority proportion ($0.5 < p < 1$) then $p^2 +(1-p)^2 - p = (2p-1)(p-1) < 0$, which implies $p^2 + (1-p)^2 < p$, i.e., random selection has lower chance to assume corresponding authors correctly.
Please see further discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/51>.

> p. 4, paragraph 2: It would be great to see citations for Genderize, especially ones that provide insights on accuracy/reliability.  It would also be nice to know how inclusive this app is in terms of names from across the world.  Without that, the 1578 missing forenames could be biased by any bias in this app.  This discussion is had with respect to wru lower down on the page, so it's natural to provide this standard here.

In the revised manuscript, we have added two citations for genderize.io regarding its accuracy and bias:

"We predicted the gender of honorees and authors using the <https://genderize.io> API, which was trained on over 100 million name-gender pairings collected from the web and is one of the three widely-used gender inference services that provide gender classifications with over 98% accuracy (Santamaría and Mihaljević, 2018).
[...] This bias of NA predictions toward non-English names has been previously observed (Weis 2016) and may have a minor influence on the final estimate of gender compositions."

Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/52>

> p. 4, paragraph 4: The terms "race" and "ethnicity" are used in the paper, but there isn't really a definition of these terms in terms of categories.  It would be nice to see that explicitly laid out, perhaps with a citation.

We appreciate the reviewer for pointing out this oversight.
In the revised manuscript, we have referenced guidance from the census and make it clearer in the **Estimation of Race and Ethnicity** subsection of the **Methods** section.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/53>.

> p. 4, paragraph 4: Why is using the average demographic distribution a reasonable assumption to make?

It is not.
We had exactly the same concerns when we performed the work, so we modified the function to return NAs so as to not use average demographic distribution.
We have clarified the **Estimation of Race and Ethnicity** subsection of the **Methods** section of the revised manuscript:

"However, in the case of names that were not observed in the census, the function outputs the average demographic distribution from the census, which may produce misleading results.
To avoid this suboptimal imputation, we modified the function to return a status denoting that results were inconclusive (NA) instead."

Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/54>.

> p. 7, Figure 2: It would be better to see statistics provided as part of this analysis.  It strikes me that the problem at hand here is similar to sample-to-sample microbiome population analysis, which use rigorous statistics, and the same types of methods could be used for analysis in Fig. 2.  This level of statistical rigor is present as part of Figure 3, which was good to see.

We agree.
During revision, we have added overall statistics from 3 Welch two-sample t-tests for each prediction classes: white, Asian and Other categories.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/55>.

> p. 9, Figure 4: The same point can be made here as for Figure 2.  It would be nice to see a statistical analysis and a p-value or two to justify claims beyond appealing to figures.

During revision, we have added overall statistics for gender comparison between authors and iscb honorees.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/56>

> p. 9, Figure 4: The term "other categories" is used but these are never really defined (see previous point).  It would be good to do so, perhaps even in a supplement.

In the revised version of the manuscript, we specified which regions category O contains in the caption of this figure.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/57>.

## Review 4

> This manuscript looks at the representation issues when honoring scientists in the field of computational biology by a computational biology society (ISCB). It establishes a background distribution based on the authors of relevant journal publications and then studies subgroup representation of keynotes at three of the ISCB-affiliated conferences (ISMB, RECOMB, PSB) and ISCB fellows against that distribution. It analyzes predicted gender, nationalities, ethnicities, and race of honorees. There are several findings but the major and only stated conclusion in Abstract is that there is recognition overrepresentation of white scientists and underrepresentation of non-white scientists.
> 
> This topic is out of scope for the proceedings of ISMB, at least by how I interpret the scope. It has its place in the published literature (I recommend with major revisions), but there is no methodology for or the analysis of molecular and biological data. Instead it is a study about the authors of such papers and broadly speaking it characterizes the recognition and reward system for their contributions to the field.

We appreciate the reviewer's perspective.
We felt that this work, as it focused on ISCB, was appropriate for submission as a general computational biology manuscript.
However, it is clear that the reviewers and session organizers felt differently, so we are pursuing other venues to disseminate the work.
See discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/58>.

> To give feedback to the ISMB senior committee and also the authors about their work, I offer a critique below assuming the manuscript is within scope of the ISMB proceedings.
> 
> Overall this is a clearly written manuscript on a clearly important topic. The work has merits and it presents simple conclusions, but it also has deficiencies in analysis and presentation of results that need to be addressed.
> 
> Positives:
> * Social trends in science are important to track and corrective measures are necessary when disparities are identified. The manuscript brings attention to these important issues.
> 
> * Societies should be kept in check and it is the responsibility of the members (and non-members) to appropriately expose problems and fix problems. It is difficult to strike the right tone and for most of the manuscript the authors did it well.
> 
> * The analysis is solid for the most part. The focus on corresponding authors is appropriate. I see no better way to address the issues of gender and race/ethnicity but to employ prediction. I'd assume this prediction is roughly correct for gender. I am less sure about race, ethnicity, religion, etc because a few queries at NamePrism did not convince me of a very high accuracy or satisfy me with its groupings. The authors use their own tool, but I have not queried it. Overall though, I am willing to accept that this works well on average to not impact broad conclusions. The authors recognized that.
> 
> * Although results might appear simple, substantial work has been completed.

We appreciate the reviewer's positive feedback on our work.
We strongly believe that acknowledging these disparities is an important first step toward justly recognizing contributions from minoritized scientists.
This is the goal of the study.

> Comments on the analysis:
> \* The analysis focuses on ISCB, its fellows and its conferences. ISCB conferences are listed at: https://www.iscb.org/iscb-conferences however, justification was not provided as to why some conferences made it and others did not. PSB for example was assessed as international but this is hard to justify given its location patterns. GIW/ISCB-Asia is omitted, but no justification was given. This is of course of significant importance for the conclusions. Either justification or expanded analysis is needed.
>
> \* Related to above, the selected journals for the background are of global reach (especially Bioinformatics because of rankings and $0 closed-access publication charges) whereas selected ISCB conferences (with their honorees) are more localized in Europe and North America for financial reasons. Considering the field as a whole, there are conferences that are limited to Asia, such as APBC or ISCB-Asia/Genome Informatics Workshop that are both of good quality and well known. APBC 2020 web site also shows that BMC Bioinformatics is among journals for their special issue. This suggests that the journals indeed better represent the field and that conferences are more geographically fragmented, including potentially ISCB conferences. This in turn means that the selection of conferences is critical for the outcome and appropriateness of this analysis. I think it would be appropriate to see a recognition of this fact in the manuscript and adjust the analysis.

We agree with the reviewer that, given PSB's location patterns, it should not be considered in this study.
We have removed this symposium out of all of the analyses.
In the revision, we focus on ISMB and RECOMB as the two society-associated meetings that are meant to represent the society globally, aim to have an international reach, and have been held in multiple continents.
Discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/62>.

> \* The background in the study is created from the publications in well-selected journals (Bioinformatics, BMC Bioinformatics and PLOS Computational Biology). That background is appropriate and provides a useful characterization but is not necessarily the most appropriate. When one talks about a society, an alternative appropriate background would be the professional membership in that society (a society has responsibilities to recognize the work of its members well). The gender information in ISCB should be publicly available so the authors can check the trends and agreements with the current background. The authors could even be able to work out a solution with ISCB to apply the predictors to the data and more deeply test their hypotheses. The conclusions could hold or not and new patterns could emerge.

Discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/61>

> \* Figure 1. There is no statistical analysis of this data. By eyeballing the graphs it looks like that women are not underrepresented as honorees, and might even be overrepresented. This should be discussed more formally (e.g. statistical tests) and confidence intervals or statistical significance should be provided much like in Figure 2, whatever the conclusions are.

During revision, we have added an overall statistic for gender comparison between authors and iscb honorees.
We found no statistically significant difference in the mean probability of honorees predicted to be female compared to that of authors.
The revised manuscript now includes this result in the **Assessing Gender Diversity of Authors and Honorees** subsection:

"Further, taking all the years together, a Welch two-sample t-test does not reveal any statistically significant difference in the mean probability of ISCB honorees predicted to be female compared to that of authors (t~418~ = 0.753, p = 0.226)."
Please see further discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/63>

> \* This may or may not be a problem in this study, but suppose 10 random papers from group A are published by 5 different corresponding authors and another 10 random papers from group B by a single member of that group. The chances that the top scientist is from group A is not 50%. How was this potential problem accounted for? If not, the authors could state how this might impact the outcomes.

This is not a potential problem in our study because we did not randomly select papers and randomly assign groupings.
We considered all publications in the specified journals and assigned prediction probabilities for corresponding authors based on carefully trained models.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/64>

> \* Minor: the keynote speakers for ISMB can be found on ISCB's web site and AAAI web site prior to 2002.

We thank the reviewer for pointing us to this resource.
We have now added to the analysis 42 ISMB speakers from 1993 -- 2002.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/65>

> Comments on the presentation:
> \* The abstract lists only one conclusion in the last sentence: white scientists are overrepresented and non-white scientists are underrepresented. This strikes me as cherry picking of findings. The paper, if I understood correctly, also found that female scientists are not underrepresented. Given the current climate, wouldn't it also be a major conclusion that the honorees are reasonably distributed gender-wise? Instead, the conclusion is "but the proportion has not reached parity". This suddenly changes the focus from ISCB practices relative to the field to ISCB practices relative to the entire society, which is a different background distribution and one where ISCB has little influence on.

Discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/66>

> \* Introduction: "finding that minority scientists tend to apply for awards on topics with lower success rates [1] could be interpreted either as minority scientists select topics in more poorly funded areas or that majority scientists consider topics of particular interest to minority scientists as less worthy of funding." It might look inflammatory to use terminology "less worthy" here. Maybe this was meant in a narrow technical sense, but a reader might decide to go for a broad interpretation and assess that the whole system is discriminatory.

Discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/67>

> \* Figure 4 and the category selection for the analysis are highly problematic. I understand that the categories were selected according to NamePrism, but it is ultimately the responsibility of the authors to justify choices. What is compared is a continent (Europe, Africa), a religion (Muslim), a country (Israel), a part of the continent (East Asian, South Asian), a group of different races or ancestries that spans continents (Hispanic), and then there are Celtic English folk. This analysis needs a substantial revision to the broader and more parallel categories, even compared to previous Figures in the manuscript. The genetics community has been successful discussing continental and subcontinental populations though the problem here is to infer those from names that reflect many things. Singling out Israel as overrepresented sends a tricky message when listed right next to Muslim as underrepresented. It surprised me to see this insensitivity in a study that is meant to assess where we are as a community and to promote sensitivities.

We agree with the reviewer that the names of the groups of countries were not appropriate as some were by country, some were by region, and others were by religion.
In this revision, we have retained the data-driven groupings but selected more appropriate names for the name origin groups.
Importantly, to complement the existing analysis, we performed an analysis of author affiliations to detect the affiliated countries for authors and honorees.
This is a major improvement of the study because, in the past work, an author's affiliation and name origin have some chance of being interlinked.
Now we can directly examine geographic discrepancies.
Within the most represented country (i.e., the US), we can also examine differences by name origin to remove the geographic confounder.
We found that both components (geography and name origin) still play a role.

We don't think it is accurate to characterize our work as an attempt to "promote sensitivities."
Instead, we think it would be more appropriate to describe the work as an effort to examine the patterns that underlie who is and who isn't being honored by the field's major international society.
By integrating different methods we hope to mitigate the existing biases and discover insightful findings that correctly reflect the current representation diversity at conferences.
Please see further discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/68>

> \* I would like to see discussion on the topic of how ISCB should adjust to identify scientists that merit recognition but have fallen through the cracks so far? Can a data-driven help be of use?

This is an important discussion point.
In fact, we did raise this point in the Discussion section:

"Societies, both through their honorees and the individuals who deliver keynotes at their meetings, can play a positive role in improving the presence of female STEM role models. [...] Honorees include significantly fewer people of color than the field as a whole, and Asian scientists are dramatically underrepresented among honorees. [...] Societies can play a positive role in enhancing equity if they design policies to honor scientists in ways that counter these biases."

Please see further discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/69>

## Review 5

> This is an analysis of 411 ISCB honorees who were keynote speakers at ISCB-associated conferences (ISMB, 2002-2019, RECOMB 1997-2019, and PSB 1999-2020) as well as ISCB Fellows named (2009-2019).
> 
> The profile of awardees was compared to a corpus of articles in Bioinformatics, BMC Bioinformatics from (2002-), and PLOS Computational Biology (2005-). PMC corresponding author information when it was available (20,696 articles) and the PubMed last author as a fallback when corresponding author information was missing (9,053 articles).  It is unknown how many of these articles were published by the name authors, or if the were attributed uniquely to authors. For example, it is custom in some institutes that the dept chair is a senior or corresponding author, and thus some authors might be over-represented by chance in the data.  Recent Increases in Asian corresponding authors was primarily driven by recent publications in Bioinformatics and BMC Bioinformatics. The % of Asian authors estimated from these journals suggests a lack of Asian scientists among keynote speakers and honorees.
> 
> The authors created the pubmedpy Python package to parse names from articles and used https://genderize.io to predict gender. Race and ethnicity of honorees and authors was inferred using the R package wru and were associated with race/ethnicity category based on US census data
> 
> Of 34,050 corresponding authors, over 25% (8,770) had a last name for which wru did not provide predictions.  Do the author know if these were random or non-random in distribution.

These missing values were non-random.
Because wru uses the US census to make predictions, many of the missing predictions are on names not observed in the US census.
Therefore, we expect an underestimation of the number of these names in both the list of authors and honorees.
We have added this limitation and our effort to alleviate this issue in the Discussion section of the revised manuscript:

"Because wru was trained on the US census to make predictions, many of the missing predictions are on names not observed in the US census.
Although the underestimation of the proportion of these names could not be compared between the list of authors and honorees, we complemented this race/ethnicity prediction method with an additional name origin analysis."

Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/70>

> There are assumptions and analysis issues. Did the author check if the association between predicted race/ethnicity and author Affiliation?  Was Asian bias by country or ethnicity?  For example, are American-Asians represented in ISCB honorees but Asians who are geographically located in Asia under-represented. Is this associated with geographic attendance at ISCB meetings? One might expect local awardees in the host country. For example, the authors note that ISMB keynotes had more probability attributable to Israel, while RECOMB had more attributable to East Asian countries.

We agree with the reviewer that the names of the groups of countries were not appropriate as some were by country, some were by region, and others were by religion.
In this revision, we have retained the data-driven groupings but selected more appropriate names for the name origin groups.
Importantly, to complement the existing analysis, we performed an analysis of author affiliations to detect the affiliated countries for authors and honorees.
This is a major improvement of the study because, in the past work, an author's affiliation and name origin have some chance of being interlinked.
Now we can directly examine geographic discrepancies.
Within the most represented country (i.e., the US), we can also examine differences by name origin to remove the geographic confounder.
We found that both components (geography and name origin) still play a role.
We also limit our race/ethnicity analysis to only US-affiliated scientists to avoid further biases.

Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/71>.

> Given this small pool of 411, some names of which were duplicated (fellows and keynotes etc), were they manually checked for accuracy.

We did not manually check names and photos to guess gender or name origins to avoid inducing bias.
Please see discussion at <https://github.com/greenelab/iscb-diversity-manuscript/issues/72>.

> There are non-random missing data. European Spanish/Portuguese/Italian are called Hispanic. Assignment of the race (white/black/Asian) based surname is difficult to extrapolate to a multi-cultural society where last name and skin color are maybe discordant.

We acknowledged that our supervised learning approaches are neither error free nor bias free.
We would also note that it would be a mistake to consider race equivalent to skin color: race, as analyzed in this study, is based on self-identification and is a complex topic with its own area of research.
However, once again, we hope that the newly added affiliation analysis at the country level without groupings will complement the approaches in the earlier version of the study.
By integrating different methods, we hope to mitigate the existing issues and discover insightful findings that correctly reflect the current representation diversity at conferences.
