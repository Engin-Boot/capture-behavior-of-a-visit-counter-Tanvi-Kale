# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

   Given:The system may be PC or mobile and sensors are ON

   When:The sensor senses the patient entry assuming separate sensor for patients

   Then:The count of patients be recorded in the system

Scenario: Compute parking slots to reserve for visiting specialists

   Given:The details about the parking area and vehicles entries

   When:The visiting specialists are planning to visit

   Then:Some parking slots be blocked for regular visitors
