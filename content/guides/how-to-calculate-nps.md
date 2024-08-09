---
title: How to Calculate NPS (Net Promoter Score) | CustomerSure
toc_title: How to Calculate NPS
jumbotron_title: How to Calculate<br> <strong>Net Promoter Score</strong>
description: Here’s a handy NPS calculator, an explanation of the NPS formula, and
  a step-by-step guide to how and why the calculation works.
itg: |-
  <p>If you’re a NPS newbie, or just refreshing your memory, you’ll be an expert by the time you finish this guide.</p>
  <p>You’ll learn why this NPS calculation works, how to perform it, and some expert-level tips about when to use net promoter scores, when not to use it, and how to handle tricky topics like non-standard scales.</p>
image: "/assets/img/guides/nps/og-calculate-nps.jpg"
banner: "/assets/img/guides/covers/how-to-calculate-nps.jpg"
order: 15
js:
- nps_calc
highlight: t
jumbotron_class: nps-calc-page
---

## Net promoter score calculation is simple

You need two numbers for the NPS calculation formula:

* The **percentage** of **detractors** your business has…

* and the **percentage of promoters** your business has.

Subtract your detractors from your promoters, write the number on a postcard and behold: **NPS**.

But what are promoters and detractors? When should you calculate NPS? What should you do after you calculate it?

NPS is a [fine customer satisfaction methodology](/what-is-nps/), and in the nine years we’ve spent helping mid-market firms develop **CX programmes that get measurable results**, we’ve seen a lot of NPS: good and bad.

Before you reach for your spreadsheet or our handy online calculator, take twominutes to read this guide and learn what we’ve spent the best part of a decade perfecting. Know for sure that you’re calculating Net Promoter at the right tim eand in the right way.

We’ll make it worth your while…

## What are Promoters and Detractors?

When Fred Reichheld was working on [the original research]({% link _researching/what-is-nps.md %}) which established Net Promoter Score, he noticed that when you ask customers,

> “On a scale of 0-10, to what extent would you recommend *company x* to a friend or colleague?”

The responses to this question naturally clustered into three distinct groups:

* **Promoters** (Score of 9 or 10): Promoters have high repurchase rates, and were very likely to refer new customers (80% of all referrals).

* **Passives** (Score of 7 or 8): Have repurchase and referral rates up to **50% lower** than promoters. These customers are motivated mainly by inertia, not enthusiasm.

* **Detractors** (Score of 0-6): These customers account for up to 80% of negative word-of-mouth. Just because they’re paying you money doesn’t mean they’re necessarily good for you, once you consider their effect in lost sales and support costs.

Once you’ve got some promoters, passives, and detractors, here’s how you use them to calculate your NPS score:

![The Net Promoter Formula](/assets/img/guides/nps/the-nps-formula.png)

Speaking of that ‘Recommend’ question,

It wasn’t plucked out of thin air.

[A lot of research]({% link _researching/what-is-nps.md %}) went into finding outwhich question had the best predictive power for a company’s future growth.

But if the standard question isn’t right for your business, don’t get hung up on it – what’s important is that you have **a question that everyone in your team understands**, and you have a **straight forward** way of grouping the scores from that question into promoters, detractors and passives.

It’s this simplicity that’s important.

Whilst the original research which became NPS showed that the ‘recommend’ question is a good predictor of future growth for most companies in most industries, years of real-world testing and tweaking has shown that the **best** question is a simple one that gets everyone on your team working towards the same goal: **measuring customer loyalty**.

If you want to see how different numbers of promoters and detractors affect yourNPS score, try using our simple interactive calculator:

## NPS Calculator

For example, if 20 people have scored you ‘9’, type ‘20’ in the box marked ‘9’

<form id="nps-calc" class="nps-calc container">
<div class="nps-calc-scores">
<label> 0
  <input class="form-control" type="number" min="0" data-nps-score data-nps-detractor name="nps-0" value="" />
</label>
<label> 1
  <input class="form-control" type="number" min="0" data-nps-score data-nps-detractor name="nps-1" value="" />
