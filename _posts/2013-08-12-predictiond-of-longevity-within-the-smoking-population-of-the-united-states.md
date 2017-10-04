---
layout: post
title: "Post with Image Feature"
date: 2014-04-07
excerpt: "Understanding Atmospheric Neutralization and It's Dependence"
tags: [Analytical Chemistry, Stastics]
feature: http://imageshack.com/a/img924/6829/AFr1mw.png
project: true
comments: true
---
{% capture images %}
	http://imageshack.com/a/img924/5298/8jR3sW.png
	http://imageshack.com/a/img924/9587/Ti7O5T.jpg
	http://imageshack.com/a/img923/3295/rGwzGp.png
	http://imageshack.com/a/img923/3413/OQOK0S.png
	http://imageshack.com/a/img923/8468/wHlezw.png
	http://imageshack.com/a/img922/2697/ggdvEJ.png
{% endcapture %}
{% include gallery images=images caption="Painting is just one way for me to express my presonality" cols=1 %}


ABOUT
 
RESEARCH
 
PRESENTATIONS
 
LINKEDIN
 
BLOG
 
ART
PREDICTIONS OF LONGEVITY WITHIN THE SMOKING POPULATION OF
THE UNITED STATES
An assessment of studies on the hazards of smoking was done to determine areas of improvement for better representation of population and increased accuracy in predictions.
August 12, 2013
MORTALITY RATES

of smokers have been studied in many counties in order to understand other external influences and effects of covariates of population demographics [i][ii][iii]. An article by P. Jha et al. in the New England Journal of Medicine showed the hazards of smoking while adjusting for variables of education, alcohol consumption, and adiposity within the population of the United States. The findings in the article were fascinating because it also analyzed the mortality of individuals that have quit smoking.

 Picture
We assessed the hazard model that was used in the article and found that improvements can be made in covariates of education, adiposity and levels of alcohol consumption. Since the study considers the population of those that have quit smoking, it would be appropriate to study the quality of life in terms of dependence on social assistance.

We did not use the income variable as there was a tendency for bias within the lower income brackets[iv]. Pre-analysis indicates that there are higher rates of missing income information within groups that relies on welfare support and food stamps. Thus substitution with a variable for the usage of welfare and food stamps for quality of life is sufficient.
Covariates of education was reconsidered to be stratified because we do not expect linear relations with mortality. The knowledge level of the health risks of smoking will be different in elementary school, secondary School, and post-secondary education.

Modeling with adiposity variable, BMI, requires a more complicated approach to account for the non-linear relation with health[v]. Recent studies have shown that slightly overweight individuals may have an advantage over underweight individuals[vi].The relation between BMI and smoking status are also ambiguous since smoking status have been shown to influence BMI[vii].

 Picture
When determining the hazard ratios for current smokers and former smokers versus non-smokers, we discovered that confidence intervals were reduced with stratification of BMI and education variables (figure 1). We saw further reduction and improvements when the variable for social status was incorporated.
 Picture
Figure 1 - Results of using different covariates to model Hazards of smoking.
A crude way of estimating the probability of survival for current smokers compared to non-smokers was used, which will helped us understand the reduction in longevity due to smoking. The results of our model gives hazards ratio and probabilities but there has to be a better way to communicate these complex statistical findings to transform probabilities into likelihood of the years reduced (Figure 2). Using our revised model, we were able to determine that in general, smoking will result in a reduction of 10 years for females and 9 years for males, compared to 11 years for females and 12 years for males in original study.
 Picture
Figure 2 - Survival Curves calculated by using an age-specific proportional-hazard model adjusting for Education, BMI, alcohol consumption and social assistance. The probability of surviving to the age of 82 for a non-smoker is the same as the probability of surviving to age of 72 for current smokers which resulted to a reduction of 10 years for females and 9 years for males.
Thanks to the large data size, the results on benefits of cessation from subcategorizing the age when quitting smoking is reliable. It is evident that earlier a smoker quits, the better it is so this analysis may seem redundant. However an important factor in achieving success in life goals is whether the goal is time bounded.

Using the same technique to determine the reduction in longevity, we determine the years gained by complete cessation, with the analysis of closeness of the probability curves of former smokers compared with never smokers. By analyzing the years gained within each age bucket of time when one quits smoking, we found that quitting at the age of 40-50 has the most impact on health (figure 3). Better yet, our findings should that survival curves of those that quitting smoking before the age of 25 is close to being identical to those that have never smoked.
 Picture
