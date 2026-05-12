---
title: "The Compute You Can't Buy"
subtitle: "AI infrastructure is the new strategic constraint, and most businesses haven't priced it in."
image: "/images/man-with-servers.jpg"
imageAlt: "Server racks"
readTime: 7
date: 2026-05-11
category: ai-news
---

For most of the last two years, the question business leaders asked about AI was some version of "what should we use it for?" The answer was usually a productivity case, a customer service case, or a thinly disguised content generation case. The unstated assumption underneath all of it was that the compute would be there when you wanted it.

That assumption is no longer safe.

The data center buildout has become the defining commercial story of 2026. [Big tech hyperscalers are projected to spend between $630 billion and $700 billion on AI infrastructure this year alone](https://fortune.com/2026/05/06/ai-data-center-michigan-saline-politics-farmland/). And [McKinsey's latest projection puts total data center capex at roughly $6.7 trillion by 2030](https://www.mckinsey.com/industries/technology-media-and-telecommunications/our-insights/the-cost-of-compute-a-7-trillion-dollar-race-to-scale-data-centers), with about $5.2 trillion of that going specifically to AI-capable infrastructure. Numbers at that scale have a way of feeling abstract. But what they translate to operationally, if you are a CIO at a mid-market firm trying to put a real AI workload into production this year, is that you are no longer competing on cleverness of use case. You are competing for allocation against companies with ten thousand times your purchasing power. And in most cases, you are losing.

## Where the shortage sits

The interesting part about the current shortage is that it isn't really a GPU shortage anymore. Nvidia and TSMC have scaled production fine. The bottleneck has moved upstream to High Bandwidth Memory, the specialized DRAM that every modern AI accelerator needs to function. SK Hynix, Samsung, and Micron control the HBM market between them, and they have collectively committed over $50 billion to new capacity. The problem is that a new memory fab takes 18 to 24 months to build, plus another 6 to 12 months to qualify production, [meaning investments made in 2026 will not produce volume HBM until 2028 at the earliest](https://www.gpunex.com/blog/gpu-shortage-hbm-crisis-2026/).

In the meantime, [lead times for data center GPUs are running 36 to 52 weeks](https://www.vamsitalkstech.com/ai/the-gpu-supply-chain-crisis-what-every-enterprise-cio-must-know-in-2026/). Delivery windows for Blackwell-class hardware have slipped into Q1 2027. And [Microsoft's Azure backlog has reached $80 billion, with power constraints limiting the company's ability to even fulfill the orders it has booked](https://tech-insider.org/big-tech-ai-infrastructure-spending-2026/). The math doesn't work, and the people closest to the math know it.

The downstream effect on enterprise buyers is the part that matters for anyone reading this. [Microsoft, Google, Meta, and Amazon placed multi-billion-dollar forward orders for Blackwell GPUs in 2025, consuming most of Nvidia's available allocation capacity through the end of 2026 and into 2027](https://www.spheron.network/blog/gpu-shortage-2026/). Mid-market and enterprise customers who used to be able to buy through standard channels are finding reserved pools locked behind existing customers. The fallback is on-demand pricing, [which runs 2 to 3x more expensive and is often throttled or unavailable when demand peaks](https://www.spheron.network/blog/gpu-shortage-2026/). A training run that was budgeted at $40,000 on reserved capacity now costs somewhere between $80,000 and $120,000 on on-demand pricing, if capacity is even accessible.

Spot pricing, which used to be a perfectly fine planning input for development workloads, has [gotten unreliable enough that enterprises that relied on it in 2024 now find those instances simply unavailable at any price during peak demand windows](https://www.vamsitalkstech.com/ai/the-gpu-supply-chain-crisis-what-every-enterprise-cio-must-know-in-2026/).

When people in industry say the GPU access strategy is the AI strategy, this is what they're talking about.

## Nvidia is no longer just selling chips

One of the stranger dynamics the supply situation has produced is that Nvidia has effectively become an equity investor across the entire infrastructure stack it sells into. [As of this week, Nvidia has committed over $40 billion in equity bets in 2026 alone](https://www.cnbc.com/2026/05/09/nvidia-embraces-ai-investor-topping-40-billion-in-equity-bets-2026.html), including a $3.2 billion investment in Corning and a deal giving it the right to invest up to $2.1 billion in data center operator IREN. The IREN deal also commits IREN to deploying up to 5 gigawatts of Nvidia's DSX infrastructure designs at facilities globally. Nvidia's non-marketable equity holdings on its balance sheet grew from $3.39 billion to $22.25 billion in a single year.

What this means in practice is that the company selling the constraining input has now bought minority positions in a lot of the companies that consume it. The structural advantage that comes with that, especially when allocation is the binding constraint on growth, is significant. The supply chain isn't just tight, it's also getting more integrated in ways that don't particularly favor anyone outside the integration.

![Tech servers](/images/techno-servers.jpg)

## The friction that isn't priced in

While the deal flow at the top of the stack looks pretty much unstoppable, the physical buildout is running into a constraint that wasn't really on anyone's roadmap eighteen months ago: people who live near the proposed sites don't want them there.

[Last week, hundreds of protesters showed up to a Box Elder County Commission meeting in Utah](https://www.cnn.com/2026/05/09/tech/ai-data-center-utah-kevin-oleary-opposition) to oppose a 9-gigawatt AI data center backed by investor Kevin O'Leary. The project was approved anyway, but residents are now pushing to get a vote on the November ballot to oppose the development. [Maine's governor was recently forced to veto a law that would have banned new construction by hyperscalers](https://www.cnbc.com/2026/05/09/ai-data-center-construction-public-opposition.html). And [fourteen states from Oklahoma to New York are considering legislation that would ban or pause new data centers](https://www.cnbc.com/2026/05/09/ai-data-center-construction-public-opposition.html).

The number that I think is most worth pausing on is that [between a third and a half of US data centers planned for 2026 are likely to be delayed or canceled](https://www.techradar.com/pro/if-one-piece-of-your-supply-chain-is-delayed-then-your-whole-project-cant-deliver-nearly-half-of-us-data-centers-planned-for-2026-canceled-or-delayed-and-things-could-soon-get-much-worse), according to Sightline Climate analysis reported by Bloomberg. That's against an estimated 12 to 16 gigawatts of announced 2026 capacity, with only about 5 gigawatts currently under active construction. The bottlenecks are mostly electrical infrastructure (transformers, switchgear, batteries, much of it sourced abroad) and power.

The friction is real, and most of it is local. Power grid strain, water usage, land impact, and a general sense that communities are bearing the cost while the upside flows to companies headquartered somewhere else. Wisconsin regulators recently [approved changes requiring large-load customers to fund the full cost of generation and grid infrastructure](https://www.datacenterknowledge.com/data-center-construction/new-data-center-developments-may-2026). North Carolina is advancing similar legislation. These aren't symbolic moves, they're changing the economics of where capacity gets built and who pays for it.

This matters for a business trying to use AI rather than build a data center because the projected pipeline of capacity that everyone is implicitly counting on, the supply that's supposed to eventually catch up with demand and bring pricing back down, runs through these same county commission meetings. If meaningful pieces of the pipeline get delayed, scaled back, or rerouted to less constrained jurisdictions, the relief that enterprise buyers are waiting for comes later than the current forecasts assume.

The Trump administration's [July 2025 executive order streamlining permitting for projects over 100 megawatts or $500 million](https://fortune.com/2026/05/06/ai-data-center-michigan-saline-politics-farmland/) cuts in the other direction federally, but state and local resistance is operating on its own timeline. The political layer is now functionally part of the supply curve, and it isn't modeled in most enterprise AI roadmaps.

## The playbook isn't that complicated

The temptation when reading any of this is to either panic or shrug, and both are wrong. The shortage is structural, but the playbook for working around it is reasonably well understood at this point.

The first move is workload classification, which sounds boring but is where most buyers go wrong. Training, inference, and experimentation have completely different procurement profiles, and treating GPU access as one undifferentiated problem is the most common mistake I see. [Inference workloads serving production traffic need guaranteed availability and SLA-backed infrastructure](https://www.vamsitalkstech.com/ai/the-gpu-supply-chain-crisis-what-every-enterprise-cio-must-know-in-2026/). Training workloads can tolerate longer acquisition cycles. Mixed development workloads are reasonable candidates for spot capacity and GPU-as-a-service providers. Get the classification wrong and you'll either be overpaying for the wrong tier or undersized for the workload that matters most.

The second thing is that reserved capacity isn't a cost optimization anymore, it's the contract you sign to get capacity at all. The era of treating cloud GPUs as elastic, on-demand commodities is over for production AI. Companies that need reliable access in 2026 and 2027 are signing multi-year commitments, and the ones that aren't are accepting (often without realizing it) that their roadmaps are going to slip.

Worth taking the alternative accelerators seriously, too. [Enterprise spending on XPUs (TPUs, Trainium, Gaudi, and other specialized chips) is projected to grow 22.1% in 2026](https://www.clarifai.com/blog/gpu-shortages-2026), outpacing GPU spending growth. About 31% of enterprise decision-makers are evaluating Google's TPUs and 26% are evaluating AWS Trainium. The lock-in concerns are legitimate, but they're concerns about a different problem than the one most teams are facing right now, which is getting any compute at a sensible price.

The neo-cloud providers (CoreWeave, Lambda, Crusoe) aren't a niche option anymore either. Their entire business model depends on keeping on-demand capacity accessible to customers who can't get it from the hyperscalers, which is exactly the customer profile most mid-market firms have just stumbled into. Worth a real evaluation, not just an internal memo.

The last thing, and probably the most useful one to internalize, is that utilization matters more than allocation now. [VentureBeat's Q1 2026 AI Infrastructure tracker found that average enterprise GPU utilization is sitting at around 5%](https://venturebeat.com/infrastructure/5-gpu-utilization-the-401-billion-ai-infrastructure-problem-enterprises-cant-keep-ignoring). That's not a typo. Most of the capacity that was bought in panic mode during the scarcity years is sitting idle. The conversation is starting to shift from "how do we get more GPUs" to "how do we stop paying for the ones we're not using," and that shift is real. It favors buyers who can demonstrate operational discipline over the ones still in panic-purchase mode.

The deeper point in all of this is that AI procurement has stopped being a technology question and turned into a strategy question. The companies pulling ahead aren't the ones with the biggest budgets, they're the ones treating compute access as a board-level concern, classifying their workloads honestly, and working with [partners who know this terrain](https://semantictechnologyservices.com/) rather than trying to figure it out internally on a cost center's schedule.

Something that's worth saying, even if it's a bit uncomfortable, is that some percentage of the AI projects sitting in enterprise roadmaps right now were never going to clear the bar regardless of compute availability. The scarcity environment is going to surface those projects faster than a normal market would. When the marginal training run costs three times what it used to, the experiment that was already shaky gets killed first. That's probably healthy on balance. The AI conversation in 2024 and 2025 was dominated by demonstrations of what was possible, and the conversation in 2026 is getting forced into a more useful one about what's worth doing. Constraint tends to clarify priority. Most leaders pretending to have a strategic AI plan in 2025 had a list of pilots, not a plan, and the supply shock is what's going to turn those lists into real plans. Because suddenly, you have to choose.
