---
layout: post
title:  "Fall 2022 Erdos Institute Project"
date:   2022-12-13 11:14:00 -0400
categories: jekyll update
---
I recently finished my second [Erdos Institute][erdosinstitute.org/] Data Science Boot Camp. During the boot camp I completed a small group data science project using synthetic data supplied provided by CoverMyMeds.

The primary goal of the project was to predict patient copay for a prescription drug given a data set of approximately 14 million pharmacy claims over the year 2022. As part of the claim process the amount that the payer reimburses the pharmacy and copayments required of the patient are set by complicated negotiations and contracts between the drug manufacturer, the payer, and the pharmacy. Those negotiations also often cover decisions on what drug claims will ultimately be approved (preferred / non-preferred / non-covered formulary status of each drug) based on the relative discounts that the payer can secure relative to other drugs in the same class that may treat the similar types of medical conditions.

The project was particularly challenging in that the dependent variable is continuous whereas all the independent variables are categorical.

<iframe src="https://docs.google.com/presentation/d/e/2PACX-1vTV_l82lixu2_W9YfE3_KGSOCCtOPhDDSjCsjBeQy69OmPIPyhP_pUkfWaOSNiK3YVDiuTB9ymQDH4J/embed?start=false&loop=false&delayms=30000" frameborder="0" width="960" height="569" allowfullscreen="true" mozallowfullscreen="true" webkitallowfullscreen="true"></iframe>