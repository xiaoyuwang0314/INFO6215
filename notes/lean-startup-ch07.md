# The Lean Startup, Chapter 7: Measure (Innovation Accounting)

> Part Two: STEER ｜ PDF p.115-146

---

## 中文版

### 一句话总结

Startup 需要一种新的会计方法，叫 innovation accounting：先用 MVP 测出真实的 baseline，再通过实验调优 engine of growth，最后决定 pivot 还是 persevere。判断进展要看 actionable metrics，而不是看起来很漂亮的 vanity metrics。

### 核心观点

1. **Startup 的两项任务。** 商业计划里的财务模型是一个理想状态，和公司早期的真实情况差得很远。Startup 要做的是：第一，严格测量自己现在在哪里，直面难看的数字；第二，设计实验，让真实数字一步步靠近计划里的理想值。大多数产品不会完全没有 traction，最危险的是一直半死不活地拖着，也就是作者说的 "land of the living dead"。(p.115)

2. **传统会计不适合 startup。** 在 Alfred Sloan 领导下，GM 用会计给各个部门设定 milestone 并追究经理责任，现代企业都沿用这一套。但 startup 太难预测，预测和 milestone 都不准。作者常问创业团队"产品在变好吗？怎么知道的？"，得到的回答通常是"改了很多东西，客户好像喜欢，总数也涨了"。作者认为这只是讲故事，无法证明改动和结果之间有关系。(p.116-117)

3. **不同的增长模型，同一个问责框架。** Innovation accounting 从把 Chapter 5 的 leap-of-faith assumptions 变成量化财务模型开始。传统制造企业的增长主要取决于每个客户的利润、获客成本和老客户复购率。eBay 这类 marketplace 则靠 network effects，关键要看新买家和卖家的 retention。两种模式驱动因素不同，但都可以放进同一个框架来问责。(p.117-118)

4. **三个 learning milestones。**
   - **Establish the baseline**：用 MVP 拿到真实数据，比如 conversion rate、注册和试用率、customer lifetime value。可以做一个完整原型一次测多个假设，也可以用 smoke test（让客户预订还没做出来的产品）单独测一个假设。应该先测风险最大的假设，比如广告类媒体公司先测能不能持续吸引目标人群的注意力，而不是先去卖广告。(p.118-119)
   - **Tune the engine**：每一项产品、营销工作都应该对准增长模型里的某个驱动因素。一个设计改动如果没有让客户行为变好，就算失败。(p.120)
   - **Pivot or persevere**：如果数字从糟糕的 baseline 向理想值靠拢，就继续；如果理想值越来越远，就是该 pivot 的信号。成功 pivot 的标志是 pivot 之后调优工作的效率比之前高。(p.118, p.120)

5. **IMVU 每天花五美元做实验。** IMVU 跟踪一串 funnel metrics：注册、下载、试用、重复使用、购买。他们每天在 Google AdWords 上花 5 美元，买到大约 100 次点击，这对营销来说微不足道，但每天都能用一批全新的客户检验产品。结果发现总量在涨，funnel metrics 却几乎不动。(p.121-122)

6. **Cohort analysis。** 不看累计总数，而是把每个时间段进来的客户当作一组（cohort）单独看表现。IMVU 大约七个月的数据显示，新客户中使用产品至少五次的比例从不到 5% 升到将近 20%，但付费比例一直停在 1% 左右。每个 cohort 都是一份独立的成绩单，没法把问题推给老客户或市场环境。(p.123-124)

7. **数据让客户访谈变得有效。** 以前作者会把给出负面反馈的测试用户当作"不是目标用户"而换掉。有了数据后，他带着具体问题去问客户，很快发现客户根本不想和现有朋友一起用 IMVU，这促成了从 IM add-on 转向结交新朋友的独立网络的 pivot。规律是：定量结果差，迫使团队承认失败，接着做定性研究，产生新假设，可能引出 pivot。(p.125-126)

