# PROJECT OVERVIEW

## Purpose
The purpose of this project is to develop a full-stack application utilizing a database, user registration, login/authentication, etc, without following a tutorial from start to finish. 
I have already built several projects without using a tutorial, but they have all been relatively simple - such as a portfolio page, or a Hangman game with Javascript. 
I wanted this project to be a real challenge, and also something I would actually use. 

## Function 
One of the things I struggle with thanks to my ADHD is memory, and retrieving stored information. Because of that, I have a really hard time keeping track of when other people in my team are working. I always have to check the paper schedule, or ask others, and everyone else seems easily able to recall when someone would be in the office - but not me. So, my idea was an application that helps with that information that is readily available to anyone on the team. 

### Here is what I want my application to do: 

1. Allow a user to login, and allow the user to add their location, their job title, and their regular workings days and hours. For example:
   Name: Michael Brandon
   Title: Network Administrator
   Days: MTWRF
   Hours: 9AM-6PM
2. Allow a user to be added to a "Team" or Department within their organization. Ex, a Network Administrator might be added to the Administrators Team, but also the IT Department.
3. Provide users with a dashboard that organizes their teams/departments. Their management and higher level coworkers should be near the top and easily accessible, while lower-level workers will be sorted toward the bottom. This allows for easy reference if they need to escalate a situation.
4. On the dashboard, it should provide the following information at a glance:
   1. Who is currently "online" (aka within their normal working hours, on their normal working day)
   2. What their job title is (which should also be searchable on the dashboard, to filter results and only show employees matching that job title)
   3. Their name and location (for example, if they work on-site or remotely - no personal location data will be provided to a user)
5. A user should be able to click on the employee's dashboard row/card, which will expand a more detailed card including the following information:
   1. Their normal schedule (ex: MTWRF)
   2. Their normal working hours (ex: 9AM-6PM)
   3. Their email, which is clickable and will open the Compose window for their email application
   4. Their work extension, if applicable
   5. Their local timezone (especially for organizations with multiple sites)
6. With this, a user can easily see who in their organization they can contact and when.
7. The dashboard should also include the user's local time, so they can compare against who they want to contact: Ex, if the user is in California, and their local time is 4pm, but they are trying to reach someone in the EST timezone whose normal working hours are 8am-5pm, the user should be able to clearly tell that 1) The employee they want to reach is off work, 2) The local time where that employee is located (ex: it should display 7PM for that person, as EST is 3 hours ahead of PST), and 3) if the user chooses to attempt contact via email, a dialog box should show warning them that the employee they are trying to contact is not within their normal working hours, and may not respond.

## Why not just use Teams or WebEx status? 
First, those statuses are not reliable, as someone can show as online when they are not at their desk, or offline/idle despite being on shift. 
Second, this kind of application would have a wider use case than just being used to assist, say, IT workers with figuring out who they can escalate an issue to. 
I also used to work in a medical call center where we had to reach out to doctors who were on-call. Each practice had a different way of presenting their on-call schedule to us, and it was a hassle to try and read some of the unclear ways they would present that information. Ideally, this application could also be used as a way to track an on-call schedule that would be easily searchable by practice or specialty in various fields, from medical to IT to any other field where an on-call schedule might be necessary. 
