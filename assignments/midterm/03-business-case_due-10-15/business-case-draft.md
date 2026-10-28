# SummerNest: Business Case (Draft, due Oct 15)

Drafted with Claude (AI) as a starting model. Every number below is an assumption for the team to change. Items marked [estimate] have no outside source yet; items marked [benchmark] link to a source. Decisions for the team are marked [decide].

## Model scope

- Period: Year 1 = one summer season (searching Jan to May 2027, stays Jun to Aug 2027)
- Launch: 10 universities in 4 cities
  - Seattle: UW Seattle, NEU Seattle
  - LA: UCLA, USC
  - SF Bay Area: SF State, USF, UC Berkeley, Stanford
  - NY: NYU, Columbia
- Founders unpaid in Year 1 [decide]
- Price: $29 season pass, one fee covers both posting and browsing [decide]

## Slide 1: Year 1 P&L

### Revenue funnel (Revenue = paid members x $29)

| Step | Assumption | Users |
|---|---|---|
| Students at 10 launch schools | Seattle 53.8k + LA 94.4k + SF Bay Area 94.3k + NY 92.7k [benchmark: school enrollment data] | 335,200 |
| Do a summer internship that year | 30% [estimate; NACE: 67% of Class of 2024 seniors had at least one internship during college] | 100,560 |
| Relocate to another city for it | 40% [estimate] | 40,224 |
| Sign up and verify (free) | 15% [estimate] | 6,034 |
| Pay for season pass | 30% [estimate] | 1,810 |

### P&L

| Line | Calculation | Year 1 |
|---|---|---|
| **Revenue** | 1,810 x $29 | **$52,490** |
| Payment processing | 2.9% + $0.30 per charge [benchmark: Stripe] = $1.14 x 1,810 | ($2,065) |
| ID check for users without a school email | 20% of 6,034 sign-ups x $1.50 [benchmark: Stripe Identity] | ($1,810) |
| Customer support | $1 per paid member [estimate] | ($1,810) |
| **Gross profit** | | **$46,805 (89%)** |
| Marketing: 10 campus ambassadors | $500 each [estimate] | ($5,000) |
| Marketing: social ads | [estimate] | ($3,000) |
| Hosting and software tools | ~$175/month [estimate] | ($2,100) |
| Legal review of terms (one time) | [estimate] | ($2,000) |
| **Operating profit** | | **$34,705 (66%)** |

Key ratios
- Contribution per paid member: about $26.86 ($29 minus Stripe and support)
- Break-even: about 518 paid members, which means a sign-up-to-paid conversion of about 8.6%
- CAC (marketing / paid members): about $4.40
- Hosting and support costs may need to grow with 6,000+ users [estimate]

### Pricing benchmarks (why $29)

- Facebook groups, Craigslist, RedNote: free
- Furnished Finder: landlords pay $199/yr per listing, tenants free [benchmark]
- Airbnb: free to list; host fee mostly 15.5% since late 2025 [benchmark; sources conflict]. On a $1,500/month room for 3 months, that is about $700.
- $29 sits close to the free options, far below paid platforms.

### Sensitivity: conversion rate drives everything

| Sign-up to paid conversion | Paid members | Operating profit |
|---|---|---|
| 30% (base) | 1,810 | +$34,700 |
| 15% | 905 | +$10,400 |
| 8.6% (break-even) | ~518 | ~$0 |
| 5% | 302 | -$5,800 |

## Slide 2: Riskiest assumptions

How we ranked them: impact on the P&L x how little evidence we have. These are the leap-of-faith assumptions from Lean Startup Ch. 5 (value hypothesis and growth hypothesis, PDF p. 84+).

### 1. Users will pay $29 when Facebook and RedNote are free (30% conversion)

- Why risky: it is the biggest revenue driver. Below ~8.6%, Year 1 loses money.
- No evidence yet. All competing channels for this group are free.
- Warning sign: Kopa (formerly PadPiper, SF, 2016), a verified medium-term housing marketplace, has shut down (per kopa.co).
- Test: landing page with a "reserve your pass" button, or pre-sale at one school.

### 2. Enough matching listings exist in each city for the right dates (liquidity)

- Why risky: a paid member who finds no room gets no value, asks for a refund, and will not recommend us.
- Our plan relies on supply-demand overlap: a student leaving City A for City B lists their room in A. We assume about 40% of members are on both sides [estimate]. If overlap is low, we have a cold-start problem in every city.
- Test: survey students at launch schools: where do you go, and will you sublet your room?

### 3. We can reach relocating interns cheaply in a short window (15% sign-up, ~$4.40 CAC)

- Why risky: each user needs us once or twice in college, so lifetime value is about one pass ($29). CAC must stay far below that.
- The search window is about 4 months per year, so a failed channel costs us a full season.
- Test: one ambassador at one school for 4 weeks, measure sign-ups per dollar.

## Sources to cite on the slides

- NACE, 2024 Student Survey: https://naceweb.org/job-market/internships/students-recognize-the-importance-of-gaining-internship-experience
- Enrollment:
  - UW Seattle (Autumn 2025): https://www.washington.edu/news/2025/10/30/washington-residents-make-up-nearly-two-thirds-of-incoming-class-as-enrollment-increases-across-all-three-uw-campuses/
  - NEU Seattle (~1,500, 2023): https://news.northeastern.edu/2023/11/21/seattle-campus-10-year-anniversary/
  - UCLA (Fall 2025): https://ucsdguardian.org/2026/01/12/uc-fall-2025-enrollment-numbers-reach-record-high/
  - USC (~47,000, 2023-24): https://usc.edu/?p=1191
  - SF State (~20,700, Fall 2025): https://goldengatexpress.org/113580/campus/a-one-sided-enrollment-battle-sjsu-booms-while-sfsu-shrinks/
  - USF (2025): https://www.usfca.edu/
  - UC Berkeley (Fall 2025): https://opa.berkeley.edu/campus-data/uc-berkeley-quick-facts
  - Stanford (Fall 2024 Common Data Set): 18,625 [find official link]
  - NYU (Fall 2025, excl. noncredit): https://www.nyu.edu/about/news-publications/nyu-at-a-glance.html
  - Columbia (Fall 2025 Common Data Set): https://opir.columbia.edu/sites/opir.columbia.edu/files/content/Common%20Data%20Set/2025-26_Columbia_General_Studies_CDS.pdf
- Stripe pricing: https://stripe.com/pricing
- Stripe Identity: https://stripe.com/identity
- Furnished Finder and Airbnb fees: from our 10/7 research [re-check links before submitting]
- Kopa: https://kopa.co
- Ries, Eric. The Lean Startup, 2011, Ch. 5
- AI citation (MLA), same format as the 10/8 slides
