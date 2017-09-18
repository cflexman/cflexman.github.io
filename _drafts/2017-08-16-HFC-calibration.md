---
layout: post
date:   2017-08-15
title:  ""
permalink: 
categories: predictions
comments: true
---

IARPA and their academic partners have a [new forecasting tournament][HFC]. But there's a twist this time: they've come to grips with our cyberpunk future and have assigned you the obligatory AI sidekick.

If you're interested in participating in the Hybrid Forecasting Challenge (HFC), go sign up and do the ~1 hr questionnaire before you continue reading (study-affecting spoilers ahead).

------

###I.

Their questionnaire collects the standard data on you: an IQ proxy, a quantitative intelligence proxy, attitude toward thinking, attitude toward changing your mind, and *something else*.

The *something else* is a bit confusing. There are 50 geopolitical questions for which you have to assign an answer (T/F) and a probability that that answer is correct (and of course they ask you not to look up the answers). These are statements like "Brazil had the lowest GDP growth of any country in South America in 2016."

This looks a lot like the standard calibration test to determine level of overconfidence, combined with a test of geopolitical knowledge. That's fine: you can probably combine these into one test, since resolution can be tested separately from calibration. But a third factor looks like it will muddy the waters on both of these metrics.

### II.

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

Eliezer Yudkowsky always talks about how most of the informational work in a prediction goes into promoting the right hypothesis to attention out of all the possibilities. If someone is looking for buried treasure and they point over yonder and say, "What if we try digging there?", you'd expect that to have an absurdly miniscule chance out of all the locations in the world—unless there was a large amount of evidence favoring that location over any of the others. If the prospector doesn't have any evidence and digs anyways, they would be committing the fallacy of [privileging the hypothesis][PTH].

On the other hand, if someone comes up to you and says, "do you want to make a bet that there is a blue rock with an X painted on it buried right over there?" and offers you odds of a million to one for, you might not want to calculate out that the chances are 10^-14 and take up their bet excitedly. By offering the bet, they are giving you strong information that there is indeed such a rock there. There is an "adversarial" nature to betting: bettors try to find specific questions on which you are badly calibrated or have poor information relative to them, which you could call an anti-inductive system or a dynamic selection bias for your weaknesses.

Just as in betting, the fact that HFC is asking this question about Brazil's economy provides information that should change your probability estimate. They are promoting it to attention over the other countries in South America, and now you have to decide how much to weight that fact. Did they really roll a (13-14 sided) die and choose a uniformly random country to ask about, or did they weight by population, or did they subjectively choose a country in which something notable happened?

