# Game Players Profile

## Feature

  This module adds functionality to save player profiles, that includes their names, usernames and levels.
  
## Acceptance Criteria

### Scenario: New user entry
  
    Given: a new user creates a profile.
    
    When: enters a name & unique username.
    
    Then: game profile will be created with level 0.
    
### Scenario: Existing user level upgrade

    Given: a user already exists in the database.
    
    When: user level upgrades.
    
    Then: increment user level.
