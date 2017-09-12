---
layout: post
date:   2017-08-15
title:  ""
permalink: 
categories: predictions
comments: true
---

IARPA and their academic partners have a [new forecasting tournament][HFC]. But there's a twist this time: they've come to grips with our cyberpunk future and have assigned you the obligatory AI sidekick.

If you're interested in participating in the Hybrid Forecasting Challenge (HFC), go sign up and do the ~1 hr questionnaire before you continue reading (spoilers ahead).

------

I.

Their questionnaire collects the standard data on you: an IQ proxy, a quantitative intelligence proxy, attitude toward thinking, attitude toward changing your mind, and *something else*.

The *something else* is a bit confusing. There are 50 geopolitical questions for which you have to assign an answer (T/F) and a probability that that answer is correct (and of course they ask you not to look up the answers). These are statements like "Brazil had the lowest GDP growth of any country in South America in 2016."

This looks a lot like the standard calibration test to determine level of overconfidence. But it could also be used to simply test geopolitical knowledge, or both of these at once, or some other devious purpose I can't think of. But the question of what this geopolitical calibration test is trying to test for is a little important, because I'm pretty sure there's a large confounder no matter the aim.

II.

Let's start with the question about Brazil.

I'm estimating P(Brazil GDP growth lowest in South America 2016 | K), where K is all background knowledge that I have. My job as a forecaster is to draw on all the info K that I have stored in my head, choose the most relevant pieces, and bring them together to form an estimate for the probability the statement is true. So I start pulling things from K to make an estimate: 

* I can think of 13 countries in South America, and it feels like I got almost all of them, so I'm guessing only 13 or 14: this yields about a 7.5% base rate per country (ETA: turns out there are only 12 countries—French Guiana is a territory)
* Brazil was one of the fastest-growing economies in the world a few years ago
* Brazil was about to host the Olympics and probably did so in 2016
* there was a whole lot of corruption during the build process for the Olympics
* the build process involved several different cities and a bunch of huge stadiums, where it seems likely that a stadium would cost between $500m and $10b, totalling perhaps up to an upper bound of $100b
* Brazil's GDP must be around ~$3t if they have a similar population to the US and a GDP per capita similar to Mexico, so $100b would be on the order of magnitude of 3% of GDP. If they spent that over only 2 years previous to the Olympics, then stopped cold turkey just before 2016, the max it could drop from this effect is 1.5%; if they were at about 4.5% growth prior to this effect (somewhere above a good 3% growth rate but below a crazy 7% growth like China lies about) then the mean would be about 3%, which puts it about where I'd expect the mean of South America is and still leaves less than a 7.5% chance. This is still using my conservative estimate, so it should be significantly lower, maybe about 1% 
* the Olympics usually bring in a ton of tourism which is why everyone competes to host it, aside from the glory
* I have to admit that the unknowns with the Olympics bring a whole lot of volatility into my analysis, and there is still a chance that the Olympics did something extremely weird to their economy that year: because of this ~10% chance of huge GDP drop and ~50% chance this results in a last-place GDP growth finish in South America, I'll increase my odds by about 5%
* I didn't hear anything about Brazil doing poorly economically in the last year during the Foresight tournament when I was looking at a variety of econ stuff
* they are asking this question

All the quantitative economic considerations yield about a 6% chance that Brazil's economic growth was lowest in South America. But the last bullet point just torpedoes the rest of the analysis.

Eliezer Yudkowsky always talks about how most of the informational work in a prediction goes into promoting the right hypothesis to attention out of all the possibilities. If someone is looking for buried treasure and they point over yonder and say, "What if we try digging there?", you'd expect that to have an absurdly miniscule chance out of all the locations in the world—unless there was a large amount of evidence favoring that location over any of the others. If the prospector doesn't have any evidence and digs anyways, they would be committing the fallacy of [privileging the hypothesis][PTH]).

On the other hand, if someone comes up to you and says, "do you want to make a bet that there is a blue rock with an X painted on it buried right over there?" and offers you odds of a million to one for, you might not want to calculate out that the chances are 10^-14 and take up their bet excitedly. By offering the bet, they are giving you strong information that there is indeed such a rock there. There is an "adversarial" nature to betting: bettors try to find specific questions on which you are badly calibrated or have poor information relative to them, similar to a dynamic selection bias for your weak spots.

Like in betting, the fact that HFC is asking this question about Brazil's economy provides information that should change your probability estimate. They are promoting it to attention over the other countries in South America, and now you have to decide how much to weight that fact. Did they really roll a die and choose a uniformly random country to ask about, or did they choose a country in which something notable happened?

