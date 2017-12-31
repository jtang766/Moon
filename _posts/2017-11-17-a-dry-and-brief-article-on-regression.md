---
layout: post
title: "A Dry and Brief Article on Regression"
date: 2017-11-17
excerpt: "Getting the dry stuff out of the way so we can do something interesting."
tags: [Statistics]
feature: /assets/img/Article_UANAID/header.png
project: true

---


## It is easy

A dry and brief article on regression 

Getting the dry stuff out of the way so we can do something interesting. 

No matter where you go you will always find someone performing analysis. This is no surprise since it is only human nature to question why an event has occurred and what caused it to happen. As we gain a better understanding of the cause and effect, we can better prevent a bad thing from happening or predict the chances of a positive gain.

Because analysis of trends became popular and was used in every industry, mathematicians and statisticians came together to develop a set of procedures for quantifying results, analyzing data and predicting the future. The big idea was that when something happens to x (independent variable), this cause a change in y (dependent variable) and by systematically analyzing the change in one variable relative to another we can use our observations to predict the outcome of a set parameter. The set of procedures used to measure the correlation between variables is a called regression analysis.
 
Regression analysis can take on many forms and names depending on the data you want model and how complex you want analysis to be. Most of you have done a simple one variable linear regression known as the linear line of best fit (does y=mx+b ring any bells)? On the other end of the spectrum, regression has no limits on the type of data it can model, which makes it so powerful. Some examples of advanced regression modeling includes logistic model, multivariate, time series and hazards models. They all do the same task of finding correlation in the data and minimizing error in predictions.
 
[picture of line of best fit]

At this moment, you might be wondering if regression is some kind of black box magic that takes an input and splits out a model that we are supposed to trust. The answer is Yes and No. In simple language regression takes two types of variables, a dependent variable (y, the effect) and a set independent variables (x, the cause); and performs a series of calculations to predict the correlation by minimizing the level of random error. An example we can relate to is the weather, we have general idea of how cold it will be tomorrow based on the temperature of today. If we were to record the temperature every day, we can estimate that the temperature will drop by one degree every few days. However, for temperatures during a storm we will take with consideration, since it might be much colder one day and warmer the next, regression will consider this as a random error. If we had more data on temperatures during storms we can add this variable into the analysis as well. When we add more variables in the model, regression seems more like black box magic since the number of calculations the program performs exponentially increases to the point where it’s hard for the human mind to comprehend, let alone do manually.

[Computer Magic]
 
Because regression looks at every data point and it’s relation with other metrics without any knowledge of the background, often a skilled statistician or data scientist is needed to monitor the analysis to ensure a cleaned dataset is being fed to the program and adjustments are made such that the model matches the nature of the industry. For us in digital marketing, that means restrictions and the model matches the digital landscape. Below are some questions statistician performing regression might ask,
 
1.   Is my data bias in anyway?
2.   What are the main KPIs and what are the secondary KPIs?
3.   Are there any relation between the KPIs? Such as clicks and sessions.
4.   Are there any boundaries and limitations the model needs to know about the data?
 
In conclusion, regression is the general term for describing the statistical procedure for analyzing trends. Often when performing predictive analysis or forecasting, you might not recognize that you are performing regression analysis since it can quickly transform and certain models are used so often that they have adapted their own name. I was once told by an expert in data that there is only 2 questions an analyst needs to answer, (1) what is the current state? And (2) what are the trends? The current state is described by reporting (Totals, Average and Medians), whereas the story of trends is told by regression.


to look at the atmosphere and assume that not much is happening but the fact of the matter is the atmosphere is very complex with many layers and contains particulate matter ranging in a variety of sizes and properties. Relatively speaking it is easier to study the atmosphere using bigger particles such as dust or pollen because they can act as a microscopic environment for gaseous contaminants to interact with each other.

Understanding these interactions can help us assess the true geographical effects of atmospheric pollutants from urbanized centers and the extent of natural processes from the surrounding ecosystem in counteracting the imbalance. The two major gaseous contaminants that are widely studied are SO2 (sulfur oxide, we will also refer it as sulfate the ionic derivative) and NOx (Nitrogen orgasms, we will also refer them as nitrates the ionic derivative).

In 1990 The Clean Air Act [i] was intended to reduce the emission of SO2(g) and NOx within the transportation sector. A study by Holland M. D et al. [1999] [ii] on data collected from CASNet (Clean Air Skies Network) concluded a gradual and significant decrease in SO2, and a moderate decrease in NOx after 1990. Our study will extend the study to 2013 with analysis of the characteristics of particle solid phases.

Due to time constraints, we only studied six sites that geographically span across the United States (figure 1). Within western United States Glacier NP and Grand Canyon NP represent less industrialized areas, where as Penn State and Shenandoah NP are within close proximity of industrialized areas. Perkinstown does not have a strong influence from urbanization however, it is located within the Northern Plains Region which has the highest agricultural production as stated by USDA (United States Department of Agriculture) [iii].

<center><figure>
	<img src="/assets/img/Article_UANAID/Figure_1.png">
	<figcaption>
	Figure 1 - Six CASTNet sites used in analysis.</figcaption>
</figure></center>

Averages of ion concentration within particulate matter are in alignment with the relative urbanization surrounding the sites, showing that more industrialized areas have higher emissions of sulfates and nitrates. The parameters used to understand overall acidity of the atmosphere are the measurement of strong acidity and for overall neutrality, neutralization. The equations for these parameters can be found in the methodology below. These parameters takes the simplistic approach in estimating the charge balance within the system.

Measurements of the concentrations of sodium Na+ and chloride Cl- were available after 2000, even though their concentrations are relatively small and will not affect the overall annual trends, inclusion in statistical modeling have shown significance. Especially with chloride which has a strong affinity for ammonium creating a strong influence on the neutralization of the system.