Figure 3 - Survival Curves calculated by using an age-specific proportional-hazard model adjusting for Education, BMI, Alcohol consumption and social assistance. Calculations of survival probabilities of former smoker was done with a crude method of multiple probability by Hazard ratios.
Although it is exciting to learn that our health is not significantly impacted if we are able to quit smoking before the age of 25, the findings in this study are based on past events. Society is constantly changing and at non-linear rates. The most that this study can offer is a historical summary of the population of United States and the figures should be used with considerations.
MORE ABOUT THE SAMPLE POPULATION
MORE ABOUT SMOKING RELATED DEATHS
MORE ABOUT MORTALITY MODELS
METHODOLOGY


Data was collected from the U.S. National Health Interview Survey between the years of 1997 and 2004[viii]. In the following years up until 2006, death records of interviewed individuals were collected from the National Death Index [ix]. Data Analysis was done using SAS and Stata software with similar adjustments to the P. Jha paper.
ACKNOWLEDGMENT

All support and assistance from Professor Paul Grootendorst is greatly acknowledged, an additional acknowledgement goes to Professor Alison Gibbs and the SAS company for the free year subscription to the statistical program SAS.
BACK TO RESEARCH
REFERENCE

i)Jha P, Landsman V, et al. 21st-Century Hazard of Smoking and Benefits of Cessation in the United Stata.N Engl J Med 2008; 4:341-250.

ii)Basavaraj S. Smoking and loss of Longevity in Canada. Canadian J of Public Heath-Revue 1993;3:341-345.

iii)Pirie K, Peto R, et al. The 21st-Century Hazard of Smoking and Benefits of Stopping: A prospective study of one million women in the UK.LANCET 2013; 9861:133-141.

iv)Turrell G. Income non-reporting: implications for health inequalities research. J Epidemiology and Community Health 2000;54:207-214.

v)De Gonzales AB, et al.Body-Mass Index and Mortality among 1.46 Million White Adults. N Engl J Med 2010; 363:2211-2219.

vi)Curtis JP, et al. The Obesity paradox – Body mass index and outcomes in patients with heart failure. Archives of Internal Med 2005;165:55-61.

vii)Sneve M, Jorde R. Cross-sectional study on the relationship between Body mass index and smoking, and longitudinal changes in body mass index in relation to change in smoking status: The Tromso Study. Scandinavian J of Pub Health 2008; 36:397-407.

