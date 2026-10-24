# VibeCheck | Music Discovery & Group Event Voting



## Project Overview

VibeCheck is a collaborative full-stack web application that helps friends discover live music events based on their music preferences and vote together on which events to attend.

The application brings together music preference data and live event information to help groups find events that match their shared interests. Developed as part of the FSCJ CEN4940 Application Development Capstone during Summer 2026, the project involved a nine-member team working across frontend development, backend services, external API integrations, authentication, and database functionality.

<img width="840" height="525" alt="image" src="https://github.com/user-attachments/assets/8915d620-f57b-4f4c-89a4-12bdae85feb9" />


## The Problem

Planning a concert or live music event with a group can be challenging when everyone has different music preferences. Searching for events individually does not always make it easy to identify options that appeal to the group or reach a shared decision.

VibeCheck addresses this challenge by using music preference data to identify relevant events and providing a group voting process to help users decide which event to attend.

## Key Features

- **Music Profile Integration:** Connects users' Last.fm accounts to retrieve music preferences and tags.
- **Group Management:** Allows users to create groups and invite others to participate.
- **Event Matching:** Uses music preferences and Ticketmaster event data to identify relevant live events.
- **Group Voting:** Allows members to vote on matched events and view the group's result.
- **User Authentication:** Uses JWT-based authentication and Spring Security to protect application functionality.
- **Event Discovery:** Helps users explore matched events and access ticket information.

## My Contributions

**Role: Full-Stack Developer | Backend Integration Engineer**

My primary focus was supporting the Last.fm integration and music profile functionality. This work required coordinating external music data with the application's backend and existing Supabase PostgreSQL database structure.

- **External API Integration:** Contributed to integrating Last.fm music data into the application's backend workflow to support user music profiles.
- **Data and Schema Alignment:** Verified that the structures used by the Last.fm integration aligned with the application's existing database schema.
- **Database Updates:** Made changes to the Supabase PostgreSQL database to support the music profile integration and its data requirements.
- **Data Integrity:** Helped ensure imported music preference data could be stored and used consistently within the application's existing data model.
- **Backend Integration:** Worked across external API data, backend services, and database persistence to support the music profile workflow.

This experience strengthened my understanding of relational databases, SQL, data structures, data consistency, and the challenges involved in connecting external systems to an existing application.

## Skills Demonstrated

- **Data Management:** Relational database structures, schema alignment, and data consistency.
- **SQL and Databases:** Working with Supabase PostgreSQL to support application data requirements.
- **API Integration:** Connecting external music data from Last.fm with backend application functionality.
- **Data Integrity:** Supporting consistent storage and use of imported music preference data.
- **Technical Problem-Solving:** Identifying and addressing alignment between external data structures and existing database requirements.
- **Peer Review and Feedback:** Reviewing teammates’ work, incorporating feedback, and collaborating to improve code quality and project consistency.
- **Team Collaboration:** Coordinating with a nine-member development team across backend integration, database functionality, and application development.
- **Documentation and Communication:** Communicating technical decisions, documenting project functionality, and explaining implementation considerations.

## Technical Challenges and Considerations

### Aligning External Data with the Database

Integrating an external API requires more than retrieving information. The incoming data must fit the application's data model and be stored in a way that supports consistent use across the system.

My work involved checking the relationship between Last.fm data structures and the existing database schema, then making database adjustments to support the integration.

### Supporting Future Integrations

As the application evolves to incorporate additional external services, maintaining consistency across data sources will become increasingly important.

One concept considered for future integrations was a **database historian**: a centralized approach to retaining historical information about data changes, imports, or integration activity. Depending on the implementation, this could help the team trace changes over time, investigate data inconsistencies, and understand how external data has changed.

This was considered as a potential future enhancement, rather than a feature currently implemented in VibeCheck.

## Technology Stack

- **Frontend:** Angular, TypeScript
- **Backend:** Java, Spring Boot
- **Database:** Supabase-hosted PostgreSQL
- **Data Access:** Spring Data JPA
- **External APIs:** Last.fm and Ticketmaster
- **Authentication and Security:** Spring Security and JSON Web Tokens (JWT)

