**2.6.2 Core Functionalities - Student Interface**



**User Authentication \& Profile Management**

* System shall allow students to register using Seneca College email
* System shall authenticate users via Seneca SSO or email/password
* System shall allow students to create and edit personal profiles
* System shall support profile fields: name, program, year, bio, email, profile picture
* System shall allow users to set profile privacy (public/friends-only/private)
* System shall maintain user sessions with auto-logout after 30 minutes





**Event Discovery \& Search**

* System should display all published Seneca events in centralized feed
* The system should allow filtering by program (CPA, BSD, Nursing, etc.)
* System shall allow filtering by date range and location
* System shall display event cards with: title, date, time, location, category, RSVP count
* System should show "X students attending" and "X friends attending" on event cards



**Event Registration (RSVP)**

* System shall allow one-click RSVP to events
* System shall prevent RSVP when event reaches capacity
* System shall allow students to cancel RSVP before event
* System shall display RSVP confirmation message
* System shall generate QR code for event check-in after RSVP



**Social Features - Friends \& Connections**

* System shall allow students to add other users as friends
* System shall display friend requests with accept/decline options
* System shall show friends list on user profile
* System shall display which friends are attending each event
* System shall show peer avatars/names attending events (based on privacy settings)
* System shall suggest friend connections based on shared event attendance



**Event Chat \& Discussion**

* System shall create event-specific chat/discussion section for each event
* System shall restrict chat access to students who RSVP
* System shall support real-time messaging in event discussions
* System shall display chat participant names and profile pictures
* System shall timestamp all messages
* System shall allow students to post text messages
* System shall limit message length to 500 characters
* System shall allow users to delete their own messages



**My Events Dashboard**

* System shall display all upcoming RSVP events
* System shall display past events attended
* System shall show event status (upcoming, today, completed, cancelled)
* System shall provide quick access to event chat from dashboard
* System shall display QR code for upcoming events
* System shall show attendance history and statistics



**Notifications \& Alerts**

* System shall send email confirmation upon RSVP
* System shall send event reminder 24 hours before event
* System shall notify when a friend RSVPs to an event
* System shall notify of new messages in event chats
* System shall notify when event details are updated or cancelled
* System shall allow users to customize notification preferences
* System shall support email and in-app notifications





**2.7 Non-Functional Requirements**



**Performance**

* The system should load event listings and event details quickly under normal network conditions.
* Search and filtering features should respond without noticeable delay.
* The platform should support multiple users accessing the system simultaneously, especially during peak academic periods.



**Security**

* Only users with valid Seneca email accounts should be allowed to register and log in.
* Administrative features should only be accessible to authorized staff.
* All data transmitted between users and the system should be encrypted.
* The system should collect only necessary personal information required for functionality.



**Usability**

* The platform should be intuitive and easy to navigate without training.
* Students should be able to discover events, view details, and RSVP using minimal steps.
* Interface design should be consistent across all pages.
* The system should function smoothly on both desktop and mobile browsers.



**Accessibility** 

* The platform should follow web accessibility best practices.
* The interface should support screen readers and keyboard navigation.
* Text and interface elements should maintain clear readability and contrast.
* Reliability
* The system should operate with minimal downtime during the academic semester.
* Event data, user profiles, and participation records should be stored reliably.



**Maintainability** 

* The system should be built using modular components to allow future updates.
* Code and system structure should support easy maintenance and improvements.



