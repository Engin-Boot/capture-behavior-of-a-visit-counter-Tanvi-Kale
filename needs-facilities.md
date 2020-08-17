# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given:The data of types of visitors in a week
  When:The week ends
  Then:The details about the visitors must be recorded

Scenario: Alert when seating capacity is full

  Given:The visitor count
  When:The count exceeds the specified number
  Then:An alert message must be send to the manager