## Future Enhancements

Potential areas for continued development include:

- Exploring a database historian or similar data history solution to support future integrations and improve traceability.
- Expanding music and event recommendation capabilities.
- Improving data validation and consistency across external data sources.
- Adding song previews and other music discovery features.
- Exploring mobile-friendly experiences and location-based event discovery.
- Improving database migration and change-management practices as the application grows.

## Project Materials

### Landing Page

<img src="https://github.com/user-attachments/assets/3f04817b-9025-4301-9f7c-d0971f576287" width="700" alt="VibeCheck Landing Page" />

### Sign In

<img src="https://github.com/user-attachments/assets/a5c3f236-d5aa-41b1-b765-3d7890b4738f" width="700" alt="VibeCheck Sign In Screen" />

### Last.fm Connection Screen

<img src="https://github.com/user-attachments/assets/d3c276a0-9e66-4c76-bdcd-1cc77f2c654a" width="700" alt="Last.fm Connection Screen" />

### Dashboard

<img src="https://github.com/user-attachments/assets/a88a1d3d-5fbc-4abd-be0b-4992d2c6f868" width="700" alt="VibeCheck Dashboard" />

### Profile and Settings

<img src="https://github.com/user-attachments/assets/17f817c9-00ba-48f1-a7c0-1cadaaee8e92" width="700" alt="Profile and Settings" />

### Groups

<img src="https://github.com/user-attachments/assets/cccc4333-7c4b-4305-ac2f-a3f08c616c79" width="700" alt="Group Management and Invitations" />

Groups can be created and shared with friends using a unique group code. Friends can join by entering that code.

### Matched Events

<img src="https://github.com/user-attachments/assets/e3227ae0-e87e-4efa-a0b4-9b1b888950e9" width="700" alt="Matched Events and Voting" />

Events that better match the group's combined music preferences receive higher scores and appear first in the voting flow. Members can vote on multiple events.

### Winning Event

<img src="https://github.com/user-attachments/assets/85db4603-85f8-4b80-8ca7-b0b28847dd38" width="700" alt="Winning Event Results" />

When voting ends, the winning event is revealed based on the group's voting results.

### Tickets

<img src="https://github.com/user-attachments/assets/fe962126-b588-454f-96fc-b34c153c4726" width="700" alt="Ticketmaster Link for the Selected Event" />

Selecting **Buy Tickets** redirects users to the Ticketmaster page for the selected event.
## Team Contributors

VibeCheck was developed collaboratively by a nine-member team as part of the FSCJ CEN4940 Application Development Capstone during Summer 2026. Team members contributed across frontend development, backend integration, authentication, database functionality, event matching, group management, and voting.

[Lauren Knotts](https://github.com/KnottsLauren) — Team Lead, Frontend Development, Branding and UX, Group Voting

[Dewey Mccrary](https://github.com/DeweyM1) — Co-Lead,Full Stack Development,   Authentication and Security

[Ricardo “Ricky” Serrano](https://github.com/RickySerrano904) — Backend Lead, Event Matching, Ticketmaster Integration, Database Design

[Shawn “Hayden” Sullivan](https://github.com/shsullivan) — Full Stack Development, Database Engineering, Event Matching, Group Voting

[Dayne Allen-Wright](https://github.com/MasterShakespearian) —Full Stack Development,  Authentication and Security, Application Themes

[Tatyana Wells](https://github.com/TatyBuilds) — Full-Stack development, Last.fm Integration, Music Profile Management, Backend Integration, 

[Anthony Greene](https://github.com/1AnthonyGreene) — Backend Development,Last.fm Integration, Music Profile Management

[Tamia Jenkins](https://github.com/FireSagg)— Frontend Development, Group Creation and Invitation System

[Baudelaire Messago Ngumouo](https://github.com/S3771361) — Backend developement, Group Creation and Invitation System

## Portfolio Note

This repository presents VibeCheck as a portfolio case study. The complete application source code is not included in this repository. The project was developed collaboratively, and the contribution summary focuses on the work I performed.



