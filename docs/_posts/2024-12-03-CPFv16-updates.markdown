---
title:  "CPF v.1.6 – what’s new?"
date:   2024-12-03 09:04:04 +0100
categories: update
---

Small updates to the v.1.6 code:

1.	A correction of the code for kidsn_hh_34 and kidsn_hh_04 in Korea and Russia – variables were showing wrong counts 

2.	Parstat in US and KOR was removed because cohabitation cannot be identified. In US it cannot be well assessed for the current code’s logic (especially for spouses in the HH in ‘href’). 

3.	PSID – correction for kids_hh_04: Values 0 (no kids) from ‘youngest HH member’ were not properly recoded in kids_hh_04, resulting in underestimation of kids_hh_04==0 (no kids). 

4.	UK – HH income
   
•	Now there are two variables: hhinc_pre (gross) and hhinc_post (net)

•	hhinc_post was changed to hhinc_pre (a wrong source variable was used)

•	a propper hhinc_post was added 

