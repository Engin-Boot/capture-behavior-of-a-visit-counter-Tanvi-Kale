# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

   Given:The system i.e., PC or mobile and sensors are ON

   When:The sensor senses the patient entry assumimg separate sensor for patients

   Then:The count of patients must be recorded in the system

Scenario: Compute parking slots to reserve for visiting specialists

   Given:The details about the parking area and vehicles entries

   When:The visiting specialists are planning to visits

   Then:Some parking slots must be reserved for them