8. **Optimization 不等于 learning。** 工程师、设计师和营销人员都擅长优化，但如果做的东西本身是错的，再怎么优化也没用。作者常被请去解决"工程团队不够努力"的问题，实际问题往往是公司在很有纪律地执行一个说不通的计划。传统管理者会因此把规格写得更细，结果计划变慢、batch size 变大、反馈更迟。(p.126-127)

9. **Vanity metrics 的危险。** 同一时期 IMVU 的总注册用户和总付费用户图是一条漂亮的 hockey stick，看起来一切顺利。但这类总量数字说明不了团队的工作有没有效果。为了让总数好看，公司可能会玩 success theater，比如临时买广告、渠道压货、炫酷演示。作者把这类传统数字叫 vanity metrics，和它相对的是 actionable metrics。(p.128-130)

10. **Grockit 的案例。** 创始人 Farbood Nivi 曾是 Princeton Review 和 Kaplan 的老师，想把同伴互学搬到网上。最早的 MVP 只是他用 WebEx 在线教课。公司后来拿到融资，严格采用 agile 和 Extreme Programming，每个 sprint 都交付新功能，但客户使用量增长不够。原因是他们看的是 vanity metrics（总客户数、总答题数），每个周期关注的指标还不一样，无法判断因果。(p.130-135)

11. **Split test 和 kanban。** Grockit 做了两个改变：改用 cohort-based metrics，并把每个新功能都作为 split test（A/B test）上线。测试发现很多社交功能并不改变客户行为，反而单人学习模式很有效，学生喜欢自己选择怎么学。他们还用 kanban 管理 user stories，分成 backlog、开发中、完成、验证中四个状态，每个状态有数量上限，一个 story 只有被验证后才算真正完成。团队从此用 validated learning 而不是功能产出来衡量效率。(p.135-139)

12. **Lazy registration 实验。** Grockit 一直投入大量精力维护 lazy registration（先用后注册），这被认为是行业 best practice。一个简单的 split test 显示，要求立刻注册的 cohort 和 lazy registration 组的注册、激活、留存完全一样。这说明客户做决定依据的不是产品使用体验，改进定位和营销可能比加功能更有用。(p.140-141)

13. **好指标的三个 A。**
    - **Actionable**：能清楚显示因果关系。像网站点击数这种指标，涨了大家都说是自己的功劳，跌了就怪别的部门。(p.141-142)
    - **Accessible**：报告要简单易懂，用具体的单位，最好以人为单位，cohort 报告就是这样。报告也要让所有人都能看到，Grockit 每天把实验数据自动发给每个员工，IMVU 把报告系统做成产品的一部分。(p.143-144)
    - **Auditable**：数据要让员工信服。管理者要能直接找真实客户核对数据，报告应尽量直接从主数据生成，减少中间环节出错。(p.144-145)

14. **真正的工作发生在"蒙太奇"里。** 电影和媒体里的创业故事会把中间的苦活用几分钟蒙太奇带过。作者说创业只有 5% 是大创意和商业模式，其余 95% 是 innovation accounting 衡量的日常工作。其中最难的决定是什么时候 pivot、什么时候 persevere，这是 Chapter 8 的主题。(p.146)

### 关键术语

| 术语 | 解释 |
|---|---|
| Innovation accounting | 专为 startup 设计的会计方法，客观证明公司是否在学会如何建立可持续业务 |
| Learning milestones | innovation accounting 的三步：establish the baseline、tune the engine、pivot or persevere |
| Smoke test | 让客户预订尚未开发的产品，只测客户是否有兴趣 |
| Funnel metrics | 客户从注册到付费一系列关键行为的转化率 |
| Cohort analysis | 按客户进入时间分组，分别观察每组的表现，而不看累计总数 |
| Vanity metrics | 让情况看起来最乐观的总量指标，无法指导行动 |
| Actionable metrics | 能显示清晰因果关系、可以用来做决策的指标 |
| Split test (A/B test) | 同时给不同客户提供不同版本，比较行为差异 |
| Kanban | 来自 lean manufacturing 的容量限制方法，这里用于限制每个阶段的 user story 数量 |
| Success theater | 为了让总数好看而做的表面功夫 |
| Three A's | 好指标的标准：actionable、accessible、auditable |

