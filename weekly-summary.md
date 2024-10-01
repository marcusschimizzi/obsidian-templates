---
created: <% tp.file.creation_date() %>
week: <% tp.date.now("YYYY-[W]ww") %>
tags: [weekly-review]
---

# Weekly Review - <% tp.date.now("YYYY-[W]ww") %>

## 📅 Overview

- Week start: <% tp.date.weekday("YYYY-MM-DD", 0) %>
- Week end: <% tp.date.weekday("YYYY-MM-DD", 6) %>

## 🔍 Review of the Week

### Accomplishments

- What were my main achievements of this week?

1.
2.
3.

### Challenges

- What difficulties did I face?

1.
2.
3.

### Lessons Learned

- What did I learn this week?

1.
2.
3.

## 📊 Habit Tracker Review

```dataview
TABLE WITHOUT ID
    file.link AS "Date",
    mood AS "Mood",
    productivity AS "Productivity",
    exercise AS "Exercise",
    meditation AS "Meditation"
FROM "planner/daily"
WHERE file.day >= date(<% tp.date.weekday("YYYY-MM-DD", 0) %>) AND file.day <= date(<% tp.date.weekday("YYYY-MM-DD", 6) %>)
SORT file.day ASC
```

## 📚 Reading Progress

- Books read/in progress:
- Pages read this week:
- Key takeaways:

## 🎯 Goals Check-in

- Progress on weely goals:
- Progress on monthly goals:
- Progress on quarterly goals:

## Well-being Reflection:

- Physical health:
- Mental health:
- Relationships:
- Work-life balance:

## Journal Entries

```dataview
LIST FROM "planner/daily"
WHERE file.day >= date(<% tp.date.weekday("YYYY-MM-DD", 0) %>) AND file.day <= date(<% tp.date.weekday("YYYY-MM-DD", 6) %>)
SORT file.day ASC
```

## 🚀 Next Week Planning

- Top 3 priorities for next week:

1.
2.
3.

- Habits to focus on:
- Any upcoming events or deadlines:

## 💭 Additional Thoughts and Reflections
