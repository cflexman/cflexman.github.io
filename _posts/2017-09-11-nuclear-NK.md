---
layout: post
date:   2017-09-11
title:  "North Korean EMP attacks still unlikely"
permalink: nuclear-NK
categories: predictions, risks
comments: true
---

Whatever my other conflicting desires, I am incredibly serious about not wanting my friends to die. So should we as individuals be taking any action for personal safety in response to recent news about North Korea hitting new nuclear weapons milestones?

The short answer is probably not. You should definitely not leave the West Coast. You could make a simple necessities stockpile or start learning basic survival skills for a post-EMP world if the opportunity cost is very low and it makes you feel better. I will probably not do these things. I may consider taking a stay in Australia if Kim Jong Un suddenly switches from appearing to act rationally to appearing very disturbed or irrational. I may revise these decisions based on new information from others. Skip to Section IV for a barely extended version of the conclusion.

I. Capabilities

With the advent of ICBMs that can go ~6000 mi, DPRK suddenly has a lot of potential targets. That is roughly the entire northern hemisphere plus Australia. It might need a bit further to reach the Eastern Seaboard, but it's basically there. 

Before it can hit most of these targets, they'd have to create a re-entry vehicle, get better at aiming, and perhaps get better at miniaturizing (though it looks like they're mostly [done][miniature] [there][min-fus]). I think it only needs the last to target Seoul with nuclear-tipped short-range ballistic missiles. None of these three are especially difficult, and they can all be worked on in parallel (unlike the development of larger and larger bombs). Further, DPRK's recent progress has been very quick, possibly due to outside technical help from Iran or other actors.

The possible warheads on these missiles are fission bombs, fusion bombs, and bombs tailored to produce a large electromagnetic pulse (EMP). The last will be discussed in the next section.

Fission bombs can range from about .5-[500 kt][ivy-king], whereas fusion bombs are more typically .1-[50 Mt][tsar-bomba]. Large fission devices can destroy a small city, large fusion devices a large city. Different effects of the bomb scale at different rates, but a quick rule of thumb is that blast radius tends to scale at something like the cube root of the tonnage. This means a bomb that is 1000 times as strong will only have a blast radius ~10x the original (10 times as strong, only 2x the blast radius). You can look at example sizes with [this convenient map][nukemap].

[DPRK has tested][test-list] several small fission bombs in the last decade (1-25 kt) and likely just tested their first fusion bomb (~200 kt). They will soon have enough material for about 30 fission bombs, but I don't know the number of fusion bombs. Making significantly larger bombs will obviously require more engineering and more fissile material, but again, progress has been quick.

II. EMP outcomes

On the other hand, [EMP attacks][NEMP] would be really bad.

These are qualitatively different and would require only miniaturization, which is again likely complete. An EMP strike consists of a warhead luanching to high-altitude and detonating outside the atmosphere, allowing the EMP to hit everywhere up to roughly the visible horizon. This means almost all of the United States with one warhead. They might have to do some work to make a high-EMP device, but you can essentially use a standard fission device with slight modifications—a fusion bomb isn't even very helpful.

All nuclear warheads produce an electromagnetic pulse upon detonation, because the nuclear reactions create a large number of gamma rays that ionized the surrounding air and release a large number of extremely high-energy relativistic electrons. Skipping over the steps where they get trapped in the Earth's magnetic field and produce large amounts of synchrotron radiation, this giant electric storm hits the ground and causes fields in the range of tens of kV/m, enough to induce absurd currents in all unshielded electronics and even many shielded ones. 

Computers are made of logic gates; logic gates are made out of transistors; transistors are semiconductors; semiconductors are only supposed to semi-conduct; once you force them to conduct multiple amps, most of them will never work again. Other things that will get fried include switches, resistors, wires, shielding, etc. Things that can attenuate the fields include distance, large structures, shielding, and other electronics. Strong resistors may require fewer of these measures, but in general only very dedicated shielding or some strong combination of the above can save sensitive microelectronics.