### 我的思考题

- 你参与过的项目里，用来汇报进展的数字有哪些其实是 vanity metrics？如果换成 cohort 视角会看到什么？
- Grockit 的 lazy registration 被认为是 best practice，却没有效果。你还能想到哪些大家默认正确、但从没被验证过的做法？
- Kanban 要求 story 被验证后才算完成，这对工程师的工作感受会有什么影响？你觉得团队能接受吗？

---

## English Version

### One-Sentence Summary

Startups need a new kind of accounting, innovation accounting: use an MVP to measure a real baseline, run experiments to tune the engine of growth, then decide whether to pivot or persevere. Progress should be judged with actionable metrics, not flattering vanity metrics.

### Key Points

1. **A startup's two jobs.** The financial model in a business plan describes an ideal that is far from where an early startup actually is. The startup has to measure where it really stands, facing the uncomfortable numbers, and then design experiments that move those numbers toward the ideal. Most products have some traction. The real danger is drifting along in what Ries calls "the land of the living dead." (p.115)

2. **Standard accounting does not fit startups.** Under Alfred Sloan, GM used accounting to set milestones for each division and hold managers accountable, and modern corporations still work this way. Startups are too unpredictable for forecasts and milestones to be accurate. When Ries asks teams how they know their product is improving, the usual answer is that they shipped changes, customers seem happy, and totals went up. He sees this as storytelling that cannot link changes to results. (p.116-117)

3. **Different growth models, one accountability framework.** Innovation accounting starts by turning the leap-of-faith assumptions from Chapter 5 into a quantitative financial model. A manufacturer grows based on profit per customer, acquisition cost, and repeat purchase rate. A marketplace like eBay depends on network effects, so retention of new buyers and sellers is what matters. The drivers differ, but both fit the same framework. (p.117-118)

4. **Three learning milestones.**
   - **Establish the baseline**: an MVP produces real numbers such as conversion rates, sign-up and trial rates, and customer lifetime value. A startup can build one prototype that tests many assumptions, or use a smoke test (letting customers preorder a product that does not exist yet) to test a single one. Test the riskiest assumption first. A media company selling ads should first test whether it can hold an audience's attention, not whether it can sell ads. (p.118-119)
   - **Tune the engine**: every product or marketing effort should target one driver of the growth model. A design change that does not improve customer behavior counts as a failure. (p.120)
   - **Pivot or persevere**: if the numbers climb from the poor baseline toward the ideal, keep going. If the ideal keeps receding, it is time to pivot. A successful pivot shows up as engine tuning that is more productive afterward than before. (p.118, p.120)

5. **IMVU's five-dollar-a-day experiments.** IMVU tracked funnel metrics: registration, download, trial, repeat use, and purchase. It spent five dollars a day on Google AdWords, which bought about a hundred clicks. That was trivial as marketing but gave the team a fresh set of customers to test against every day. Gross numbers grew while the funnel metrics stayed flat. (p.121-122)

6. **Cohort analysis.** Instead of cumulative totals, look at each group of customers who arrived in a given period as a separate cohort. Over about seven months at IMVU, the share of new customers who used the product at least five times rose from under 5 percent to nearly 20 percent, yet the share who paid stayed near 1 percent. Each cohort was an independent report card, so the team could not blame old customers or market conditions. (p.123-124)

7. **Data made customer interviews useful.** Earlier, Ries would dismiss test users who gave negative feedback as outside the target market. Once he had data, he went to customers with urgent, specific questions and learned they did not want to use IMVU with existing friends. That led to the pivot from an IM add-on to a stand-alone network for meeting new people. The pattern: poor quantitative results force an admission of failure, which opens space for qualitative research, new hypotheses, and possibly a pivot. (p.125-126)

