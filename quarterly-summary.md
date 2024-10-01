---
created: <% tp.file.creation_date() %>
quarter: <% tp.date.now("YYYY-[Q]Q") %>
tags: [quarterly-review]
---

# Quarterly Review - <% tp.date.now("YYYY-[Q]Q") %>

## 📅 Overview

- Quarter start: <% tp.date.now("YYYY-[Q]Q-01") %>
- Quarter end: <% tp.date.now("YYYY-[Q]Q") + "-" + (tp.date.now("Q") \* 3 + "").padStart(2, "0") + "-" + (tp.date.now("Q") < 4 ? "30" : "31") %>

## 🏆 Key Achievements

1.
2.
3.

## 🎯 Goals Review

- Quarterly goals achieved:
- Progress on yearly goals:
- Goals to carry forward:

## 📈 Personal Growth

- New skills acquired:
- Areas of significant improvement:
- Challenges and learnings:

## 📚 Reading and Learning

- Books read:
- Courses completed:
- Key learnings:

## 💼 Professional Development

- Career milestones:
- New opportunities:
- Skills to develop:

## 🧘 Well-being Review

- Physical health:
- Mental health:
- Relationships:
- Work-life balance:

## 💰 Financial Review

- Income overview:
- Expense analysis:
- Savings progress:
- Investment performance:

## 🌟 Memorable Moments

1.
2.
3.

## 📊 Habit Tracker Quarterly Summary

```dataview
TABLE WITHOUT ID
  sum(exercise) AS "Days Exercised",
  sum(meditation) AS "Days Meditated",
  average(mood) AS "Avg Mood",
  average(productivity) AS "Avg Productivity"
FROM "planner/daily"
WHERE file.day >= date(<% tp.date.now("YYYY-[Q]Q-01") %>) AND file.day <= date(<% tp.date.now("YYYY-[Q]Q") + "-" + (tp.date.now("Q") * 3 + "").padStart(2, "0") + "-" + (tp.date.now("Q") < 4 ? "30" : "31") %>)
GROUP BY file.day.month
```

## 🚀 Next Quarter Planning

- Top 3 priorities:
  1.
  2.
  3.
- New habits or routines to implement:
- Upcoming major events or milestones:

## 💭 Overall Reflection and Insights
