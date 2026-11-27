# 👋 Welcome to my app

```sql
SELECT * FROM projects WHERE id = 'study_buddy'
```
{: .query bind="projects" #my_project }

**{= my_project.first.name }** — {= my_project.first.story }

I chose this project because I'm learning Python, Java and JavaScript on my way to a job in IT, and I know what it feels like to be stuck on one exercise for hours. Usually somebody who learned it a few months earlier could explain it in ten minutes. I want to build the app I wish I'd had.

My aim: both. The social impact is free help for students and self-taught learners who can't pay for a tutor. The money comes from an optional paid tier where experienced mentors offer longer sessions and keep most of the fee.

My twist: Study Buddy for coding learners in my city. It matches a stuck learner with a peer who passed the same course or knows the same language (Python, Java or JavaScript), and it can match by the exact error message or exercise. Helpers earn badges they can show on their CV and LinkedIn, so helping others also helps them land a job.