</label>
<label> 2
  <input class="form-control" type="number" min="0" data-nps-score data-nps-detractor name="nps-2" value="" />
</label>
<label> 3
  <input class="form-control" type="number" min="0" data-nps-score data-nps-detractor name="nps-3" value="" />
</label>
<label> 4
  <input class="form-control" type="number" min="0" data-nps-score data-nps-detractor name="nps-4" value="" />
</label>
<label> 5
  <input class="form-control" type="number" min="0" data-nps-score data-nps-detractor name="nps-5" value="" />
</label>
<label> 6
  <input class="form-control" type="number" min="0" data-nps-score data-nps-detractor name="nps-6" value="" />
</label>
<label class="passive"> 7
  <input class="form-control" type="number" min="0" data-nps-score data-nps-passive name="nps-7" value="" />
</label>
<label class="passive"> 8
  <input class="form-control" type="number" min="0" data-nps-score data-nps-passive name="nps-8" value="" />
</label>
<label class="promoter"> 9
  <input class="form-control" type="number" min="0" data-nps-score data-nps-promoter name="nps-9" value="" />
</label>
<label class="promoter"> 10
  <input class="form-control" type="number" min="0" data-nps-score data-nps-promoter name="nps-10" value="" />
</label>
</div>
<div class="nps-calc-out">
<div data-detractors class="nps-calc-detractors">
<p>Detractors</p>
<span data-nps-pct class="nps-sum"></span>
(<span data-nps-sum class="nps-pct"></span>)
</div>
<div data-promoters class="nps-calc-promoters">
<p>Promoters</p>
<span data-nps-pct class="nps-sum"></span>
(<span data-nps-sum class="nps-pct"></span>)
</div>
<div class="nps-calc-nps">
<p>NPS</p>
<span data-nps class="nps-nps"></span>
</div>
</div>
</form>


## When should I calculate my NPS?

This depends on your circumstances. There’s no one-size-fits-all answer, but if you’d appreciate some advice, we [love to chat](/contact/) about customer satisfaction and we don’t do awkward, pushy sales, so give us a call? But in general…

[The NPS system]({% link _researching/what-is-nps.md %}) describes two main type sof survey: **transactional** (every time a customer completes a touchpoint with you) and **relationship** (surveying a cohort of your customers at a moment in time).

Done well, transactional surveys can replace a lot of the need for relationship surveys. If you’re surveying most of your customers naturally as they interact with you, then a ‘quarterly customer survey’ or ‘monthly customer attitude poll’ isn’t going to tell you a lot you don’t already know.

Transactional surveys give you constant visibility of your live NPS score. Which is nice. But, like any business metric, it’s not helpful to obsess over it day-to-day. So when should you look at it?

![NPS score month by month](/assets/img/guides/nps/nps-overtime.png)

You need to make two choices when you calculate your NPS score from transactional surveys:

* **How often** are you going to calculate it? As a rough guideline, we’d recommend you do this monthly. Less often, and you run the risk of ‘coasting’ in between updates, but any more often and you run the risk of being thrown off-course by day-to-day swings in your data.

* **What time period** are you calculating for? If you’re calculating your score every month, are you just looking at the previous month’s data, or a rolling time window (i.e. past 3, 6 or 12 months)?

If you’re calculating over a 12-month window, good scores from the past may pull up your average and mask bad scores you’re getting today. But, calculating month-to-month can give you very volatile data that it’s hard to make sensible business decisions with. As a broad guideline, we’d suggest a 3-month rolling window… But ultimately, the right answer depends on your circumstances.

But always, always remember: It’s great to know your NPS **score**, but it’s the NPS **system** that improves customer satisfaction. However you choose to measure things, your primary focus should always be [finding and fixing individual customer issues]({% link _implementing/respond-to-customer-feedback.md %})in real time.

## What data should I use to calculate my NPS?

We’ve covered which time period you should calculate NPS over, but there’s another important question: how should you ‘slice’ your team or organisation’s data?

Again, there’s no ‘one true answer’ here – [get in touch]({% link contact/index.html %})if you’d like to discuss your circumstances. However, let’s look at some of the factors which shape the answer:

