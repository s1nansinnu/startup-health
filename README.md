# startup-health
the  task is i need to give score to startup based on their features in the csv 
file for handling csv file and calculation i need pandas and numpy
after that i need to analyse the dataset and normalise.there is two part for normalisation the 
some attributes are higher better and some are lower better, for that i separated them,only spending is high it is not better other are higher better
for min max normalisation i used min max normalisation formula for all features except monthly burn rate for this used invert the normalisation after doing normalisation for amking equal
now i need to give weights to all features basedon the relevance of them, here team experience 15 beacause experienced are better for them
market size- it has many oppurtunities
monthly active userrs-it is most important and shows the startup values,
for monthly burn- more spend shows hey can easily shut,fund raised-they can raise fund as many want it is not always useful,
valuation- shows how much valued is them in their industry
for giving score ,multiply the normalised values and their respective weights and add each of them then multiply the sum with 100 and add a rank column to show rank
the start  up 6 rank high because it has 10 years of experience it is the highest and active users are highest among other startups we gave high weightage to active users also donot have high burn rate which also good and other features are average it is not the lowest among others
for the 100 rank startup 55 it has 10 years of experience but active users is low and monthhly burn rate is high other features are low comparedto other startups
then visualized the corelation between  features and  shows the bar graph for startup ranks
