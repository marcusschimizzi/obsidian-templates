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

## 🧠 Top of Mind

## Exercise:

- Type:
- Duration:
- Notes:

## 📖 Learning

## ✨ Highlight of the day

## 🗒️Notes Created/Edited Today

```dataview
LIST FROM "" WHERE file.cday = this.file.day OR file.mday = this.file.day
SORT file.name ASC
```

---
