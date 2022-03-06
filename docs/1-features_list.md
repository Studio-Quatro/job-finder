# 1. Features list

[Back to home](../README.md) | [2 - First approach](2-first_approach.md)

According to [first meeting between David and client](meeting_memories/01.md), we built these preliminar analysis.

Two main profiles are CANDIDATES and EMPLOYEERS/RECRUITERS.

Candidates should be able to:

- Signup and login with email and password / social networks.
- Create a profile with education, skills, certifications and professional experience.
- Upload a CV in PDF format.
- Upload a video to his profile and to each job application.
- Upload documentation (like certifications or ID verifications). We should verify privacy here.
- Set his job preferences.
- Receive alert jobs that match with his preferences.
- Find jobs manually.
- Apply to jobs in website of in employeers website.
- See his application history.
- See his hiring proccesses.

Employeers should be able to:

- Create and modify companies profile (if demonstrates belonging to a company trough email verification or documentation).
- Create a "provisional"company if does not exists.
- Post new jobs (with skills, education, experience requirements and salary range).
- Find candidates ("only basic profile information is displayed and employers must pay before they can download CV and see personal information"). If employeers can see name and lastname, they could find people in social networks and contacts them outside of the platform.
- Create "hiring proccesses".
- Set state of candidate hiring proccess.
- See a job board to track all candidates proccesses.
- Chat with candidates inside platform.

Platform should:

- Use AI to match candidates and jobs.
- Offer gamification features (dashboards, leaderboards, points, etc.).
- Be prepared to i18n.

*Company profile*: Who are we, Values and Culture.  Also show company logo and photo
We could have a COMPANY ADMIN profile and this person can give access to post and edit jobs to other people. In this way, we can accept "recruiters" that manage more than one company.

*Hiring proccess* (applications model): Some steps like QUESTIONS, MEETINGS (HR, technical, etc), CHALLENGE, FINAL MEETING. Employeers can set every step posting a link and a description and set the progress of candidate.
Also, employeers can add private information in each step (only visible to employeers).
