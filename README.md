

Undergraduation.com Admin Dashboard (Technical Task)

A technical task for Undergraduation.com involved creating this straightforward internal CRM dashboard.  
The internal team can access a centralized view of students, their progress, and their communication history.



 Features :

 The Students Directory
- Table of students with:
  - Name, Email, Country
  - Application Status (“Exploring”, “Shortlisting”, “Applying”, “Submitted”)
  - Last Active date
- Filters and search
- Click to open individual profile

Student Profile
- Shows student basic info: name, email, phone, grade, country
- Application progress bar based on status
- Interaction timeline (mocked events: logins, AI questions, uploads)
- Communication log (add/view/delete messages)
- Internal notes (add/edit/delete notes)
- Communication tools:
  - Manual logs
  - Trigger follow-up email (mock)
  - Schedule reminders (stored in Firestore)
- (Bonus) AI Summary placeholder

 Insights
- Quick filters:
  - Students not contacted in 7 days
  - High intent (Applying/Submitted)
  - Needs essay help (mock)
- Displays summary stats (# active students, # in essay stage, etc.)



 Tech Stack :
- **Frontend:** Next.js (TypeScript)
- **Backend/Data:** Firebase (Firestore + Auth)
- **UI:** React components
- **State/Data fetching:** React Query
- **Forms & validation:** Zod
- **Styling:** TailwindCSS

 Setup Instructions

1. I Cloned the repo:
   ```bash
   git clone https://github.com/YOUR_USERNAME/undergrad-admin.git
   Then use cd undergrad-admin to get into undergrad-admin directory