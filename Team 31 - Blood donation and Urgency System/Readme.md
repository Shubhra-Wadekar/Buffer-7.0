🩸 Blood Donation Management System

📌 Problem Statement
Blood donation is a critical process that saves lives, but patients often face delays in finding suitable donors due to mismatched blood groups, lack of availability, or geographical distance. Traditional systems struggle with:

- Manual donor–patient matching that is slow and error‑prone  
- Unclear compatibility rules leading to unsafe or incorrect matches  
- No urgency prioritization, meaning patients in critical need may not be served first  
- Poor record‑keeping, making it difficult to track donation history and donor eligibility  

This project aims to design and implement a *menu‑driven blood donation management system* that addresses these challenges by:
- Registering donors with details such as blood group, location, and donation history  
- Adding patients with urgency levels and required blood groups  
- Matching patients to compatible donors using a scoring algorithm that considers *blood group compatibility, priority, and distance*  
- Maintaining a clear donation history for accountability and future reference  

 Objectives
- Build a *menu‑driven blood donation management system* that is beginner‑friendly and easy to use  
- Ensure *accurate donor–patient matching* using blood group compatibility rules and location‑based scoring  
- Prioritize patients based on *urgency of need*, ensuring critical cases are handled first  
- Maintain a *transparent donation history* for accountability and tracking donor eligibility  
- Provide a *collaborative workflow* that allows multiple team members to contribute seamlessly via GitHub  

Scope
- *Donor Module*: Registration of donors with details such as name, blood group, location, last donation date, and contact information  
- *Patient Module*: Addition of patients with required blood group, urgency level, and location  
- *Matching Module*: Automated donor–patient matching based on compatibility, distance, and priority scoring  
- *History Module*: Recording and displaying past donations with donor, patient, blood group, and date 


 System Architecture
The system follows a *modular design*:

1. Datastore
   - Maintains donor records, patient queue, and donation history  

2. BloodCompatibility Module  
   - Defines compatibility rules and assigns priority levels to blood groups  

3. *PatientServices Module*  
   - Manages patient queue (priority based on urgency)  

4. MatchingServices Module  
   - Matches patients to donors on the basis of blood scarcity and distance
     
5. Archive Module  
   - Stores donation history with donor, patient, blood group, and date  


 Team Members
- Vaishnavi Kalane
- Shubhra Wadekar
- P Nandhini



 Conclusion
This project demonstrates how technology can streamline blood donation workflows by ensuring *compatibility, urgency prioritization, and transparent record‑keeping*. It serves as an academic model for understanding how real blood banks could manage donor–patient matching more effectively.\