In general, the last strategy is "adversarial" on their part—systematically causing you to give wrong answers if not corrected. Notable events tend to be ones that have low probability assigned to them beforehand. Then if a sample of questions is weighted toward notable events, your answers will systematically underestimate them (be overconfident that they won't occur), unless you correct for this unknown sample bias.

In my analysis, I tried to partially correct for this by considering past questions they'd been asking, and figuring out how random those were. It's really hard to tell, because I couldn't look anything up and find out whether the questions were non-random or not—and the few that I could positively identify as non-random then left me guessing whether only those 10% were non-random or whether the rest were the same.

Ultimately, I had to put about a 30% chance on the question being non-random, and 50% chance on it being true if non-random, so after multiplying these I added about 15% to my original 6% probability. The rest of the analysis hardly mattered compared to the adversarial consideration.

And it turns out that Brazil had -3.5% GDP growth, but Suriname had -7% or something and saved me, which looks an awful lot like their question wasn't random after all.

Of course, you could just argue that this is part of a good forecaster's job, to take into account unknowns like whether the question is random and update accordingly. But the sub-analysis of whether the question is random almost swamps the effect from the original analysis. In the problem above, my estimate would have changed by 50% depending on whether I assumed the question was fully random or fully non-random. This is on the order of the full range available, 2.5x the range I would have considered plausible, beforehand, and 5x what the rest of my analysis was considering!

### III.

Another example: "Iran has ended its territorial dispute with the United Arab Emirates concerning three islands in the Persian Gulf."

This one's a mess—I didn't know this was happening, wouldn't have known if it was happening, etc. Seems like a lot of territorial disputes I hear of have been going on for ages, but it's also likely that I only hear about ones that have been going on for ages. The doomsday argument says that from a position of ignorance (which I am definitely in here), something is about 50% likely to end in the next interval of equal length to its current lifespan. In this case, that means if there was a 5-year dispute, it would only have 50% chance of ending in the next 5 years. And since I have to update against the fact that they are asking this question, I'm going to assume the dispute would have ended in the last two years, so if the original dispute started more than 5 years ago it's unlikely it would have ended... but on the other hand, them asking the question means it's notable, so maybe there is closer to a 50% chance. Anyways, I was probably about to put 40 or 50% confidence.

But, you may have noticed, there are a few extra details tacked on here, and we've been taught to always [beware of those][BD]. What if the dispute only concerned two islands? What if they were in the Indian Ocean? What if the UAE's dispute was with Iraq and not Iran?

I think I ignored this possibility and assumed the question was about the main dynamic and not about all the random other questions. But later in the questionnaire was this statement: "Scientists have calculated that only 35% of the Great Barrier Reef has been "bleached" and is currently at a high state of health." Being bleached is, of course, as bad for coral as it is for humans and everything else, so this is evidently false. But this question is absolutely trying to trick us with a detail, the meaning of the word "bleached".

If I had adjusted out for possible tricks in the Iran/UAE question, I might have ended up with like 20-25% confidence. But this is hard to adjust for. I hadn't seen the Great Barrier Reef question yet and didn't know how much likelihood to put on definitional tricks. Further, a lot of questions have multiple possibilities for tricks, but some feel more adversarial than others. One was "Japan, China, and South Korea dispute sovereignty over the Senkaku Islands." Another: "Since 2014, Kurdish peoples have been fighting as part of the [Pengwar-Kurdish] militias against ISIS, primarily in Northern Iraq." (The last one is from memory and I don't remember what the type of militia was named—probably not "Pengwar-Kurdish.")

This opens a Pandora's box of issues in adversarial testing: is the base rate of questions a uniform 50% true? If so, I should be giving the Iran/UAE question 50%, but if not and we're supposed to be adjusting out for tricks, this will burn me. Perhaps in general questions are 50%, but ones with extra details are down at like 25%? Should I be putting a base rate of 50% on every detail, so that any question with a main clause and two details is only 12% likely? This seems like overkill, but since we know they trick with at least some details, I have to penalize some—and multiple details add up fast. And some statements sound like their details are only to provide informational context to the main implied question, whereas others have details that read specifically like extra propositions that could be false. The "primarily in Northern Iraq" piece tacked on the end of the last question seems especially suspicious in this regard. Should I be worried about the "2014" addition as much as I worried about the definition of "bleaching"? 

### IV.

One could make the argument that correcting for adversarial question selection and adversarial detail addition could be said to be part of a forecaster's duty. In prediction markets for example, distinguishing motives of other actors that might corrupt information or markets is vital. If the HFC admins came to me and said this was a thing they meant to test, along with calibration and resolution, I would take issue with the variance it would add to the other two variables but not the aim. On the other hand, I've seen the exact same dynamic on countless true/false tests, and similar dynamics on other prediction tests, so I want this to serve as a warning.

All tests are attempting to quantify some underlying mental ability that you can't observe directly (if you can extract a calibration score from someone's raw neural tissue, let me know). As proxies for this feature, tests won't be a simple function of just the relevant feature: there will be noise, and noise is a label we slap onto all other features that our function depends on which we don't care about. If the test is dependent on a feature that is uncorrelated across each subject's answers, this noise will at least go down proportionally to one over the square root of the number of questions asked. But if the test is dependent on a feature that _is_ correlated across each subject's answers, it will be attenuated slower than this—and in the limit, if it's dependent on a feature that is fully correlated across each subject's answers, it won't be attenuated at all. 

For true/false tests, the _eternal_ failure mode is to have the two exact problems stated previously: adversarial question selection and difficulty in correcting for details. These are specifically bad because they're very strongly correlated across a subject's answers. At some point, you decide how tricky you think the teacher/creator is being with details and with questions that are about specifically rare events, and you apply this factor to every question on the test. (Whether some questions have more details than others is roughly irrelevant. The point is that for each question there is some possible trickiness correction, and though the size might vary per question, the test-takers will tend to make corrections of a similar fraction of this quantity each time, corresponding to the base rate that they've put on the administrator being tricky.)

Administrators need to be very careful with their test formation to avoid contributing a large amount of this noise to tests. Remember from the last two sections that the trickiness factor can in general take events with ~0% probability under normal circumstances to 50% probability, and that three additional details can take an event with a ~100% main clause down to 12.5%. Whatever signal you're looking at in general, these are huge effects. Oftentimes during this battery, I was moving my answer more by trying to update on the question-selection than I was from my analysis of the geopolitical question. Even if test-takers all assign between 40-60% trickiness and the average question has a trickiness factor of 50%, you're still adding in 10% variation to test answers. Many times, assigned trickiness will have a wider interval and other factors will exacerbate this effect.

Most forecasting tests do away with details and don't fall into the adversarial selection trap, but need to be even more careful of correlated variables. If you add 10% variation to answers in a T/F test, you might have people scoring over a 50% range and this effect only contributing a fifth of variance. But if you are measuring calibration in people, having a boost of 10% to all your stated probabilities will give you a terrible score. I haven't seen data on calibration levels of people who have gone through 3 hours of training, but I'd bet they are off by only a _max_ of 10% averaged across categories. Suddenly a 10% variation doubles your variance. And if you are dealing with low-probability events with log-scoring, 10% can be the difference between an 11% guess and a 1% guess, which is 3.5 bits or 10.4 dB if false!

For these reasons, forecasting tests need to be exceptionally careful with undesired features that might be correlated across questions if trying to distinguish other abilities. If the question set includes few fields, are there any important numbers, knowledge of which might be important to a significant fraction of the questions? If so, you may want to make these known to forecasters, if not change the test. If the test involves news-acquisition ability, you may want to make sure they have similar access through paywalls. If the test involves a strict time-limit, you may add noise based on reading/thinking speed or comfort with forecasting; if it doesn't, you may add noise for time available. If the test involves relatively subjective question selection, you want to make sure everyone's on the same page about the selection algorithm. And to avoid one of the most common failure modes, you want to make exceptionally sure that all questions are well-worded and specific enough about resolution criteria that you won't have a correlated factor like "how much will the test-scorers grade toward the letter of the law compared to the intent?".

It's hard to adjust out for everything, as I noted with the timed-test dichotomy. But I do want to make the point that test-design is possibly more important in forecasting than other situations, due to small margins. I want us to _at least_ be cognizant enough of these dynamics to prevent forecasting and calibration tests from getting worse as more actors enter the space. Ideally, we would learn from past failures, raise our bar, and improve as a field.

[HFC]: https://intake.hybridforecasting.com/conditions/me
[PTH]: http://lesswrong.com/lw/19m/privileging_the_hypothesis/
[BD]: http://lesswrong.com/lw/jk/burdensome_details/