## Should I calculate NPS for Individual Advisors?

There are arguments for and against this. On balance, we’d advise that you don’t.

Most strongly **against** is the fact that the traditional NPS question asks _would you recommend **the organisation**?_, so it’s unfair to pin the answer to that question to any one person.

You might get better results [combining two metrics]({% link _researching/customer-satisfaction-metrics.md %}),asking one question about the organisation (NPS), and another question, for example, CES, about the individual.

In the right setting, we have seen NPS-for-individuals work, though.

In practice though, we’ve seen NPS for individuals can be made to not only work,but deliver [brilliant results]({% link _implementing/team-motivation.md %}).

![NPS scores by staff member](/assets/img/screenshots/staff-heatmap.png)

To get it right, there’s a few things you need to be aware of:

### Organisation vs Individual

People who point out that the NPS question is about the organisation have a point. Be very, very careful about assuming that bad scores mean bad performance, especially when you’re working with a limited amount of data.

We strongly recommend that you ask a few short, customer-centric [follow up questions]({% link _researching/nps-surveys.md %}) on your NPS surveys,and this is just one of the reasons why.

Asking targeted questions like “How helpful was your advisor today?” alongside general sentiment questions like NPS allows customers to be specific about their feelings. As a customer yourself, have you ever wanted to simultaneously criticise an organisation but praise an individual within that organisation who tried to help you?

You should also never be asking the NPS question without a question for free-text feedback, and this feedback will normally make clear whether the score relates to the individual or the organisation or a whole.

### Culture

Culture is the single most important factor being the success (or failure!) of**any** CX initiative.

Unsurprisingly it’s massively important here.

That individual who keeps getting low NPS scores… Are they a problem? Or are they your star performer who’s fixing more than their fair share of difficult customer issues? Are they a liability, or are they a new starter, who, with a little coaching could be one of your greatest assets?

If your company culture doesn’t support your people, individual NPS could be a morale-destroyer. It’s not great to feel that your peers are judging you on a score you don’t have full control over!

Part of [the motivation for NPS]({% link _researching/what-is-nps.md %}) is to unite the whole organisation around one key customer-centric number, so it goes without saying that company-level NPS is something which should be sharedfar-and-wide.

However, unless your company culture is extremely supportive, and people are genuinely looking out for each other, it could be best to keep individual-levelNPS scores between advisors and their managers.

### Comparing Individuals

Following on from the previous two points, never, ever **benchmarking** NPS for individuals. As a rule, we’d say that [benchmarking satisfaction is a waste of time]({% link _researching/nps-benchmarks.md %}), and this is doubly-true when attributing scores to individual advisors.

It’s a useful tool to identify team members who might need extra coaching, not an arbitrary score to hold your team to.

### Skewed Data

And finally, on that note – have you ever had a comment card pressed into your hand and been asked,

> Please give me a 9 or a 10… my bonus depends on it!

As a customer, did you feel able to give truthful, helpful feedback in that situation?

Feedback that would help the company improve its customer service?

Or do you just give a 10 and move on with your life?

Never use NPS as a basis for any form of **individual incentivisation**. People will always try to ‘game’ the system. The best scores will go to your team members who are best at sweet-talking customers, you’ll miss out on a huge amount of constructive feedback, and lose a reliable measure of how satisfied your customers *really* are.

## What about non-standard NPS scales?

We’ve got a whole blog post explaining [how to calculate NPS on a 1-5 scale]({% post_url 2023-08-23-calculate-nps-on-a-1-to-5-scale %})!

## Can I calculate NPS for other areas of my company?

If it’s a meaningful way of dividing up your business, it can be a useful way of segmenting your NPS. Depending on your circumstances, it can be helpful to compare things like contact centre teams, sites or product lines. But in most cases, the issues we discussed around comparing advisors will still apply, so remember:

* put things in **context**,

* build a positive **culture** around satisfaction scores

* don’t rely on **benchmarks**.

* and definitely, do not incentivise NPS or any other CX metric.
