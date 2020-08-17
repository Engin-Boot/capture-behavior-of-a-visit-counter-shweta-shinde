# Visit-counter for a Director

Scenario: Show patient visits during working days and holidays

  Given:The server is functional
  When: I press "Show patients visits on working day" button
  Then: It should display all the details about patients visits from Monday to Saturday
  When: I press "Show patients visits on holiday day" button
  Then: It should display all the details about patients visits on Sundays and holidays

Scenario: Compute parking slots to reserve for visiting specialists

  Given: There are empty parking spaces and Server is functional
  When: When I press "Compute reserved parking spot"
  Then: It should give all the empty parking spot available
