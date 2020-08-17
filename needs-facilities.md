# Visit-counter for a Facilities Manager

Scenario: Report visitor trends during a week of operation

  Given:The server is functional
  When: I press "View Visitor Trends" button
  Then: give the summary of all the visitors of current week

Scenario: Alert when seating capacity is full

  Given: The server is functional
  When: The all the seats are occupied
  Then: give an Alert message "Seating capacity full"
