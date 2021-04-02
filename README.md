# Pet Management

The main purpose of this project is to practice my Rails knowledge. It's based on Petlove's backend challenge (see https://github.com/petlove/vagas/tree/master/backend-ruby)

## Scenario

I need to create an app with the following scenario:

  * Entities:
    * People: _name_, _document_ and _birthdate_;
    * Animal: _name_, _monthly cost_ and _kind_;

  * Associations:
    * People has animals;
    * Animals has kinds;
  
  * Rules:
    * People can have multiple animals;
    * People must be older than 18 to have swallows;
    * People who have name starting with 'A' can't have cats;
    * People who already spend more than 1000 with animals can't have more.
