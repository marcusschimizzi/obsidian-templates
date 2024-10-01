---
created: <% tp.file.creation_date() %>
year: <% tp.date.now("YYYY") %>
tags: [yearly-review]
---

# Yearly Review - <% tp.date.now("YYYY") %>

## 🏆 Year's Biggest Achievements

1.
2.
3.
4.
5.

## 🎯 Goals Review

- Annual goals achieved:
- Ongoing long-term goals progress:
- Unmet goals and reflections:

## 📈 Personal Growth

- Major areas of growth:
- New skills acquired:
- Significant mindset shifts:

## 📚 Learning and Development

- Books read:
- Courses or training completed:
- Key learnings:

## 💼 Professional Journey

- Career milestones:
- Job changes or advancements:
- New skills or certifications:

## 🧘‍♀️ Well-being Assessment

- Physical health journey:
- Mental and emotional growth:
- Relationship developments:
- Work-life balance reflections:

## 💰 Financial Year in Review

- Income summary:
- Expense analysis:
- Savings and investments progress:
- Financial goals achieved:

## 🌟 Memorable Moments

1.
2.
3.
4.
5.

## 🌍 Impact and Contributions

- Personal achievements:
- Community involvement:
- Environmental efforts:

## 📊 Year in Numbers

```dataview
TABLE WITHOUT ID
  sum(exercise) AS "Total Days Exercised",
  sum(meditation) AS "Total Days Meditated",
  average(mood) AS "Avg Mood for Year",
  average(productivity) AS "Avg Productivity for Year"
FROM "planner/daily"
WHERE file.day.year = this.year
```

## 🔄 Habits and Routines

- Most impactful habits developed:
- Habits to leave behind:
- New habits to cultivate:

## 🚀 Looking Ahead

- Vision for the coming year:
- Top 5 goals for next year:
  1.
  2.
  3.
  4.
  5.
- Areas to focus on:
- Habits or skills to develop:

## 💭 Year-End Reflection

- What am I most grateful for this year?
- What were the biggest lessons learned?
- How have I changed or grown?

## 📸 Year in Pictures

<!-- Consider adding links to a photo album or memorable images from the year -->
