# 06 · Reporting & insights

> Turn numbers into decisions. Pair these with [paid-social-ai-report](https://github.com/anaiscarapaica/paid-social-ai-report).

---

## 6.1 · Monthly report for a client (non-technical)

```text
ROLE: Social media manager presenting to a business owner who is not a marketer.
DATA: {{paste monthly metrics: followers, reach, engagement rate, top 5 posts, ads spend, results}}
OUTPUT:
1. 3-line summary: what happened, why, what we do next
2. KPI table vs last month (↑↓ and %)
3. 3 wins and 1 thing that didn't work (with honest reason)
4. Next month: 3 actions with expected impact
RULES: No vanity metrics without context. Translate every metric to business language.
Respond in {{language}}.
```

## 6.2 · Top/bottom post analysis

```text
Here are my 30 posts from last month with format, topic, hook, reach, saves, shares, comments: {{data}}
Find what the top 20% have in common vs the bottom 20% (format, topic, hook type, length, posting time).
Give me 5 rules for next month backed by the data, and 3 hypotheses to test.
Respond in {{language}}.
```

## 6.3 · KPI tree

```text
Business goal: {{goal}}. Build a KPI tree from that goal down to weekly social metrics.
For each level: metric, formula, current value {{if known}}, target, who owns it.
Show it as an indented list.
Respond in {{language}}.
```

## 6.4 · Insight → content brief

```text
Insight: {{e.g. "carousels about mistakes get 3x saves"}}.
Turn it into a 2-week content brief: 6 pieces, each with topic, format, hook, KPI target, and how we'll know the insight still holds.
Respond in {{language}}.
```

## 6.5 · Explain a drop

```text
Reach dropped {{X}}% this {{week/month}}. Context: {{posting frequency, formats, changes, seasonality, ads}}.
List the most likely causes ranked by probability, the data I need to confirm each, and what to do in the next 7 days. Don't blame "the algorithm" without evidence.
Respond in {{language}}.
```

## 6.6 · Quarterly review deck outline

```text
Create the outline for a 10-slide quarterly review for {{brand}}: one headline per slide (the conclusion, not the topic), the chart to show, and the speaker note.
Data: {{paste}}
Respond in {{language}}.
```
