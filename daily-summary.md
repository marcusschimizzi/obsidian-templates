---
created: <% tp.file.creation_date() %>
tags: [daily, journal]
mood:
productivity:
exercise:
meditation:
sleep_duration:
sleep_quality:
---

# Daily Journal - <% tp.date.now("YYYY-MM-DD") %>

Day of the year: <% moment(tp.file.title).format("DDD") %>

## 🔗 Quick Links

- [[<% tp.date.yesterday("YYYY-MM-DD") %>|Yesterday]] | [[<% tp.date.tomorrow("YYYY-MM-DD") %>|Tomorrow]]
- [[<% tp.date.now("YYYY-MM-DD", -365) %>|One year ago]]

## 🧠 Brain Dump

<!-- Use this space for unstructured thoughts, ideas, or reflections -->

## 🎯 Personal Goals

- [ ] Goal 1
- [ ] Goal 2
- [ ] Goal 3

## 💪 Health & Wellness

### Physical Health

- Exercise: <% tp.system.prompt("Did you exercise today? What did you do?") %>
- Nutrition: <% tp.system.prompt("How was your nutrition today?") %>

### Mental & Emotional Health

- Mood: <% tp.system.prompt("Rate your mood today (1-10):") %>
- Stress level: <% tp.system.prompt("Rate your stress level today (1-10):") %>
- Meditation: <% tp.system.prompt("Did you meditate today? For how long?") %>

### Sleep Log

- Bedtime (last night): <% tp.system.prompt("What time did you go to bed last night?") %>
- Wake time (today): <% tp.system.prompt("What time did you wake up today?") %>
- Sleep duration: <% tp.system.prompt("How many hours did you sleep?") %>
- Sleep quality (1-10): <% tp.system.prompt("Rate your sleep quality (1-10):") %>
- Notes: <% tp.system.prompt("Any notes about your sleep (dreams, interruptions, etc)?") %>

## 🍽️Food Log

- Breakfast:
- Lunch:
- Dinner:
- Snacks:
- Water intake:

## 💼 Work (if applicable)

- Accomplishments:
- Challenges:
- To-do for tomorrow:

## 👥 Relationships

- Notable interactions:
- Gratitude for someone:

## 📊 Habit Tracker

- [ ] Habit 1
- [ ] Habit 2
- [ ] Habit 3

## 📚 Reading Log

- Current book(s):
- Pages read today:
- Key takeaways or favorite quotes:

## 🏫 Daily Learning

What's one new thing I learned today?

## 🗒️Notes Created/Edited Today

```dataview
LIST FROM "" WHERE file.cday = this.file.day OR file.mday = this.file.day
SORT file.name ASC
```

## ✨ Daily Highlight

<% tp.system.prompt("What was the highlight of your day?") %>

## 📅 Tomorrow's Focus

- [ ] Task 1
- [ ] Task 2
- [ ] Task 3

## 🔁 Weekly Review Prep

<!-- Use this section to jot down points for your weekly review -->

---
