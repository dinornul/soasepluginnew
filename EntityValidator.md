Tool: EntityValidator

Validates entity files based on multiple criteria prior to executing in the Sins debugger.

**Entity validation criteria is defined in an external xml configuration file which contains all the validation and structure rules.**

Summary of validations currently supported:
  * Boolean: Validates boolean entries contain TRUE or FALSE only
  * Brush: Validates a referenced brush entry exists for the value entered
  * Conditional Validation: Allows conditional structures to follow based on a field value
  * Key word: Validates all entity file key words are spelled correctly
  * Quotes: Validates any values requiring qoutes have beginning and ending quotation marks
  * Integer: Validates integer entries contain digits
  * Decimal: Validates decimal entries contain ####.#####
  * Entity References: Validates a referenced entity file exists for the value entered
  * String Reference: Validates a referenced String entry exists for the value entered
  * Sound Reference: Validates a referenced Sound entry exists for the value entered
  * Enumeration Validation: Validates an entry confirms to an allowed set of values (i.e. buffInstantActionType)
  * Iteration Validation: Validates repeating elements are correct
  * Structure Validation: Validates entries appear in the correct order in the entity file (configurable to allow unordered structures)
  * Explosion Validation: Validates a referenced explosion entry exists for the value entered
  * Texture Validation: Validates a referenced texture exists for the value entered
  * Particle Validation: Validates a referenced effect exists for the value entered

Versions supported:
  * Diplomacy
  * Entrenchment
  * Vanilla (limited support)

Entities supported:
  * Ability
  * Buff
  * CannonShell
  * CapitalShip
  * EntryVehicle
  * Fighter
  * Frigate
  * Mission
  * PipCloud
  * PlanetBonus
  * PlanetModule(s)
  * Planet
  * Player
  * Quest
  * ResearchSubject
  * ResourceAsteroid
  * SpaceMine
  * Squad
  * StarBaseUpgrade
  * StarBase
  * Star

EntityValidator Ant Task Options:
  * debug: boolean, defaults to false
  * warn: boolean, defaults to false
  * failOnError: boolean, defaults to true
- Next three will need to be added back into the new task. Defaults are currently used.
  * ignoreCaseOnFiles: boolean, defaults to true
  * decimalPointRequired: boolean, defaults to false. Allows integer only entries for decimal fields.
  * allowDecimalOnInteger: boolean, defaults to true. Allows integer only entries to include decimal values.

```
<validateentity warn="false" debug="false" failOnError="false" >
2.   <fileset dir="GameInfo" includes="*.entity"/>
3.  </validateentity>
```