Unfortunately, our national infrastructure is entirely dependent on sensitive microelectronics. A [report from 2008][EMP] detailing the likely effects of an EMP attack highlighted the importance of Supervisory Control And Data Acquisition (SCADA) systems: basically, the small computers, sensors, and actuators controlling water valves, electric plant parameters, car engines, manufacturing capabilities, food production equipment, etc. If an EMP destroyed a significant fraction of microelectronics in the water system, there would be flooding, aqueduct damage, etc. In manufacturing equipment, our factories would grind to a halt. In food production equipment, yields would become a fraction of their current amount. In engines, there'd be no way for most of the populace to get to work, food to get distributed, etc. In the power grid, large portions of the country without electricity. This would leave shielded electronics useless as well. Even generators often have controlling circuits nowadays.

(In retrospect, it probably wasn't a great idea to have a single point of failure affecting every important infrastructural component AND the backups when we know that point [will occasionally fail][Carrington].)

The question essentially becomes how quickly this can all be repaired. It doesn't look great for us: many of these components have lead times on the order of a year, and even if they wouldn't be sourced from now-crippled U.S. factories, yanking a fifth of the gross world product may cause significant disruptions to global plants. I'm not sure exactly how globalized we've gotten yet, but people say it's a lot. If electric plant emergency shutdown circuits are destroyed before the shutdown takes place, then everything else will get fried, requiring a near-complete overhaul before it would again be functional.

A lot of things could happen here. The world could band together to give supplies to a country in crisis. We might have enough dedicated engineers to fix the critical parts before we descended from rioting into full anarchy. The damage might be less than expected for some physical reason. Even in its 200 pages, the report mentioned doesn't really give many useful quantities for Fermi estimates here. I'd be excited if anyone had a better resource on the matter—did Nick Beckstead or someone look into similar catastrophic risks a while back?

One hopeful note here is that this report was from 2008. It's possible that the government has been functional enough since then to convince, regulate, and subsidize our way into having critical infrastructure resistant to EMPs (it's a thing you can do with enough money). The government does tend to be more proactive about defense spending than most other things.

The other important thing to note is that an EMP attack won't be able to take U.S. nuclear missiles off-line (or the Cold War would have ended very differently).

III. Motivations

Just because DPRK could wreak havoc with their arsenal doesn't mean they will. The most important part of forecasting politics is to look at what the most powerful actors want.

Unfortunately, discerning Kim Jong Un's motivation has been quite difficult due to negligible unclassified intelligence. From the state-level view, potential additive reasons for them to acquire nuclear weapons are:
- Continue the vital narrative around the U.S. being the great enemy, which justifies centralization
- Domestic respect
- International respect
- International diplomatic acknowledgment
- Actual defense from U.S. invasion and regime change analogous to Qaddafi or Hussein
- Deterrent to cover smaller aggressions
- Credible blackmail for economic or financial bounty
- Use arsenal for attack

Actual defense from U.S. regime change, the narrative of "U.S. as enemy", and perhaps international/domestic respect all seem relatively likely as primary motivations. In some of the few communications with their regime, they stated the reason for the arsenal as defense from the fates of Hussein and Qaddafi, and directly believing explicit statements of intent from deranged autocrats has been working pretty well in the prediction booth lately.

[A 2015 report][DPRK] looks at potential motivations and concludes that their motivations have evolved over time. The first motivator was diplomatic concessions, the next was catalyzing cautionary intervention from actors like U.S. and China in the Korean conflict, the current motivator is assured retaliation, and the next phase would be actual war-fighting capability. I don't really understand the second, and the fourth seems like a continuation of the third, but the other two match up with my guesses above. This report leaves out the potential desideratum of respect, which may not fit under structural realism but seems to be a real influence in the world.

A last angle to look at this is from the perspective of opportunity costs. If you're leading a rogue state—which I really hope you're not—you might not have a lot going for you in the whole IR department. As a ruler, you want to be secure from internal and external threats. For many states, this means being nice enough to your citizens and other states that everyone wants you to remain in power. But once you're rogue and have minimal economic ties and no one wants you in power, you don't lose a lot from going full rogue and closing your borders completely, and it allows you to both minimize enemy intelligence and implement full news censorship—strong security improvements against both external and internal threats. And once you're there, nuclear weapons provide a strong deterrent against regime change, with little increased chance of being invaded or nuked since you have South Korea hostage and no increased chance of being assassinated because no one can cross your border. Finally, if your only trade possibility is the black market, nuclear weapons plans are easily the highest-cap economic possibility. It looks like Iran and North Korea might have a partnership set up that minimizes cost for North Korea or even allows them to export technology. And if there is remaining cost from weapons, it's probably significantly defrayed by the increased tax rates available when your nation has an outside aggressor.

