---
created: <% tp.file.creation_date() %>
tags: [daily, journal]
meditation:
sleep_duration:
sleep_quality:
---

# Daily Journal - <% tp.date.now("YYYY-MM-DD") %>

Day of the year: <% moment(tp.file.title).format("DDD") %>

## 🔗 Quick Links

- [[<% tp.date.yesterday("YYYY-MM-DD") %>|Yesterday]] | [[<% tp.date.tomorrow("YYYY-MM-DD") %>|Tomorrow]]
- [[<% tp.date.now("YYYY-MM-DD", -365) %>|One year ago]]

## 📈 Today did I...

Meditate::0
Take Prescription::0
Exercise::0

## 🥅 Today's Goals

<!-- Set no more than 3 goals for a single day. What do you want to get done today? -->

[ ] Goal 1
[ ] Goal 2
[ ] Goal 3

## 🧠 Morning Thoughts

<!-- Space for morning thoughts, reflections, and plans for the day -->

## 📓General Notes

<!-- General notes for thoughts throughout the day -->

## Exercise:

- Type:
- Duration:
- Notes:

## 📖 Learning

- What I learned today:
- Resources used:

## 😴 Sleep Log

- Time slept:
- Sleep quality (1-5):
- Notes:

## ✨ Highlight of the day

## 🪞Evening Reflection

<!-- Use this space for end of day thoughts and planning for tomorrow -->

## 🗒️Notes Created/Edited Today

```dataview
LIST FROM "" WHERE file.cday = this.file.day OR file.mday = this.file.day
SORT file.name ASC
```

---