<center><figure>
	<img src="/assets/img/Article_UANAID/Table_1.png">
	<figcaption>
	Table 1 – Particle ion concentrations. Abbreviations for site name are GLA: Glacier NP, GRA: Grand Canyon NP, PER: Perkinstown, SHE: Shenandoah NP, PEN: Penn State, GEO: Georgia Station.</figcaption>
</figure></center>

Naturalization of the atmosphere is important because it helps to maintain the pH level of rain water to about 5.6, which is the natural pH of rain. Acidity levels of acid rain below the pH of 5.6 will lead to harmful effects on human health, terrestrial and aquatic ecosystems. Calculations used to determine the acidity of the environment require complex calculations, which were conveniently available as an online model, known as E-AIM (Extended Aerosol Inorganics Model) [iv].

A drawback to our analysis was that only weekly measurements were available. This may not greatly affect the ion concentrations, however weekly averages of relative humanity for E-AIM are completely useless. For the spirt of understanding the particulate system, we analyzed the behavior of the system by setting the relative humanity at 70%, 80% and 90%. Due to the extensive procedure, only concentrations of Georgia Station were analyzed.

Figure 2 shows the calculated pH values from the E-AIM model. Average pH for rainfall within the United State is about 4.3 by the EPA (Environmental Protection Agency). The wave-like pattern is a result of seasonal changes; during warmer seasons vegetation will naturally produce more ammonia resulting in a lower pH.

<center><figure>
	<img src="/assets/img/Article_UANAID/Figure_2.png">
	<figcaption>
	Figure 2 – pH values calculated through E-AIM with set relative humidity values. Vertical lines marks the end of the year.</figcaption>
</figure></center>

Observations at the relative humidity of 70% are interesting as the system only exists at two levels of pH. Further analyses with set relative humidity at increments of 2% from 70% to 90% shows that at a relative humanity of 78%, the system equalizes into a continuous trend.

<center><figure>
	<img src="/assets/img/Article_UANAID/Figure_3.png">
	<figcaption>
	Figure 3 – A) pH values at relative humidity of 70%, 80%, and 90% from 2004 - 2013. B) pH values at relative humidity of 72%, 74%, 76% and 78% from 2004 - 2013 C) pH values at relative humidity of 82%, 84%, 86% and 88% from 2004 - 2013.</figcaption>
</figure></center>

The relative humidity at 78% represents the water activity coefficient, which is the ability for high concentrations of water molecules to enter the particulate phase, in order for the system to have a linear relation between the acidity and ion concentrations.

Our study only covers the interactions with the particulate phase, thus much consideration is placed on understanding the partitioning of water molecules. Relative humidity values are set higher than the average for Georgia Station thus values do not represent the real system. However knowing the strong dependence on relative humidity, we have a better understanding of how to model atmospheric acidity in the future.


## Methodology 

### Measurement and Data 

Dry deposition samples were collected weekly by the Clean Air and Skies Network using ion chromatography and coupled plasma-atomic emission spectrometry. The two parameters of interest were strong acidity (equation 1) and the neutralization (equation 2). Concentrations of Na+ and Cl- were available after 2004, thus calculations for the full 20 years (1990-2010) were done without Na+ and Cl-.

Strong acidity:
<figure>
	<img src="/assets/img/Article_UANAID/Equation_1.png">
</figure>

Neutralization:
<figure>
	<img src="/assets/img/Article_UANAID/Equation_2.png">
</figure>

Changes in strong acidity and neutralization were calculated by the Theil-sen slope estimator [v], which calculates the changes of all possible combinations of two ordered-points. An estimation of the slope is calculated by the sum of the scores; +1 when there was in an increase, -1 when there is a decrease and 0 when there is no change. This methodology reduces noise and extreme values.

### E-AIM Analysis

Ion concentration from Georgia Station from 2004-2013 was processed using the E-AIM (Extended Aerosol Inorganics Model) [4]. The concentration of H+ (equation 3) was determined to be the ionic equivalent to balance the charges in the system. The model’s outputs were activity coefficients, µ, and molar fractions, n, which were then used to calculate the pH of the system (equation 4).

H+:
<figure>
	<img src="/assets/img/Article_UANAID/Equation_3.png">
</figure>

pH:
<figure>
	<img src="/assets/img/Article_UANAID/Equation_4.png">
</figure>


## Acknowledgment 

Assistance from Professor Murphy and Alex Tevlin is greatly acknowledged and appreciated.


[Back to Research](http://janicetang.com/research/){: .btn}     
[Meet The Team](http://janicetang.com/meet-the-murphy-team/){: .btn}


## Reference

i)U.S. Environment Protection Agency (2013) The Clean Air Act Amendments of 1990. Epa.gov/oar/caa/caaa_overview.html, Office of Air and Radiation Communication Office UP EPA. Washington D.C., August 2013. 

ii)Holland, D. M., Principe, P. P., Sickles, J. E. II. (1999) Trends in atmospheric sulfur and nitrogen species in the eastern United States for 1989-1995. Atm. Env. 33, 37-49.

iii)Major Uses of Land in the United Sates, 2002. EIB-14. Available from Economic Research Service, USDA United States Department of Agriculture.

iv)E Aim (Extend Aerosol Inorganics Model) (2013) Extended AIM Aerosol Thermodynamic model. www.aim.env.uea.ac.uk/aim/aim.php(accessed 15 March).

v)Theil, H. 1950. A rank-invariant method of linear and polynomial regression analysis. Proc. Kon. Ned. Akad. V. Wetensch. A, 53, 386-392, 521-525, 1397-14-12.
