# ml_sandbox
Welcome to my ML Sandbox! 
Dedicated to maintaining my ML &amp; DS skills beyond LLM applications with weekly exercises.

As much of my time is dedicated to LLMs and its related applications, I've realized the importance of maintaining my broader machine learning (ML) and data science (DS) skills, perhaps trying out some ideas and trying to break things. This repository is a personal project aimed at precisely that. 

Here, I commit to maintaining my core data science and ML skills, with a public pledge to produce at least one exercise or mini-project each week.
For most I will at least cover exploratory data analysis, and some form of supervilised learning. 
I will seize opportunities to throw in unsupervised methods, if I'm thinking why not.
I will include one AWS deployment a month. 
I should throw in some other types deployment within 3 months.
After the first month/ first 4 projects, I will use alternative ways of getting data, than generic open source datasets or using a generic API.
I won't use coding assistants. 
NO AUTO ML!
Uploading old university projects won't count towards this commitment, unless I then really change and update them, ie TF1 to TF2 or Pytorch, change the architecture, ie CNN to transformers, try out different hyperparameters.
A secondary objective, if time permits after meeting the the prime aim, describe what I learnt from specific projects and hackathons, what was the problem. What was the solution. Any insights.

Additionally, this it may incidentally serve as a portfolio, as none of the code from my current and previous roles is open source as a matter of contract. 



### Weekly Exercises


#### Week starting 9 April 2024
Dry Beam dataset. 
Basic EDA. Use SVM.
Consider sensitivity to feature scales.
Consider difference in performance with PCA.

#### 3rd Week April 2024
Next project - do a XGBoost, and CatBoost.
Curious difference in timing and performance.
Compare and contrast. 





### Ideas/Notes/To dos/ brainstorm -- Thinking out loud then writing it down 
I will start with small projects and work towards the ones below.
AWS deployments when do - take some screenshots - think of it a a note - reminder - how do to it for later - quick ease of reference but in my words.
Check free tier before using free credits from events.
Don't foget, free Colab GPU as well.

#### CV Project
For another project (not open source), I scaped web assets from wayback machine, using bash and python,
from a url saving the htmls, then parsing to save the relevant web assets within. 
This was somewhat automated, but could have duplication of image assets.
Fix that, use that workflow to scape other data, photos for example and use in a project.
Perhaps grab photos - use as a computer vision / ML project. Ie reverse engineer instagram filter. 
Or add or remove blur. Add colour to black and white. Increase the quality of the image.
Or compress (so actual information loss) and then increase quality - eyeball the difference

#### NLP text feedback
Write about very short text clustering, Australian's using to much slang and acronyms. 
Instead of Global Embeddings or SBERT, Scrap feedback comments from google or something like that.
Use an LLM to create some labels about the comments. Ie length, sentiment. Basic metrics about user
(ie new profile, one post, doesn't mean fake but on average, might be). Also timing. Check what other data.
Try to make a tabular dataset out of this, and classify dodgyness.
Perhaps compare to TF-IDF, topic modelling, UMAP and HDBscan (That would only identify groups - ... curious the difference, but probably not
Curious how would LLMs go, if prompting to evaluate credibility.

#### Custom CV pipeline - of a commercial product.
Ie adobe auto fill using AI... - isn't that hard with open source tools.

#### Knowledge graph ML imputation vs......
Grab a tabular dataset with missing values - or one, that is complete.
delete a bunch of data. 
Apply a couple benchmarking imputation methods. Compare
Convert it to a knowledge graph format.
Apply knowledge graph ML, check with former team what method they preferred.
Also try out GRAPE - compare other methods - to impute these missing values.
https://proceedings.neurips.cc/paper/2020/file/dc36f18a9a0a776671d4879cae69b551-Paper.pdf
Compare the difference in performance.

#### NLP project pre chat gpt3.5
2nd Objective - talking about projects Project I did pre chat gpt3.5 - OCR - to classification pipeline - photo of reciepts, then classify transactions based on expense categories.
Could write about that - could also make a project, OCR (could use AWS texstract), then use an LLM to classify, 
when brand names aren't recognised as products, use an LLM agent to lookup products - could google. Or perhaps whatever BARD is called now, with the right prompt, 
it can summarise what the product is. Could also go to flag / visualise where the spending occured. 
Perhaps scrape product descriptions - have that as a reference.
Personal value here - keeping track of how much I'm making Bunnings rich - and way to monitor what I have and use/ limit waste/ assist with stocktake.

#### Digital twin -
I should have a digital twin of where I put stuff in my shed and laundry. 
At least a paper one.
Thinking in terms of inventory management, space optimisation, also safety re pool chemicals.
Sounds like overdoing it, for context, I'm slowly reniventing my house with my mrs, from flooring, walls, reinforcing patio beams etc. 
Came with a massive shed, a jungle of a front and backyard.
The reciept OCR application hand in hand with montoring and planning with a digital twin - would avoid that pet hate - waste of time and resources.

