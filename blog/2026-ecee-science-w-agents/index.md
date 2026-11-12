# The Elephant in the Session Room

*Some notes from ECEE 2026*

- Author: Antonio P. Sberna (Research fellow in Structural Engineering, University of Chieti-Pescara)
- Published: 26 September 2026, Berlin, Germany
- Updated: 7 October 2026, 21 October 2026, 8 November 2026
- Web page: https://AntonioSberna.github.io/blog/2026-ecee-science-w-agents/
- Discussion: https://mastodon.uno/@antoniosberna/117530509520232679
- License: CC BY 4.0 (https://AntonioSberna.github.io/license/). Cite as: Antonio P. Sberna, "The Elephant in the Session Room", 26 September 2026, https://AntonioSberna.github.io/blog/2026-ecee-science-w-agents/

---

Five days in Berlin for [ECEE 2026](https://ecee2026.eu/), and what lingers is not a talk but a feeling of unease.
Not because of the science: the science was excellent. Professor Cotton's keynote on ground-motion models in the age of big data was among the most stimulating talks I have heard in a while, and Professor Vamvatsikos confirmed once again his gift for metaphors that are daring and yet pedagogically flawless.[^1]

And yet, wandering through the scattered halls of TU Berlin, I felt something I had never felt at a conference before: estrangement. As if we were discussing everything except the elephant in the room. As if each of us were carrying on with the profession while pretending not to notice what is looming over it. Maybe it is partly where I stand with academia. Not entirely for sure.

## The elephant

A few days earlier, OpenAI had released a proof on Navier-Stokes, one of the Millennium Prize Problems, produced by some 10,000 agents working in parallel.[^2] But try to picture them: 10,000 Ph.D. students working together and talking to each other with perfect efficiency, no pointless meetings, no unanswered texts, no rivalries. I cannot. At ECEE 2026, the main European gathering in earthquake engineering, there were about a thousand of us, ten times fewer.

If agents can take on a Millennium Prize problem, what about us? Let us be honest: much of works we present at conferences like this one is numerical, and almost every step of that workflow[^3] can already be delegated:

* surveying the literature to identify open problems;
* judging which of them are tractable (and important);
* designing the numerical experiment;
* generating the data;
* writing the paper.

Richard Hamming reminded us that *"the purpose of computing is insight, not numbers."* [^4] The uncomfortable question is what remains for us when the machine delivers both.

## First refuge: the laboratory

![Completely off-topic: the candy trolley at the social dinner really appreciated. I want one at my wedding party.](https://AntonioSberna.github.io/blog/2026-ecee-science-w-agents/ecee26_social_dinner_candies.jpg)

The obvious answer is experimental work. Slow, expensive and unglamorous, it has been sidelined for years by an academic economy that rewards volume.[^5] Perhaps it becomes our last stronghold.

But the machine would design the experiment too. We would be left as the material executors of tests conceived elsewhere, producing data on how the world works so that it can be fed to something that understands it on our behalf. How would that differ from any production line? The product is no longer a car or a chair, but a measurement.

## Second refuge: the lecture hall

Then there is teaching, the other pillar of the university, which on this side of the ocean has also been pushed into the background by the same bulimia of scientific production.[^6] Perhaps the academy will return to something closer to its eighteenth-century form: theory, conversation, teaching. Perhaps we will even put the gowns back on to cross the campus.[^7]

But that academy was also deeply elitist. If the production of knowledge is automated, does the university become a luxury, a quiet place where a privileged few contemplate what the machines have found? Is that a renaissance or a retreat?

## Third option: adapt

Discussing some of this thoughts with a CS professor at my university, the conclusion was a familiar one: jobs will be lost by those who fail to adapt, as with the steam engine, the internal combustion engine and computers?

Perhaps. But those technologies extended our hands and accelerated our arithmetic. This one targets the step we always considered ours: deciding which questions are worth asking. The weaver who adapted to the power loom still knew what cloth was for. Will we still know what our papers are for?

In *The Leopard*, Tancredi warns: <em>"Things will have to change in order that they remain the same."</em>[^8] Academia seems to have read the line backwards: everything is changing, and we keep presenting as if nothing had.
Maybe at the next ECEE the elephant will get its own session. It will probably have written the abstract itself.

![The TU Berlin campus on a sunny day: old brick industrial halls on both sides of a cobbled street with tram rails, a cyclist in the distance.](https://AntonioSberna.github.io/blog/2026-ecee-science-w-agents/tu_berlin.jpg)

## Update, 7 October 2026

P.S. A few weeks later came the confirmation: [OpenAI is giving mathematics a thorough beating](https://www.theguardian.com/technology/2026/oct/07/openai-mathematical-findings-concerns). The queen of the sciences, as Gauss called it,[^9] falls first, perhaps precisely because she is the more rigouros: no laboratories, no construction sites, only symbols and a proof checker that drink too much coffee. Next come the disciplines further down the ladder of abstraction: physics, chemistry, mechanics... and structural engineering? When will our turn come? Or, more honestly: are we sure it has not come already, and we are simply waiting for the next shock to notice?

More to read about it: [Is AI the end of math as we know it?](https://www.quantamagazine.org/is-ai-the-end-of-math-as-we-know-it-20261005/)

## Update, 21 October 2026

Just today I listened to the new episode of *The Rest Is Science*. Even a podcast, hardly the slowest of formats, struggles to keep pace with what is happening, which says a lot about how disruptive this is. (That is my comment no. 1.)

A side note: the episode is ___ (candidates may insert their favourite positive adjective here; I have run out of words). I usually listen to podcasts on my commute to the university, but this time I got completely lost in it, and my brain walked me down the street on autopilot. I hope I did not cross on a red light :-). Hannah Fry's explanation of the problem itself is remarkable, accessible to an almost unfair degree. I will leave that part alone, though. The last time I looked at the Navier-Stokes equations was ten years ago, when my hydraulics professor, after a couple of weeks spent setting up the problem, finally wrote them on the board and said something like: *"This is how it works. But we cannot solve them, which is why you are here. This is where my course begins."* My comments are about the second part.

**Unsolicited comment no. 2.** It starts from a brief, almost throwaway remark by Michael Stevens about a superorganism. That is more or less the feeling I tried to describe some aspects in [These Are All English Words](https://AntonioSberna.github.io/blog/2026-on-thinking-differently-screen/): intellectual work is changing shape, and with it the question of who gets credit for what. I plan to develop this properly in a post in two weeks, if the plan holds. Stay tuned.

**Comment no. 3.** At some point they argue that those building these systems do not care about the problems themselves, only about impressing investors. Entirely reasonable, and they make the case far better than I could.[^10] But let me push it one step further, as a question: should we care? Everyone pursues their own interests. These companies are not nonprofit,[^11] yet whatever they find stays with the rest of us. Nobody reheating last night's rice cares that the microwave oven came out of [wartime radar research](https://en.wikipedia.org/wiki/Microwave_oven#History). Nobody asking their phone for directions cares that GPS was built for the [military](https://en.wikipedia.org/wiki/Global_Positioning_System#History). Motives far less innocent than pleasing investors have given us tools we now take for granted.

**Comment no. 4.** On the interpretability of results.[^12] There is a thread here I have yet to untangle: why do we keep writing for humans? Why not separate the knowledge meant for agents[^13] from the message meant for humans who want to learn? The paper sits awkwardly in between. Split it: on one side, condensed knowledge for agents (credited and valued like a paper), on the other, books or short teaching texts, 20, 30, 50 pages of pure theory, written for a human to understand. (A link to a separate post on this will appear here in the next few weeks)

**Comment no. 5 (the last one, I swear).** More of a request. The part where Hannah Fry talks about abstraction really stuck with me. I am in this world to learn, not to confirm what I already think, so reading suggestions on the topic are very welcome. Accessible ones, please: I am not equipped for highly abstract philosophy.[^14]

[Listen on Spotify](https://open.spotify.com/episode/1KwRO8MPsAFMzKrMMvRVqh)

_p.s. to the p.s.: the metaphor in the title is brilliant, and it carries a whole chain of interesting thoughts._

## Update, 8 November 2026

This is the last addendum to this post, I promise. At this rate I should write a post made only of addenda, at least until the next release makes that one obsolete too.

The new batch of AI-written papers that OpenAI has just made [public](https://github.com/openai/math/tree/main/preprints) shows something else. In my view it is the final blow to a sector that everyone already describes as a bubble: academic publishing. Driven by the bibliometric indicators that decide careers and in some way also grants, the number of scientific publications has exploded. In the twentieth century Erdos stunned everyone with around 30-ish papers a year. Today, take a stroll through the CVs on any university website and look at the numbers. I doubt everyone has become as brilliant (and as eccentric) as Erdos. For a few generations now, what counts in academia is no longer what, but how much. I have seen plenty of it in my short career. I will stop the rant here, or I will never finish.

Science communicators, especially in fields closer to the public such as medicine, keep repeating that a single paper is not science. I like to think of the scientific literature as the night sky for a navigator. A single star means nothing to a navigator; on its own, it cannot be read, what you recognise is the pattern, the constellations of brighter and fainter stars that together let you find your way. Even Polaris is found by following the pointers of the Plough. Add a thousand, ten thousand faint stars, and the constellations still hold.

But what about hundreds of thousands, packed so tightly that they blur into one another? How long will the brightest stars remain recognisable? The risk is a sky that turns into a Milky Way[^15]: luminous, beautiful, and useless for finding north.

---

[^1]: I deeply regret never having sat in one of his classes as a student.
[^2]: [The announcement](https://openai.com/index/navier-stokes-solution/). I could not follow it beyond the first lines of the abstract, it still awaits scrutiny by mathematicians, and it has sparked a dispute over credit.
[^3]: See for instance [*Building effective agents*](https://www.anthropic.com/engineering/building-effective-agents), by Anthropic.
[^4]: R. W. Hamming, *Numerical Methods for Scientists and Engineers*, 1962 ([Wikiquote](https://en.wikiquote.org/wiki/Richard_Hamming#:~:text=The%20purpose%20of%20computing%20is%20insight%2C%20not%20numbers)).
[^5]: See for instance [this piece in *Nature*](https://doi.org/10.1038/d41586-025-03623-2).
[^6]: See for instance [this study in *Quantitative Science Studies*](https://doi.org/10.1162/qss_a_00327).
[^7]: [Like Moriarty](https://static0.srcdn.com/wordpress/wp-content/uploads/2022/06/Sherlock-Holmes-meeting-Jared-Harris-as-Moriarty-in-Sherlock-Holmes-A-Game-Of-Shadows.jpg?q=50&fit=crop&w=825&dpr=1.5) in *Sherlock Holmes: A Game of Shadows*.
[^8]: G. Tomasi di Lampedusa, [*The Leopard*](https://en.wikipedia.org/wiki/The_Leopard), 1958 ([Wikiquote](https://en.wikiquote.org/wiki/The_Leopard#:~:text=Things%20will%20have%20to%20change%20in%20order%20that%20they%20remain%20the%20same)).
[^9]: The full quote is [on Wikiquote](https://en.wikiquote.org/wiki/Carl_Friedrich_Gauss#:~:text=Mathematics%20is%20the%20queen%20of%20the%20sciences).
[^10]: They are there, I am here, there must be a reason.
[^11]: One of them was born as a it, but <i lang="la">pecunia non olet</i>.
[^12]: The part on *abc conjecture* and [Mochizuki's claimed proof](https://en.wikipedia.org/wiki/Abc_conjecture#Claimed_proofs), which I read about when it came out (I think I was still in high school).
[^13]: Something like the MCP servers I am starting to use for my research since this year.
[^14]: Someone has always talked me out of buying the <i lang="la">Tractatus Logico-Philosophicus</i> (thank you, Andrea).
[^15]: Something like [this NASA image of the Milky Way](https://apod.nasa.gov/apod/ap240718.html)

