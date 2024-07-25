# FORUS: FOCUSED OPERATIONAL RESEARCH AND UNIFIED SYSTEMS

![image](https://github.com/user-attachments/assets/5fdcbf21-6dec-4e3e-a74c-86f0551da796)

## Introduction

FORUS (Focused Operational Research and Unified Systems) is a comprehensive solution for crowd-sourced disaster management. It leverages modern technology to provide real-time information, coordination, and resource management during disasters. Our platform integrates data from multiple sources to enhance situational awareness and improve response efforts. The system integrates several components, including Inventory Management, Camp Management, Rescuer App, Public App, Validation Engine, and Precautionary Disaster Response System (PDRS), to streamline operations and ensure effective disaster management.

## Key Features

- **Crowd-Sourced Data Collection**: Real-time data collection from users on the ground.
- **Integrated Communication Tools**: Facilitates coordination between various disaster response teams.
- **Resource Management**: Efficiently tracks and allocates resources where they are needed most.
- **Real-Time Analytics**: Provides actionable insights through data analysis and visualization.
- **User-Friendly Interface**: Intuitive design for ease of use by both professionals and volunteers.

## Necessity of FORUS

1. **Efficient Resource Management:** FORUS provides a structured approach to managing and allocating resources. Supplies are distributed based on the real-time needs of the camps and the public. This helps minimize wastage and provides timely support to affected regions.

2. **Real-Time Updates and Coordination:** The PDRS system helps government officials identify disasters early, allowing for rapid response and coordination among various stakeholders, including NGOs, NDF, and field workers.

3. **Public Engagement:** The Public App enables the public to donate money or send goods to someone who has requested them, facilitating a peer-to-peer connection even via SMS when the internet is down.

## System Architecture

![image](https://github.com/BlackEmpir7199/FORUS/assets/118678415/0e1bc4ae-3214-4fb0-bdb0-5069177b2b0b)

The architecture of FORUS is designed to be robust and scalable, ensuring efficient data collection, processing, and dissemination during disaster situations. The key components include:

1. **Data Collection Layer:** Collects data from various sources, including mobile apps, sensors, and social media.
2. **Processing Layer:** Processes and analyzes the collected data using machine learning models.
3. **Communication Layer:** Facilitates communication and coordination between different stakeholders.
4. **Resource Management Layer:** Manages the allocation and tracking of resources.
5. **Visualization Layer:** Provides real-time analytics and visualizations to aid decision-making.

## Components

### Inventory Management System

**Overview:**
The Inventory Management System serves as the backbone of the disaster response framework, facilitating efficient management and allocation of resources to rescue camps. 

**Features:**
- **Dashboard:** Centralized monitoring system integrating PDRS results, camp details, supply status, and intensity data with heat maps and visualizations.
- **Data Entry:** Manual entry of warehouse inventory for accurate tracking.
- **Supply Management:** Monitors and tracks rescue camp requests and capacities, allocates supplies based on demand and demography insights, and features an encrypted communication channel for bureaucratic approval.
- **Request Supplies:** Monitors supply updates, posts requests to the public app and social media for visibility, and supports sharing options for public engagement.
- **Money Manager:** Manages financial donations using intelligent rule-based algorithms, provides a money planner tool for efficient goods procurement, and supports incentives and aid distribution.

**Stakeholders:**
- Inventory Managers: Utilize the app for resource management and allocation.
- Government and NGOs: Oversee and coordinate disaster response efforts.
- Tier 1 Operators (e.g., DRDO): Collaborate in resource distribution and logistics management.

### Camp Management System

**Overview:**
The Camp Management System is crucial for managing rescue camps, facilitating coordination, resource allocation, and real-time decision-making during disasters.

**Features:**
- **Dashboard:** Provides an overview of camp capacity, needs, and critical updates for camp supervisors.
- **Data Entry:** Real-time data input on camp conditions, including population, health status, and resource requirements.
- **Supply Management:** Manages inventory supplies within camps, sends supply requests based on requirements, and facilitates distribution within and between camps.
- **Alerts & Notifications:** Receives alerts from the People App regarding urgent needs and notifies rescuers for timely response.
- **Validation Engine:** Validates user requests to ensure authenticity and prioritizes response based on urgency.

### Rescuer App

**Overview:**
The Rescuer App is a vital tool for field workers during rescue and relief operations.

**Features:**
- **Rescue Allocation System:** Efficiently allocates rescue tasks based on real-time updates.
- **Alerts & Notifications:** Receives alerts about individuals needing rescue or urgent assistance.
- **Safety Monitoring:** Tracks the location of field workers in real-time for their safety and security.
- **Camp Monitoring:** Allows rescuers to monitor camp activities and make informed decisions about resource allocation.
- **Feedback Mechanism:** Enables field workers to provide feedback on rescue operations and camp conditions.
- **Integration with Validation Engine:** Utilizes feedback to cross-check and verify donation needs posted by users.

### Public App

**Overview:**
The Public App, also known as the People's App, serves as a platform for individuals to contribute to disaster relief efforts and access real-time updates.

**Features:**
- **Donate Option:** Enables users to make donations with a secure payment gateway.
- **Request Option:** Allows individuals to request essential goods or assistance, with requests undergoing cross-verification.
- **Information & Updates:** Offers frequent updates on disaster situations and relief efforts.
- **Feedback Mechanism:** Enables users to provide feedback on critical areas and disaster intensity.
- **Re-share Option:** Allows users to share donation requests on social media for increased visibility.
- **Volunteer Option:** Enables camps to post volunteer requirements, and users can volunteer to assist in relief efforts.

### Validation Engine

**Overview:**
The Validation Engine ensures the accuracy and integrity of all processes and data.

**Components:**
- **Data Sources:** Utilizes demographic data, historic disaster records, and population statistics to assess risk and severity.
- **Feedback Integration:** Integrates feedback from inventory and camp management systems to validate resource allocation decisions.
- **User Feedback Analysis:** Incorporates feedback from rescuers and users for real-time validation of user-reported information.
- **Algorithmic Framework:** Uses APIs, AI, and rule-based algorithms for data processing and analysis.
- **External Cross-Checking:** Conducts external validation through social media and other sources.
- **Collaborative Approach:** Works with other system components for effective validation processes.

### Precautionary Disaster Response System (PDRS)

**Overview:**
PDRS uses various methods to scrape data and identify potential disasters early on. It then assesses the population in the affected region and formulates a detailed first responders plan, integrated with the inventory management system.


## Conclusion

FORUS stands out in the disaster management landscape due to its integrated approach, real-time data processing, and proactive disaster response capabilities. Its validation engine and public engagement features further enhance its effectiveness, making it a superior solution compared to existing competitors. By addressing the critical needs of resource management, coordination, and transparency, FORUS significantly improves disaster response and resilience.
## Roadmap

### Phase 1: Initial Development (26th June 2024)
- ✅ Complete system architecture design
- Implement core features:
  -  Inventory Management System
  - ✅ Camp Management System
  -  Rescuer App
  - ✅ Public App
  - ✅ Validation Engine
  - ✅ Precautionary Disaster Response System (PDRS)

### Phase 2: Enhancements and Integrations (14th July 2024)
- 🔲 Four Layer Fallback idea change
- ✅ Add more integrations:
  - Social media platforms (twitter.com/x.com)
  - External data sources (weather, seismic activity, etc.)
- ✅ User interface improvements based on feedback
- ✅ Initial deployment of app as .apk for testing on various devices

### Phase 3: User Review and Compatibility Adjustments (23rd 2024)
- 🔲 Conduct extensive user reviews and gather feedback
  - ✅ User feedback collected from initial deployment
  - ❌ Realized that the government has a separate method for transporting goods requiring permission letters to be sent - information from someone working for DDMA
  - ✅ Integrated government permission workflows into the system
- 🔲 Implement security enhancements based on feedback and findings
  - ✅ Addressed data encryption and secure communication channels
  - ❌ Discovered vulnerabilities in initial encryption methods## Contributing

### Team Members of the FORUS Project

- **Rakhul Prakash S B** - App Development
- **Shanthosh S** - PDRS and Validation System
- **Fazil S** - App Development (Front-end)
- **Kannal A S** - App Development (Back-end)
- **Arunachalam T** - IoT Developer
