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

## Participants Part

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


## Organizers Part

### Screen 1: Homepage
#### Description:
The first page users typically encounter serves as a gateway for various roles within our platform. Whether you're a competition creator, coach, or judge, this page provides tailored pathways to meet your needs.

Hackathon Creator: If you're looking to organize a hackathon, head to the "Hackathon Creator" section. Here, you'll find tools and resources to initiate and manage your competition effectively.

Expert Access: Are you a coach or judge? Navigate to the "Expert" section for access to pertinent features and information. This area caters to individuals involved in guiding participants or evaluating submissions.

Insights and Information

Beneath these user-specific sections, you'll find valuable insights and information to enhance your experience:

=> Reserved Hackathons Calendar: Stay informed about already booked dates by other creators. This feature prevents scheduling conflicts and ensures smooth coordination of events.

=> Endorsed Judges and Coaches: Discover recommended coaches based on their past experiences and contributions to the platform. Find mentors with proven track records or those already active within our community.

=> Frequently Asked Questions: Have questions? Check out our FAQ section for answers to common queries and helpful guidance on navigating our platform.

=> MIA Organisation.

=> License.

![Organiser - First Page](https://github.com/safae-rabbouzi/Competition-website/assets/108349017/2721aa8e-d403-4c23-943c-83dcca577ff5)


### Screen 2: Request Form
#### Description:
Creators submit their request by providing their information and details of the proposed hackathon. Once the form is filled out, it is sent to the organizer for review and processing. Creators receive notifications about the status of their request. 

![Organiser - Request](https://github.com/safae-rabbouzi/Competition-website/assets/108349017/c8c796e8-06ae-48c0-94a7-32a50b57aaba)

### Screen 3: Request Confirmation Page
#### Description:
The creator receives a message confirming the successful submission of their request. They are informed that their request has been successfully transmitted and are prompted to check their email. It is indicated that a response will be sent within the next 15 days.

![Organiser - Request (1)](https://github.com/safae-rabbouzi/Competition-website/assets/108349017/fddb6c42-56a1-488b-a7ca-64e40bbdd57a)

### Screen 4: Competition Details Page
#### Description:
After receiving confirmation of the validation of their request, the creator must now provide additional information about their competition, including:

Competition Name: The title of the competition.

Description: A brief description explaining the content and purpose of the competition.

Hosting Organization Name: The name of the organization hosting the hackathon.

Contributors: The names of contributors or partners involved in the competition.

Manager's Email Address: The email address of the manager or coordinator of the competition.

Competition Tags (Themes): Tags or themes that describe the nature or subject of the competition.

Date and Time: The start and end dates and times of the competition.

Hackathon Target Audience: The target audience or demographic group for the competition.

Competition URL: The URL where participants can find more information about the competition.

Photo and Cover: Representative or promotional images of the competition.

![Frame 14](https://github.com/safae-rabbouzi/Competition-website/assets/108349017/80977df6-90cb-4eb6-8bee-a026d6785da9)

### Screen 5: Hackathon Steps/Hackathon Requirements Page
#### Description:
On this page, Hackathon organizers need to specify various requirements and constraints for the competition:

=> Participant Age Range: Define the minimum and maximum age limits for participants.

=> Background Constraints: Outline any background requirements or constraints participants must meet.

=> Geographic Constraints: Specify any geographic limitations or requirements for participants.

=> Restricted Materials: Identify any materials or resources that are prohibited during the competition.

=> Gender Specification: Indicate if the competition is open to all genders, restricted to a specific gender (e.g., "for girls only"), or if there are no gender specifications.

![Create a hackathon- Hackathon -Requirements](https://github.com/safae-rabbouzi/Competition-website/assets/108349017/c4bf2d8a-8fb5-48cf-9d0f-75415c5bbae6)

### Screen 6: Hackathon Steps/Hackathon Coaches Page
#### Description:
On this page, the competition creator must select the coach corresponding to their competition:

Required Profi Hackathon Steps/Hackathon Coaches Page

On this page, the competition creator must select the coach corresponding to their competition:

Required Profiles: Define the necessary profiles or qualifications for coaches participating in the competition.

Tags: Use tags to categorize coaches based on their expertise or skills.

Announcing the Requirement for a Coach: Provide a clear description for your announcement, detailing the specific requirements and expectations for coaches in the competition.

Invite a Coach: Enter the coach's email or username and add a comment for your invitation. This comment can include additional information or instructions for the invited coach.

Pending Invitations: View a list of pending invitations to coaches. This section displays invitations that have been sent but have not yet been accepted or declined by the invited coaches.les: Define the necessary profiles or qualifications for coaches participating in the competition.

Tags: Use tags to categorize coaches based on their expertise or skills.

Announcing the Requirement for a Coach: Provide a clear description for your announcement, detailing the specific requirements and expectations for coaches in the competition.

Invite a Coach: Enter the coach's email or username and add a comment for your invitation. This comment can include additional information or instructions for the invited coach.

Pending Invitations: View a list of pending invitations to coaches. This section displays invitations that have been sent but have not yet been accepted or declined by the invited coaches.

![Create a hackathon- Hackathon - Coaches](https://github.com/safae-rabbouzi/Competition-website/assets/108349017/cf3c46f6-27bd-41bc-9588-f0c4a6418d5d)

### Screen 7: Hackathon Steps/Validation Steps
#### Description:
On this page, the hackathon creator can outline the steps that participants need to follow:

Add a Step: To add a new step, click on the "Add Card" button. Provide a title for the step and enter a description. Optionally, attach a document or provide a link for participants to follow.

Toolbar: Utilize the toolbar to enhance your steps. You can add a cover, template, photo, or link to provide additional context or resources for participants.

Untitled Step: Enter the title for each step, along with a description detailing the actions or tasks participants need to complete.

Save: Once all steps have been added, click on the "Save" button to save the validation steps for participants to follow during the hackathon.

![Create a hackathon- Hackathon - Validation Steps - initial Step](https://github.com/safae-rabbouzi/Competition-website/assets/108349017/d18b370b-ce82-42ac-8e0e-35bba42ea9ff)

### Screen 8: Submission Preferences
#### Description:
On this page, the creator specifies whether they want submissions in the form of a presentation, GitHub repository, or demo:

Submission Format: Choose the preferred format for submissions. Options include: (examples) Presentation: Participants submit their work in the form of a presentation or slide deck. GitHub Repository: Participants share their code and project documentation via a GitHub repository. Demo: Participants demonstrate their project through a live presentation or video demonstration. Save: After selecting the submission preferences, click "Save" to confirm the settings.

![Create a hackathon- Hackathon - Submission](https://github.com/safae-rabbouzi/Competition-website/assets/108349017/c78189e8-2f3e-4cba-a6f8-8945730ce828)

### Screen 9: Hackathon Steps/Prizes
#### Description:
On this page, the creator outlines the prizes for the first, second, and third winners of the hackathon, as well as additional prize categories:

First Prize: Specify the prize for the first-place winner.

Second Prize: Define the prize for the second-place winner.

Third Prize: Outline the prize for the third-place winner.

Toolbar: Utilize the toolbar to add additional prize categories if the creator wishes to include more options.

Save: Once all prize details have been added, click "Save" to finalize the prize settings for the hackathon.

![Create a hackathon- Hackathon -  Prize - Intermediate Page](https://github.com/safae-rabbouzi/Competition-website/assets/108349017/24853ff0-9acb-4fab-b819-402345c611b4)
     
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
-RABBOUZI Safae
-Intissar el bouzyani 
-Hajar Hamdaoui


