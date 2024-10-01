---
created: <% tp.file.creation_date() %>
month: <% tp.date.now("YYYY-MM") %>
tags: [monthly-review]
---

# Monthly Review - <% tp.date.now("MMMM YYYY") %>

## 📅 Overview

- Month start: <% tp.date.now("YYYY-MM-01") %>
- Month end: <% tp.date.now("YYYY-MM-DD") %>

## 🏆 Major Accomplishments

1.
2.
3.

## 💪 Challenges Overcome

1.
2.
3.

## 📊 Habit Tracker Monthly Summary

```dataview
TABLE WITHOUT ID
    choice(sum(exercise) > 0, "✅", "❌") AS "Exercise",
    choice(sum(meditation) > 0, "✅", "❌") AS "Meditation",
    average(mood) AS "Avg Mood",
    average(productivity) AS "Avg Productivity"
FROM "planner/daily"
WHERE file.day.month = date(<% tp.date.now("YYYY-MM-01") %>).month
GROUP BY file.day.week
```

## Reading Summary

- Books completed:
- Total pages read:
- Favorite book/reading of the month:

## 🎯 Goals Review

- Monthly goals achieved:
- Progress on quarterly goals:
- Progress on yearly goals:

## 💡Key Learnings

1.
2.
3.

## 🧘Well-being Assessment

- Physical health trends:
- Mental health trends:
- Relationship developments:
- Work-life balance reflections:

## 💰 Financial Check-in

- Income:
- Expenses:
- Savings:
- Financial goals progress:

## 🔁 Habit Review

- Habits that served me well:
- Habits to improve or develop:

## 🚀 Next Month Planning

- Top 3 priorities for next month:

1.
2.
3.

- New habits or skills to develop:
- Upcoming events or deadlines:

## 💭 Overall Reflection and Insights