viii)National Health Interview Survey. Hyattville, MD; National Center for Health Statistis, May 2013 (http://www.cdc.gov/nchs/nhis.htm).

ix)National Health Interview Survey (1986-2004) Linked Mortality Files, mortality follow-up through 2006: matching methodology. Hyattville, MD: National Center for Health Statistic, May 2013 (http://www.cdc.gov/nhis/data/datalinkage/matching_methdology_nhis_final.pdf).


CREATE A FREE WEBSITE
POWERED BY 




Portland in shoreditch Vice, labore typewriter pariatur hoodie fap sartorial Austin. Pinterest literally occupy Schlitz forage. Odio ad blue bottle vinyl, 90's narwhal commodo bitters pour-over nostrud. Ugh est hashtag in, fingerstache adipisicing laboris esse Pinterest shabby chic Portland. Shoreditch bicycle rights anim, flexitarian laboris put a bird on it vinyl cupidatat narwhal. Hashtag artisan skateboard, flannel Bushwick nesciunt salvia aute fixie do plaid post-ironic dolor McSweeney's. Cliche pour-over chambray nulla four loko skateboard sapiente hashtag.

Vero laborum commodo occupy. Semiotics voluptate mumblecore pug. Cosby sweater ullamco quinoa ennui assumenda, sapiente occupy delectus lo-fi. Ea fashion axe Marfa cillum aliquip. Retro Bushwick keytar cliche. Before they sold out sustainable gastropub Marfa readymade, ethical Williamsburg skateboard brunch qui consectetur gentrify semiotics. Mustache cillum irony, fingerstache magna pour-over keffiyeh tousled selfies.

## Cupidatat 90's lo-fi authentic try-hard

In pug Portland incididunt mlkshk put a bird on it vinyl quinoa. Terry Richardson shabby chic +1, scenester Tonx excepteur tempor fugiat voluptate fingerstache aliquip nisi next level. Farm-to-table hashtag Truffaut, Odd Future ex meggings gentrify single-origin coffee try-hard 90's.

* Sartorial hoodie
* Labore viral forage
* Tote bag selvage
* DIY exercitation et id ugh tumblr church-key

Incididunt umami sriracha, ethical fugiat VHS ex assumenda yr irure direct trade. Marfa Truffaut bicycle rights, kitsch placeat Etsy kogi asymmetrical. Beard locavore flexitarian, kitsch photo booth hoodie plaid ethical readymade leggings yr.

Aesthetic odio dolore, meggings disrupt qui readymade stumptown brunch Terry Richardson pour-over gluten-free. Banksy american apparel in selfies, biodiesel flexitarian organic meh wolf quinoa gentrify banjo kogi. Readymade tofu ex, scenester dolor umami fingerstache occaecat fashion axe Carles jean shorts minim. Keffiyeh fashion axe nisi Godard mlkshk dolore. Lomo you probably haven't heard of them eu non, Odd Future Truffaut pug keytar meggings McSweeney's Pinterest cred. Etsy literally aute esse, eu bicycle rights qui meggings fanny pack. Gentrify leggings pug flannel duis.

## Forage occaecat cardigan qui

Fashion axe hella gastropub lo-fi kogi 90's aliquip +1 veniam delectus tousled. Cred sriracha locavore gastropub kale chips, iPhone mollit sartorial. Anim dolore 8-bit, pork belly dolor photo booth aute flannel small batch. Dolor disrupt ennui, tattooed whatever salvia Banksy sartorial roof party selfies raw denim sint meh pour-over. Ennui eu cardigan sint, gentrify iPhone cornhole.

> Whatever velit occaecat quis deserunt gastropub, leggings elit tousled roof party 3 wolf moon kogi pug blue bottle ea. Fashion axe shabby chic Austin quinoa pickled laborum bitters next level, disrupt deep v accusamus non fingerstache.

Tote bag asymmetrical elit sunt. Occaecat authentic Marfa, hella McSweeney's next level irure veniam master cleanse. Sed hoodie letterpress artisan wolf leggings, 3 wolf moon commodo ullamco. Anim occupy ea labore Terry Richardson. Tofu ex master cleanse in whatever pitchfork banh mi, occupy fugiat fanny pack Austin authentic. Magna fugiat 3 wolf moon, labore McSweeney's sustainable vero consectetur. Gluten-free disrupt enim, aesthetic fugiat jean shorts trust fund keffiyeh magna try-hard.

## Hoodie Duis

Actually salvia consectetur, hoodie duis lomo YOLO sunt sriracha. Aute pop-up brunch farm-to-table odio, salvia irure occaecat. Sriracha small batch literally skateboard. Echo Park nihil hoodie, aliquip forage artisan laboris. Trust fund reprehenderit nulla locavore. Stumptown raw denim kitsch, keffiyeh nulla twee dreamcatcher fanny pack ullamco 90's pop-up est culpa farm-to-table. Selfies 8-bit do pug odio.

### Thundercats Ho!

Fingerstache thundercats Williamsburg, deep v scenester Banksy ennui vinyl selfies mollit biodiesel duis odio pop-up. Banksy 3 wolf moon try-hard, sapiente enim stumptown deep v ad letterpress. Squid beard brunch, exercitation raw denim yr sint direct trade. Raw denim narwhal id, flannel DIY McSweeney's seitan. Letterpress artisan bespoke accusamus, meggings laboris consequat Truffaut qui in seitan. Sustainable cornhole Schlitz, twee Cosby sweater banh mi deep v forage letterpress flannel whatever keffiyeh. Sartorial cred irure, semiotics ethical sed blue bottle nihil letterpress.

Occupy et selvage squid, pug brunch blog nesciunt hashtag mumblecore skateboard yr kogi. Ugh small batch swag four loko. Fap post-ironic qui tote bag farm-to-table american apparel scenester keffiyeh vero, swag non pour-over gentrify authentic pitchfork. Schlitz scenester lo-fi voluptate, tote bag irony bicycle rights pariatur vero Vice freegan wayfarers exercitation nisi shoreditch. Chambray tofu vero sed. Street art swag literally leggings, Cosby sweater mixtape PBR lomo Banksy non in pitchfork ennui McSweeney's selfies. Odd Future Banksy non authentic.

Aliquip enim artisan dolor post-ironic. Pug tote bag Marfa, deserunt pour-over Portland wolf eu odio intelligentsia american apparel ugh ea. Sunt viral et, 3 wolf moon gastropub pug id. Id fashion axe est typewriter, mlkshk Portland art party aute brunch. Sint pork belly Cosby sweater, deep v mumblecore kitsch american apparel. Try-hard direct trade tumblr sint skateboard. Adipisicing bitters excepteur biodiesel, pickled gastropub aute veniam.
