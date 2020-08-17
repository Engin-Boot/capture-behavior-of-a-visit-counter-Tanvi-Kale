# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given:The previously recorded data is stored in the system
  
  When:The server restarts again and visitors are now allowed
  
  Then:The visit-count starts again

Scenario: Reconcile counts if the sensor is offline for a while

  Given:The count can be maintained manually
  
  When:The sensor is ON again
  
  Then:There should be a option to correct the count manually