In this scenario, Kim Jong Un is still entirely selfish and holding both his own and other populations hostage under the threat of nuclear annihilation. But he might not be insane to do so—merely following the gradient of cost-effective strategy. And cost-effective selfish strategy definitively breaks down if you get yourself nuked, so I think MAD will still easily work on Kim Jong Un unless he is way crazier than I think. The most powerful actor clearly wants to stay alive and ruler, and I think that motivation is strong enough to provide guarantees up to the background rate of insanity (and likely further if his generals and inner circle actually see insanity setting in and can stop him from getting them all killed). 

From the side of the U.S., having Seoul get annihilated by ordnance has so far been a higher cost than they are willing to take to stop DPRK from being able to target the U.S. mainland with nuclear weapons. If the U.S. leadership generally believes that Kim Jong Un is following rational incentives and the endgame will never involve the actual use of these weapons, this is somewhat reasonable. DPRK may be able to make more economic demands or something, but isn't in a position to cause real damage.

The only way this could go awry is if something weird happens with MAD. I'm pretty sure that even Trump is generally a very strategic and selfish rational actor, but I'm not more than 99% sure that he won't do something extremely dumb having misread a brief or created some crazy escalation via a half-deleted tweet. 

IV. Conclusions

From my current vantage point, I would put the odds at a 1.5% chance of a purposeful nuclear exchange with DPRK during the Trump presidency, and lower than this with future presidents. Affirmation by others and those with IR experience might make me more confident, thoughtful disagreements may make me less so, and answers or resources pertaining to the questions at the bottom may go either way.

The chance of an accidental exchange from our extensive missile systems and early warning detection was estimated at about 1%/yr during the Cold War (with a really impressive [near-miss list][FLI]), but I don't think the DPRK situation increases our odds of accidental nuclear exchange from whatever they already are with Russia (hopefully lower than 1% with technological improvements). 

If we did have a purposeful or accidental exchange with DPRK, it seems likely that we could shoot down any U.S.-targeting missiles if the attack occurs while they still have few warheads. The missile shield is complex and I don't have very good information.

The odds of an EMP attack in a nuclear exchange seem high, significantly more likely than a conventional attack on a single city other than Seoul. This is based both on their threat of the same and the high damage it would cause. By the time DPRK has a larger arsenal of weapons to consider hitting multiple targets, they will also likely have the range to hit any target in the U.S. This is why I wouldn't expect the West Coast to be worth evacuating.

These conclusions may change if Kim Jong Un shows psychological problems or wild abandon for personal safety in an actual irrational sense and not a crafted partial-escalation for bargaining sense. I might advocate a brief stay in Australia rather than learning survival skills, but it depends on how long the situation looks like it will go on. You could be one of the lucky Hunger Games victors!

Semi-open questions:
- How much infrastructure is now EMP-resistant?
- Any better resources on the likely outcome of much of our electronics getting fried?
- Is Kim Jong Un crazy enough to fail the MAD test?
- What are DPRK's motivations in developing nuclear weapons?
- How good is our missile defense? Getting mixed reports about Aegis being great, Patriot being abominable, and THAAD being ok, especially for high-altitude EMP missiles

[test-list]: https://www.wikiwand.com/en/List_of_nuclear_weapons_tests_of_North_Korea
[ivy-king]: https://www.wikiwand.com/en/Ivy_King
[tsar-bomba]: https://www.wikiwand.com/en/Tsar_Bomba
[nukemap]: https://nuclearsecrecy.com/nukemap/
[miniature]: http://www.npr.org/2017/08/08/542286036/north-korea-has-miniaturized-a-nuclear-warhead-u-s-intelligence-says
[min-fus]: http://www.thedrive.com/the-war-zone/14051/north-korea-shows-h-bomb-warhead-design-says-it-will-use-it-in-emp-strike
[NEMP]: https://www.wikiwand.com/en/Nuclear_electromagnetic_pulse
[EMP]: https://works.bepress.com/george_h_baker/17/
[Carrington]: https://www.wikiwand.com/en/Solar_storm_of_1859
[DPRK]: http://uskoreainstitute.org/wp-content/uploads/2016/02/NKNF_Evolving-Nuclear-Strategy_Smith.pdf
[FLI]: https://futureoflife.org/background/nuclear-close-calls-a-timeline/