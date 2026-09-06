# Group 4 Project Proposals


**Group Members:** Jaskaran Bhogal, Jonathan Peves, Matthew Motieram, Dev Mondal
**Platform:** Mobile Application

---


## 1. LeaseGuard


### Brief Description


A remote property-monitoring app for landlords who own or manage one or multiple rental units, often spread across different cities or states, and can't personally inspect each one on a regular basis. Landlords can create properties and units, set inspection schedules, and establish a move-in condition baseline that documents the property's initial condition for both the landlord and tenant. Tenants are prompted to photograph fixed areas of their unit — walls, floors, fixtures, and appliances — using guided camera prompts to help keep photos consistent between inspections. AI compares each submission against the unit's baseline, identifies visible changes, classifies them as likely normal wear or potential damage, and assigns a severity level. Higher-severity findings are flagged for landlord review. Tenants can also report maintenance issues during inspections, with AI helping categorize the issue, determine its urgency, and draft a maintenance request for the tenant to review before submitting. The system maintains a condition history for each unit, allowing landlords and tenants to review how the property's condition changes from move-in through inspections and move-out. 

### Existing Need / Problem


Landlords with multiple properties, especially ones they don't live near, have limited visibility into a unit's actual condition between move-in and move-out. They either trust the tenant, pay for a local inspector or property manager, or find out about a problem only when it has already become expensive. Tenants also have limited ways to consistently document pre-existing damage or property issues, which can make it difficult to show how a property's condition changed over time. There's no simple way to regularly document and compare a property's condition while giving both landlords and tenants a shared record. 


### Target Audience


Individual and small-portfolio landlords managing multiple rental units, particularly those with properties they can't easily visit in person, as well as tenants who want to document their rental's condition and report maintenance issues. 


### Five Unique Features / Epics


1. **Multi-property and unit management**
2. **Move-in condition baseline & Move Out condition** 
3. **Tenant photo submissions with AI condition assessment** 
4. **Severity-based review system** 
5. **Condition History**


### Technologies / Services


* React Native
* Python
* Django
* Django REST Framework
* MongoDB or PostgreSQL
* Gemini API or Claude API
* Celery & Redis
* Google Calendar integration
* GitHub
* GitHub Actions
* Figma


---


## 2. CampusCatch


### Brief Description


CampusCatch is a mobile application that allows college students and staff to report lost or found items on campus. Users can upload a photo, description, and location of an item. AI will compare lost and found reports to identify likely matches and notify users when a possible match is found.


### Existing Need / Problem


Most campus lost-and-found systems are difficult to search and rely on students physically checking security offices or lost-and-found locations. As a result, many items remain unclaimed. CampusCatch creates a centralized digital system where users can quickly report, search for, and receive notifications about lost or found items.


### Target Audience


College students, faculty, staff, and campus security personnel.


### Five Unique Features / Epics


1. **Lost and Found Reporting** — Users can create reports containing photos, descriptions, dates, categories, and locations.
2. **AI-Powered Item Matching** — AI compares images and descriptions from lost and found reports to identify likely matches.
3. **Smart Notifications** — Users receive push notifications when a potential match for their item is discovered.
4. **Search and Location Tracking** — Users can search reports and filter them by category, date, building, or campus location.
5. **Report Management** — Users can manage their reports, mark items as recovered, and automatically archive expired listings.


### Technologies / Services


* React Native
* Python
* Django
* Django REST Framework
* PostgreSQL
* Gemini API or Claude API
* Expo Notifications
* Celery
* Redis
* Google Maps API or Leaflet
* Firebase Storage or another cloud image storage service
* GitHub
* GitHub Actions
* Figma


---


## 3. StudySync


### Brief Description


StudySync is an AI-powered mobile application that helps college students find compatible study partners and organize study groups. The application matches students based on courses, availability, study preferences, and learning styles while providing AI-powered tools for studying and planning.


### Existing Need / Problem


Students often want to study with classmates but have difficulty finding people who share the same courses, schedules, or study habits. Even after forming a group, organizing notes, scheduling sessions, and preparing for exams can be difficult. StudySync combines study-group coordination with AI-powered academic tools in one platform.


### Target Audience


College and university students.


### Five Unique Features / Epics


1. **AI Study Partner Matching** — Matches students based on shared courses, schedules, study preferences, and learning styles.
2. **AI Notes and Quiz Generator** — Converts uploaded notes or images into flashcards, summaries, and practice questions.
3. **Smart Study Planner** — Creates personalized study schedules based on upcoming exams, quizzes, and assignments.
4. **Syllabus Scanner** — Extracts important dates from uploaded syllabi and automatically adds them to a student calendar.
5. **Study Group Collaboration** — Allows students to create groups, message members, schedule study sessions, share resources, and combine group notes into AI-generated study guides.


### Technologies / Services


* React Native
* Python
* Django
* Django REST Framework
* MongoDB
* Gemini API or Claude API
* Firebase Cloud Messaging
* Firebase Storage
* Celery
* Redis
* Google Calendar integration
* GitHub
* GitHub Actions
* Figma