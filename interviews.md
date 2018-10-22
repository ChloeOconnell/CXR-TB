# Interview notes

Clinical applicability interview notes, week of 10/22/2018

# Matthew Lungren, M.D. (clinical mentor)

## Big picture / long-term game plan
Overall, one big thing to figure out will be when to release/deploy this should we get it working satisfactorily. It'll be a question of balancing the good it can do (i.e. faster diagnosis/faster treatment for pts with HIV in the developing world) with potential harm (misclassification/incorrect diagnosis). This will be something that we can ask for help on from our clinical partners in South Africa and elsewhere - if we get a good enough model, we can then give it to them for prospective validation. 
## How to proceed
- Can predict cavitation and lymphadenopathy – both are variables in Niel’s dataset. Should start with Niel's dataset bc that'll be easier, and then can eventually move to Tom's
- Later, predict ground truth (i.e. PCP vs. TB vs. PNA)
- Once we have a model, we can explore whether clinical info (i.e. O2 sat, etc.) helps the model performance
- Final step: Evaluate cases in which the model was wrong. Could be that sputum culture was terrible, but clear evidence on CXR
## Data processing / photo of CXR issue 
- Remember when writing up the paper that if choose to use Tom's data, these are photographs of films on screens – we need to address the issue of determining that the model performs similarly on the actual images
## If things don't work out: Back-up project
- Intermountain health: Prescriptive healthcare
- To diagnose PNA, they just do a CXR & look for only 3 things: opacities, effusions, feeding tube
-	Could try to detect those 3 things, which could save them a lot of time/money


# Nathan Lo, Ph.D. (has served as an advisor on the World Health Organization: Neglected Tropical Diseases panel)
Informal interview - main topic of discussion was variable selection. For maximal clinical utility, it will be interesting to compare accuracies with and without clinical info (i.e. for PCP, O2 sat will likely be very important, but can also sometimes be difficult to obtain in a low-resource setting. As a result, getting a quantitative idea of how much it helps the model can help guide whether or not to include it)