In general, the latter strategy is "adversarial" on their part—systematically causing you to give wrong answers if not corrected. Notable events tend to be ones that have low probability assigned to them beforehand. Then if a sample of questions is weighted toward notable events, your answers will systematically underestimate them (be overconfident that they won't occur), unless you correct for this unknown sample bias.

In my analysis, I tried to partially correct for this by considering past questions they'd been asking, and figuring out how random those were. It's really hard to tell, because I couldn't look anything up and find out whether the questions were non-random or not—and the few that I could positively identify as non-random then left me guessing whether only those 10% were non-random or whether the rest were the same.

Ultimately, I had to put about a 30% chance on the question being non-random, and 50% chance on it being true if non-random, so after multiplying these I added about 15% to my original 6% probability. The rest of the analysis hardly mattered compared to the adversarial consideration.

And it turns out that Brazil had -3.5% GDP growth, but Suriname had -7% or something and saved me, which looks an awful lot like their question wasn't random after all.

Of course, you could just argue that this is part of a good forecaster's job, to take into account unknowns like whether the question is random and update accordingly. But the sub-analysis of whether the question is random almost swamps the effect from the original analysis. In the problem above, my estimate would have changed by 50% depending on whether I assumed the question was fully random or fully non-random. This is on the order of the full range available, 2.5x the range I would have considered plausible, beforehand, and 5x what the rest of my analysis was considering!

This is not an airtight argument about these kind of non-random questions being included, but there are a few other effects that add to it in a concerning way.

III.

Another example: "Iran has ended its territorial dispute with the United Arab Emirates concerning three islands in the Persian Gulf."

This one's a mess—I didn't know this was happening, wouldn't have known if it was happening, etc. Seems like a lot of territorial disputes I hear of have been going on for ages, but it's also likely that I only hear about ones that have been going on for ages. The doomsday argument says that from a position of ignorance (which I am definitely in here), something is about 50% likely to end in the next interval of equal length to its current lifespan. In this case, that means if there was a 5-year dispute, it would only have 50% chance of ending in the next 5 years. And since I have to update against the fact that they are asking this question, I'm going to assume the dispute would have ended in the last two years, so if the original dispute started more than 5 years ago it's unlikely it would have ended... but on the other hand, them asking the question means it's notable, so maybe there is closer to a 50% chance. Anyways, I was probably about to put 40 or 50% confidence.

But, you may have noticed, there are a few extra details tacked on here, and we've been taught to always [beware of those][BD]. What if the dispute only concerned two islands? What if they were in the Indian Ocean? What if the UAE's dispute was with Iraq and not Iran?

I think I ignored this possibility and assumed the question was about the main dynamic and not about all the random other questions. But later in the questionnaire was this statement: "Scientists have calculated that only 35% of the Great Barrier Reef has been "bleached" and is currently at a high state of health." Being bleached is, of course, as bad for coral as it is for humans and everything else, so this is evidently false. But this question is absolutely trying to trick us with a detail, the meaning of the word "bleached".

If I had adjusted out for possible tricks in the Iran/UAE question, I might have ended up with like 30% confidence. But this, too, is hard to adjust for. I hadn't sen the Great Barrier Reef question yet and didn't know how much likelihood to put on definitional tricks. Further, a lot of questions have this many possibilities for tricks, but some feel more adversarial than others. One was "Japan, China, and South Korea dispute sovereignty over the Senkaku Islands." Another: "Since 2014, Kurdish peoples have been fighting as part of the [Pengwar-Kurdish] militias against ISIS, primarily in Northern Iraq." (The last one is from memory and I don't remember what the type of militia was named—probably not "Pengwar-Kurdish.")

This opens a Pandora's box of issues in adversarial testing: is the base rate of questions a uniform 50% true? If so, I should be giving the Iran/UAE question 50%, but if not and we're supposed to be adjusting out for tricks, this will burn me. And it seems like main clauses are about 50% but tricks are less likely—is this true, or should I be penalizing details at 50% too? But how do I even classify details and tricks compared to main clauses? Some statements sound like they only provide details for context to the main implied question, whereas others have details that read specifically like extra propositions. The "primarily in Northern Iraq" piece tacked on the end of the last question seems especially suspicious in this regard. Should I be worried about the "2014" addition as much as I worried about the definition of "bleaching"? 

IV.

Again, both non-random question selection and the burden of distinguishing truthfulness of details could be said to be part of a forecaster's duty. 
Unfortunately, even if you did want to test for these things, this probably isn't the way to do it.

With the original test, you can use the Brier score as a proxy for geopolitical knowledge. And you can straightforwardly test calibration/overconfidence by ensuring about 70% of questions given 70% confidence are gotten right, etc. These don't get in each other's way, and provide strong quantified estimates of the participant's epistemics.

On the other hand, these 



Nonetheless, they add enormous amounts of variance to the test compared to the underlying knowledge. For many of the questions, I was moving my answer more by trying to update on the algorithm of the question-selectors than I was from my analysis of the geopolitical questions themselves. I would very roughly estimate that about 50% of my variance was from fundamental analysis, 30% was from the evidence of the question being asked, and another 20% was from details and various other adversarial considerations. 





Let's assume for now that the primary aim of these questions was to determine geopolitical knowledge and/or calibration and overconfidence on generic factual questions.

In this case, not only 




One Simple Trick





[HFC]: https://intake.hybridforecasting.com/conditions/me
[PTH]: http://lesswrong.com/lw/19m/privileging_the_hypothesis/
[BD]: http://lesswrong.com/lw/jk/burdensome_details/



Since 2014, Kurdish peoples have been fighting as part of the Pengwar-Kurdish militias against ISIS, primarily in Northern Iraq. 

Brazil had the lowest GDP growth of any country in South America in 2016.

Azerbaijan and Armenia have formally settled their border dispute. (I put 50%)

Algeria has experienced a revolutionary overthrow of its government in the last 5 years.

Iran has ended its territorial dispute with the United Arab Emirates concerning three islands in the Persian Gulf.

Japan, China, and South Korea dispute sovereignty over the Senkaku Islands.

Scientists have calculated that only 35% of the Great Barrier Reef has been "bleached" and is currently at a high state of health.





