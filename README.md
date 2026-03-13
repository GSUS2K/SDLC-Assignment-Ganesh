# SDLC-Assignment-Ganesh
Agile pivot plan for student attendance app!

Here are my files for the "Release Manager" Roleplay assignment for SDLC & DevOps Fundamentals.

### Files
* `Analysis.pdf` - This has my breakdown of why Waterfall fails here and how we pivot to Agile. 
* `Backlog.csv` - This is the Sprint 1 Backlog with the User Stories and estimated hours.

### Why CI/CD is important for our Agile Sprints

Using Continuous Integration and Continuous Deployment (CI/CD) is basically required if we want to push these Sprint updates to students automatically. Here's why:

1. **Continuous Integration (CI):** When we start working on Sprint 2 (the Face ID update), devs are going to be adding a lot of new code. CI automatically runs tests every time new code is pushed. This makes sure that the new Face ID stuff doesn't accidentally break the Geo-fencing feature we already built in Sprint 1.
2. **Continuous Deployment (CD):** Instead of manually updating the app stores and making students reinstall or download complicated updates, CD does it automatically. Once the CI tests pass, CD pushes the update out so students get the Face ID feature smoothly without any downtime.
3. **Faster Feedback:** In Agile, we need feedback quickly. CI/CD lets us push out the MVP at the end of Sprint 1 straight to the users and stakeholders (like the Dean). That way, we get their feedback early and can make changes during Sprint 2.
