# Competition Management Platform (Incomplete)

## Table of Contents
1. [Overview](#overview)
2. [Design Overview](#design-overview)
3. [Features](#features)
4. [Technologies Used](#technologies-used)
5. [Usage](#usage)
6. [Contributors](#contributors)

## Overview
This project aims to develop a web application for managing competitions where users can participate in competitions and organizers can create and manage competitions. The platform will provide a centralized system for handling all aspects of competitions, including registration, submission of entries, judging, and result announcements.

## Design Overview

### Screen 1: Homepage
#### Description:
The homepage is designed to accommodate both participants and organizers. It features distinct sections for joining a competition and adding a new competition.

1. **Join a Competition Section**: This section targets participants, encouraging them to explore available competitions and register to participate. It showcases featured competitions and provides quick links to browse and join competitions of interest.

2. **Add a New Competition Section**: Organizers are prompted to add a new competition through this section. A call-to-action button directs organizers to the competition creation form, where they can input competition details and requirements.

3. **List of Competitions**: Following the introduction sections, there's a list of competitions available on the platform. Each competition entry includes essential details such as the competition name, description, deadline, and a button to view more details.

4. **FAQ Section**: To address common queries and provide additional information, a frequently asked questions (FAQ) section is included at the bottom of the homepage. Users can find answers to questions regarding competition rules, submission guidelines, and platform usage.
   
![Home page](https://github.com/DesignToWebsite/Competition-website/assets/74991230/1d5806f4-ae72-4fde-9afd-0d0a2c56f700)

### Screen 2: Competitions Page
#### Description:
The Competitions page serves as a centralized hub where users can discover all available competitions and search for specific ones.

1. **List of Competitions**: The page displays a comprehensive list of competitions hosted on the platform. Each competition entry includes essential details such as the competition name, description, deadline, and a button to view more details or register.

2. **Search Functionality**: Users can utilize a search bar to find competitions based on specific keywords, such as competition name, category, or organizer. The search functionality enhances user experience by allowing users to quickly locate competitions of interest.

3. **Filtering Options**: Additionally, filtering options are provided to enable users to refine their search results further. Users can filter competitions based on criteria such as competition type, deadline, or popularity.

4. **Pagination**: To manage large datasets of competitions effectively, pagination controls are implemented, allowing users to navigate through multiple pages of competition listings.

5. **Navigation Menu**: A navigation menu is available to facilitate seamless exploration of other sections of the platform, such as the homepage, participant dashboard, and competition creation form.

![hackathons](https://github.com/DesignToWebsite/Competition-website/assets/74991230/109d5a53-5fb8-45ac-9295-6b99ea8f5715)

### Screen 3: Competition Details Dashboard
#### Description:
The Competition Details Dashboard provides users with comprehensive information about a specific competition. Depending on the user's role (participant or non-participant), different sections are accessible.

1. **Overview**: 
   - Non-participants and participants alike have access to the overview section, which provides a summary of the competition, including its purpose, theme, and key dates.

![competition overview](https://github.com/DesignToWebsite/Competition-website/assets/74991230/aabe9b09-6bbe-4ba5-8f4b-c56803ecfd4e)

2. **Resources**: 
   - Non-participants and participants can access resources related to the competition, such as reference materials, guidelines, or external links.
  
![competition Ressources-1](https://github.com/DesignToWebsite/Competition-website/assets/74991230/99153d29-d6e6-46ac-b7fc-36c30810201d)

3. **Rules**: 
   - Both non-participants and participants can review the rules and regulations governing the competition, ensuring transparency and fair play.
   
     ![competition projects](https://github.com/DesignToWebsite/Competition-website/assets/74991230/a2544f0a-c366-42e9-b4c1-7b3351c91beb)

4. **Project Gallery**: 
   - Non-participants and participants can view a gallery showcasing projects submitted by participants. This section serves as inspiration and showcases the creativity and diversity of submissions.
     
  ![gallery](https://github.com/DesignToWebsite/Competition-website/assets/74991230/a780d8a5-a9d9-4542-b043-029541b7358d)

5. **Participants** (Accessible to Participants Only): 
   - Participants have the additional privilege of viewing a list of other participants involved in the competition. This allows participants to connect with peers, collaborate, or gather insights.
     
   *Not a participant :*
   
![competition participant](https://github.com/DesignToWebsite/Competition-website/assets/74991230/1913a4d8-1ae1-4398-a8e9-1f322d4b890c)

  *A participant :*
  
![Participant](https://github.com/DesignToWebsite/Competition-website/assets/74991230/6ced6de6-92ed-4952-a653-69adbf561311)



7. **Discussion Section**:
   - A discussion section is available where participants can ask questions related to the competition. Participants can post their queries, and organizers can provide answers, facilitating communication and clarifications.

![Disscussion](https://github.com/DesignToWebsite/Competition-website/assets/74991230/008f62c1-97b6-4d4c-9b89-ce4898d3d686)

8. **My projects** (Accessible to Participants Only): 
   - Participants are provided with the functionality to create and submit their projects directly from the dashboard. They can input project details, upload files, and submit their entries seamlessly.
     
### Project Creation and Submission Process

1. **Join the Hackathon**: 
   - As a participant, the first step is to join the hackathon by registering for it through the platform.
  
![competition review project](https://github.com/DesignToWebsite/Competition-website/assets/74991230/080db522-94cf-446e-a52b-1c371d7f428d)

2. **Create a Project**: 
   - Once registered, participants can create a project for the hackathon. This involves providing general information about the project, such as the project name, category, and team members (if applicable).

![no project exist in hakathon](https://github.com/DesignToWebsite/Competition-website/assets/74991230/e8f414fe-3148-42f5-983e-79d86ff8ecd0)

3. **Project Overview**: 
   - After creating the project, participants will provide an overview of their project. This includes a brief description of the project, its objectives, and any other general information.
     ![Project etape 1](https://github.com/DesignToWebsite/Competition-website/assets/74991230/1dda62a9-bb91-40ef-918e-c9e969c7631b)


4. **Project Details**: 
   - Participants can then delve deeper into the project by adding project details. This may include the project story, explaining the inspiration behind the project, the technologies used, and any challenges faced during development.
     
![Project etape 2](https://github.com/DesignToWebsite/Competition-website/assets/74991230/ed47b996-03b9-43fb-91c4-134f8bcae94c)

5. **Additional Info**: 
   - Participants have the option to provide additional information about their project, such as project documentation, demo videos, or external links to repositories.
     
![Ptoject 3](https://github.com/DesignToWebsite/Competition-website/assets/74991230/7959bfca-ca53-4f64-b144-76b30cebb9fc)

6. **Submit Project**: 
   - Once all necessary information is added, participants can submit their project for review by the organizer. This action signifies the completion of the project creation process
     
![project 4](https://github.com/DesignToWebsite/Competition-website/assets/74991230/8ff0812f-2508-41ea-9744-c49cc81430ac)

7. **Review and Approval by Organizer**: 
   - The submitted projects are then reviewed by the organizer. The organizer may have additional steps or requirements for participants to fulfill before their projects are approved.

8. **Team Member Addition**: 
   - Participants can also add members to their project team if they wish to collaborate. This step allows for teamwork and enhances the project's scope and capabilities.
     
![add team](https://github.com/DesignToWebsite/Competition-website/assets/74991230/e297069f-116f-4fe6-8ad3-11fe7fd16198)


### Projects Page
#### Description:
The Project Page serves as a central repository where all submitted projects for the hackathon are showcased. Participants and organizers can browse through the projects, view their details, and engage with the project creators.

1. **Project Listings**: 
   - The page displays a comprehensive list of all submitted projects. Each project entry includes details such as the project name, team members, project category, and a brief description.

2. **Project Details**: 
   - Clicking on a project entry expands it to reveal more detailed information about the project. This includes the project overview, project story, additional information, and any attached resources or links.

3. **Search and Filter**: 
   - Participants and organizers can utilize search and filter functionalities to narrow down the list of projects based on specific criteria such as project name, category, or team members.

4. **Engagement Options**: 
   - Users can interact with projects by liking, commenting, or sharing them. This fosters community engagement and encourages collaboration and feedback among participants.

![Projects](https://github.com/DesignToWebsite/Competition-website/assets/74991230/102685d9-0a82-41c1-b9e9-2786866bfcfd)


### Project Story Page
#### Description:
The Project Story Page is dedicated to showcasing the detailed narratives and stories behind each project submitted for the hackathon. It provides participants with a platform to share their journey, challenges, and inspirations throughout the project development process.

1. **Project Story Listings**: 
   - The page displays a curated collection of project stories submitted by participants. Each story entry includes the project name, team members, and a narrative describing the project's journey, challenges faced, and lessons learned.

2. **Detailed Narratives**: 
   - Clicking on a project story expands it to reveal the detailed narrative provided by the project creator. This may include insights into the project's conception, development milestones, technical aspects, and personal reflections.

3. **Engagement Options**: 
   - Users can engage with project stories by leaving comments, sharing their thoughts, or expressing appreciation for the project creators' efforts and storytelling.

![Project](https://github.com/DesignToWebsite/Competition-website/assets/74991230/e5bef536-640f-4f2a-aa26-66094ae27427)

     
## Features (Incomplete)
- **User Registration and Authentication**: Users can register for an account and authenticate to access the platform.
- **Competition Creation**: Organizers can create competitions by providing details such as competition name, description, rules, deadlines, etc.
- **Competition Management**: Organizers can manage competitions, including adding judges, setting judging criteria, managing submissions, etc.
- **Participant Registration**: Users can register to participate in competitions by submitting their entries and required information.
- **Submission Management**: Participants can submit their entries for competitions, and organizers can manage and review submissions.
- **Judging Process**: Judges can evaluate submissions based on predefined criteria, and organizers can manage the judging process.
- **Result Announcement**: Organizers can announce competition results, and participants can view their standings.

## Technologies Used (Incomplete)
- **Frontend**: React.js is used for building the frontend user interface of the web application. It provides a dynamic and responsive user experience.
- **Backend**: ASP.NET is used for developing the backend server-side logic and APIs required for data processing, authentication, and communication with the database.
- **Database**: SQL Server or another suitable relational database management system (RDBMS) is used for storing user data, competition details, submissions, judging criteria, etc.

## Usage (Incomplete)
Provide instructions on how to set up and run the project locally for testing and development purposes.

## Contributors (Incomplete)
-Essoussi Zineb
-Safae Rabouzi
-Intissar 
-Hajar Hamdaoui


