# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given: The data of types of visitors in a week

  When: The week ends

  Then: Record the details about the visitors

Scenario: Alert when seating capacity is full

  Given: The visitor count

  When: The count exceeds the specified number

  Then: Send an alert message to the Manager