8. **Optimization is not learning.** Engineers, designers, and marketers are good at optimizing, but optimizing the wrong product yields little. Ries is often hired because a team supposedly is not working hard enough, and the real issue is usually that the company is carrying out a flawed plan with great discipline. Traditional managers respond by writing more detailed specs, which slows planning, grows batch sizes, and delays feedback. (p.126-127)

9. **The danger of vanity metrics.** From the same period, IMVU's charts of total registered users and total paying customers formed a nice hockey stick. Those totals say nothing about whether the team's work is having an effect. The pressure to boost them leads to success theater such as last-minute ad buys, channel stuffing, and flashy demos. Ries calls these traditional numbers vanity metrics and contrasts them with actionable metrics. (p.128-130)

10. **The Grockit case.** Founder Farbood Nivi taught test prep at Princeton Review and Kaplan and wanted to bring peer learning online. His first MVP was simply him teaching over WebEx. After raising money, the company followed agile and Extreme Programming rigorously and shipped features every sprint, but usage was not growing enough. The team was watching vanity metrics like total customers and total questions answered, and the metric of focus changed from cycle to cycle, so cause and effect stayed unclear. (p.130-135)

11. **Split tests and kanban.** Grockit switched to cohort-based metrics and launched every new feature as a split test (A/B test). Many of the social features turned out not to change behavior, while a solo study mode worked well, and students liked choosing how to study. The team also adopted kanban for user stories, with four states (backlog, in progress, done, being validated) and a cap on each. A story counted as finished only once validated. The team began measuring productivity by validated learning instead of features shipped. (p.135-139)

12. **The lazy registration test.** Grockit spent a lot maintaining lazy registration (use first, register later), an accepted industry best practice. A simple split test showed that a cohort forced to register up front behaved exactly like the lazy registration group in registration, activation, and retention. Customers were deciding based on something other than using the product, so better positioning and marketing might matter more than new features. (p.140-141)

13. **The three A's of metrics.**
    - **Actionable**: a report must show clear cause and effect. With a number like website hits, everyone takes credit when it rises and blames another department when it falls. (p.141-142)
    - **Accessible**: reports should be simple and use concrete, people-based units, which is why cohort reports work well. They should also be widely available. Grockit emailed every employee a daily report on all experiments, and IMVU built reporting into the product itself. (p.143-144)
    - **Auditable**: employees must trust the data. Managers should be able to spot-check numbers with real customers, and reports should come straight from master data to limit errors. (p.144-145)

14. **The real work happens in the montage.** Startup stories in movies and magazines skip the hard middle part with a quick montage. Ries says only 5 percent of entrepreneurship is the big idea and business model, and the other 95 percent is the everyday work that innovation accounting measures. The hardest decision is when to pivot and when to persevere, the subject of Chapter 8. (p.146)

### Key Terms

| Term | Meaning |
|---|---|
| Innovation accounting | Accounting built for startups that objectively shows whether a company is learning to build a sustainable business |
| Learning milestones | The three steps of innovation accounting: establish the baseline, tune the engine, pivot or persevere |
| Smoke test | Letting customers preorder an unbuilt product to test only their interest |
| Funnel metrics | Conversion rates across the key customer behaviors from sign-up to purchase |
| Cohort analysis | Grouping customers by when they arrived and tracking each group separately instead of looking at totals |
| Vanity metrics | Gross numbers that paint the rosiest picture but do not guide action |
| Actionable metrics | Metrics with clear cause and effect that can inform decisions |
| Split test (A/B test) | Offering different versions to different customers at the same time and comparing behavior |
| Kanban | A capacity-limit method from lean manufacturing, used here to cap user stories at each stage |
| Success theater | Surface-level efforts to make gross numbers look good |
| Three A's | Standards for good metrics: actionable, accessible, auditable |

### Discussion Questions

- In projects you have worked on, which progress numbers were really vanity metrics? What would a cohort view have shown?
- Lazy registration was a best practice that made no difference for Grockit. What other widely accepted practices have you seen that nobody actually tested?
- Under kanban, a story is not done until it is validated. How would that change how engineers feel about their work, and would your team accept it?
