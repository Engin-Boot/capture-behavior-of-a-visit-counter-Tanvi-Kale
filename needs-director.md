# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

   Given:The system may be PC or mobile and sensors are ON

   When:The sensor senses the patient entry assuming separate sensor for patients

   Then:Record the count of patients in system

Scenario: Compute parking slots to reserve for visiting specialists

   Given:The details about the parking area and vehicles entries

   When:The visiting specialists are planning to visit

   Then:Block some parking slots for regular visitors
