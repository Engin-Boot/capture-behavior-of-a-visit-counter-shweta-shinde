# Visit-counter technical needs

Scenario: Recover across restarts of the server
that runs the visit-counter

  Given: The server is not functional
  When: The server restarts
  Then: Retrive the saved value of visitor counter

Scenario: Reconcile counts if the sensor is offline for a while

  Given: The server is not functional
  When: The server is online
  Then: Manually add the number of visitorcards issued when offline
