Version History:


Eclipse Plugin:

11/1/2012 v2.1.1 (Compatible with Eclipse 3.6.x or higher)
  1. Enhancement: Warns of entity files that "may" not be referenced
  1. Enhancement: Warns of mesh files that "may" not be referenced (Could be referenced from a Particle Effect).
  1. Enhancement: Warns of sound files that "may" not be referenced
  1. Enhancement: Warns of particle files that "may" not be referenced (Could be referenced from a Mesh). # Reports needsToFaceTarget should not be set to TRUE when applying buff to self or multiple targets in Ability entities
  1. instantActionTriggerType should not be set to OnDelay in Ability entities
  1. Added new hasWeaponEffects Reporter
    1. Reports 'canWeaponEffectHitHull' and 'canWeaponEffectHitShields' only make sense when then ImpactOffsetType is 'RandomMesh'. If the impact isn't on the mesh then these values are ignored.
  1. Preferences now include Rebellion Installation and Rebellion Reference options in the Preferences Dialogue.

9/12/2012 v2.1.0 (Compatible with Eclipse 3.6.x or higher)
  1. Enhancement: Added Compare Reference right click option in project explorer. Compares the mod file against the matching named reference file. (Rebellion Compatible).
  1. Enhancement: instantActionTriggerType now does additional validations based on the scope of it's usage: Ability, instantAction, periodicAction
  1. Enhancement: Added support for limit constraints on iterative fields such as NumWeapons constrained to a limit of 5.
  1. Enhancement: Added HasBuff aiUseTargetCondition.
  1. Enhancement: Supports Rebellion 1.04 release.
  1. Enhancement: Preferences now include Rebellion Installation and Rebellion Reference options in the Preferences Dialogue.

6/28/2012 v2.0.8
  1. Defect: Changed RequiredFactionNameID from Any to StringInfo
  1. Defect: Added Invalid to WeaponClassType
  1. Enhancement: weaponClassForWeaponPassive now references global WeaponClassType
  1. Defect: PirateStrengthAgainstYouAdjustment changed to NotDiplomacyOrRebellion
  1. Enhancement: Added new version policy NotDiplomacyOrRebellion
  1. Defect: Added xpModifier to star base upgrade

6/13/2012 v2.0.6
  1. Defect: optional effectInfo removed from ApplyBuffToLocalOrbitBodyWithTravel and RestoreAntiMatter
  1. Defect: added new weapon types to linkedWeaponClass

6/13/2012 v2.0.5
  1. Enhancement: Rebellion support added

3/19/2012 v1.0.8
  1. Enhancement: Various improvements to tool

10/6/2011 v1.0

  1. Enhancement: Now does reference completion for non-entity files
  1. Enhancement: Now does stackingLimit validation for allowFirstSpawnerToStack
  1. Enhancement: Now "correctly" identifies missing required fields
  1. Enhancement: buffInstantActionType rules modified to reflect which require effectInfo and which don't
  1. Enhancement: Gameplay.constants rules updated to better reflect required fields between Vanilla, Entrenchment and Diplomacy
  1. Enhancement: Explosion validation rule updated to reflect required fields for type of explosion
  1. Enhancement: Finish condition rules updated to reflect required keywords depending on finish condition chosen.
  1. Wiki update to reflect changes in validation rules

7/21/2011 v.0.9

  1. Enhancement: Updated to support modifications with Diplomacy 1.3 and 1.31 (see http://forums.sinsofasolarempire.com/410523).

6/27/2011 v.0.8.4
  1. Enhancement: Adds support for research modifier PirateRaidsOneLevelLower
  1. Enhancement: Now propery handles random maps in Galaxy files

3/18/2011 v.0.8.3
  1. Defect: Fixes issue opening non-eclipse managed files in the Sins Editor via the File->File Open... menu actions.
  1. Defect: Fixes issue ordering issue of reference files for some validations introduced with version 0.8. For example vanilla brush files are overiding Entrenchment reference brush files. The ordering was introduced to better handle total conversion projects.

3/11/2001 v.0.8.2
  1. Enhancement: Adds support for custom Galaxy files (**.galaxy)
  1. Enhancement: Adds support for Explosiondata files
  1. Enhancement: Adds two pass validation for Galaxy and GalaxyScenarioDef files for the following validations.
    1. Galaxy template references
    1. Galaxy orbit body type references
    1. Galaxy design references**

3/10/2011 v.0.8.1
  1. Defect: Fixes issue with file deletions causing fullBuild to error in some scenarios.

3/10/2011 v.0.8.0
  1. Enhancement: Updates Wiki to reflect new changes
  1. Enhancement: Adds support for resource event listening which is used to determine when a fullBuild or incrementalBuild is required. This should alleviate a lot of the Project/Clean... manual work when adding/removing and modifying files.
  1. Enhancement: Adds aiUseTime->OnlyWhenDebrisWithinRange (Beta 1.2)
  1. Enhancement: Adds aiUseTargetCondition->AntimatterExceedsAmount (Beta 1.2)
  1. Defect: Adds missing FightersPerSquadron for buffEntityModifierType
  1. Defect: Adds ChaosBolt to weaponClassForWeaponPassive
  1. Enhancement: Adds defaults for upgrade times
  1. Enhancement: Adds new GameEventSound:QuestEnded (Beta 1.2)
  1. Enhancement: Adds new PlayerAITable->BuildMines (Beta 1.2)
  1. Enhancement: Adds new PlanetData->minPropagatedCultureRate (Beta 1.2)
  1. Enhancement: Adds new PlanetData->culturePropagationPerc (Beta 1.2)
  1. Enhancement: Adds new PlanetData->cultureDecayRate (Beta 1.2)
  1. Enhancement: Adds new pirateRaidDef->raidCost:[0-4](Beta 1.2)
  1. Enhancement: Adds new playerDiplomacyAIDef->tradeBonusRatePerTrip  (Beta 1.2)
  1. Enhancement: Adds new playerDiplomacyAIDef->tradeBonusCap (Beta 1.2)
  1. Enhancement: Adds new playerDiplomacyAIDef->tradeBonusDecayRate (Beta 1.2)


12/26/2010 v.0.7.7
  1. Defect: NumCriticalHitEffectSoundIDs incorrectly referenced Particle for SoundID
  1. Enhancement: Add support for vanilla only settings
  1. Enhancement: Add support for project property overrides (right click on project in explorer)

11/16/2010 v.0.7.6
  1. Enhancement: Add support for multiple mods
  1. Enhancement: Add version support for conditions
  1. Enhancement: Add version tags to additional constants
  1. Enhancement: Add research subject upgrade time validation support

11/01/2010 v.0.7.5
  1. Enhancement: Add support for constraints on decimals
  1. Enhancement: Add travelSpeed validation when weaponType=Beam
  1. Defect: Add missing FightersPerSquadron buffEntityModifierType
  1. Defect: Add missing minCount/maxCount in rebellionInfo/requiredShip

10/12/2010 v.0.7.4
  1. [Defect](http://code.google.com/p/soaseplugin/issues/detail?id=5): WithinSolarSystem should be WithinCurrentSolarSystem
  1. [Enhancement](http://code.google.com/p/soaseplugin/issues/detail?id=6): useCostType is Passive but autocast is TRUE
  1. [Enhancement](http://code.google.com/p/soaseplugin/issues/detail?id=7): Validate weaponEffect weaponType equals Weapon's weaponType
  1. [Defect](http://code.google.com/p/soaseplugin/issues/detail?id=10): ResearchSubject Tier validation not working properly for Artifacts
  1. [Defect](http://code.google.com/p/soaseplugin/issues/detail?id=11): ApplyForceFromSpawner not validating correctly on force line
  1. [Enhancement](http://code.google.com/p/soaseplugin/issues/detail?id=12): Add support for tier level research cost validation (defaulted to off via preferences)
  1. [Defect](http://code.google.com/p/soaseplugin/issues/detail?id=13): HEX Color validation currently showing errors on RGB (6 character hex codes), works for RGBA


8/24/2010 v.0.7.3
  1. [Enhancement](http://code.google.com/p/soaseplugin/issues/detail?id=4): Adds tier validation support for ResearchSubject entity files
  1. [Defect](http://code.google.com/p/soaseplugin/issues/detail?id=3): Fixes issue with requiredShip rule not correctly validating minCount and maxCount.

8/24/2010 v.0.7.2
  1. [Defect](http://code.google.com/p/soaseplugin/issues/detail?id=1): Fixes issue with content assistance not correctly completing unfinished portion of keyword.
  1. [Defect](http://code.google.com/p/soaseplugin/issues/detail?id=1): Fixes issue with content assistance not correctly completing unfinished values
  1. [Defect](http://code.google.com/p/soaseplugin/issues/detail?id=1): Fixes issue with content assistance not recognizing `_` (underscores) in ID values
  1. [Defect](http://code.google.com/p/soaseplugin/issues/detail?id=2): Fixes issue with Project/Clean... not completing.

8/23/2010 v.0.7.1
  1. Fixes issue with v.0.7 build not including icons

8/23/2010 v.0.7

  1. Enity Editor Enhancements
    1. Adds Syntax Coloring Support
    1. Adds Hover Help Support
    1. Adds Content Assistant
      * Enumerations/Constants
      * Sound References
      * Entity References
      * Explosions
      * Particle Effects
    1. Adds popup menu with F3 shortcut to open referenced entity files
    1. Adds new icons
  1. Adds new preference options
    1. Version support
    1. Editor Tab Width
    1. Show Hover Help Flag
    1. Syntax Coloring
  1. Entity Builder
    1. Adds additional progress information
  1. Entity Parser/Validator
    1. Addds support for Vanilla/Entrenchment/Diplomacy validations
    1. Fixes some issues with validation
    1. Enhanced validation for many conditional type fields
      1. finishConditionType
      1. buffInstantActionType
      1. etc

7/23/2010 v.0.6

  1. Added new grammar validation rules
    1. Any - Just validates there is a value
    1. SoundFile? - Validates the referenced file and extension exists
    1. Color - Validates the color is a RGBA value
    1. Position - Validates the position matches [#, #, ... ](.md)
  1. Added brushes.xml - validates all **.brushes files
  1. common.xml changes
    1. Added condition canAlwaysFire for fireConstraintType
    1. Added missing force element\_rule
  1. Added constants.xml - validates Gameplay.constants
  1. Added help support to grammar definitions
  1. Added missing FALSE condition for hasWeaponLevels in frigate.xml
  1. Added galaxy\_scenario\_def.xml - validates**.galaxyScenarioDef files
  1. Added missing validation rules to pip\_cloud.xml
  1. Added missing validation rules to quest.xml
  1. Added sound\_data.xml - validates **.sounddata files
  1. Added string\_info.xml - validates**.str files
  1. Build/Nature
    1. Added support for files other than **.entity
    1. Added new preference for sins installation directory
    1. Allows for binary file references to be located such as**.ogg
  1. Entity Definition View
> Added support for files other than **.entity
  1. Entity Parser
    1. Fixes issue when tabs are used instead of spaces between keyword and value
    1. Adds validation support for Any, SoundFile?, Color and Position
    1. Fixes issue where an error was not reported at the end of the file
    1. Adds references to field definition handler - used for wiki generation
  1. WikiDefinitionBuilder?
    1. Adds new functionality to generate dynamic wiki pages based on definition xmls**

7/14/2010 v.0.5
  1. Added custom perspective for Sins of a Solar Empire.
  1. Added custom icon for Sins of a Solar Empire files.
  1. Added text editor extensions to automatically map str, entity, constants and galaxyScenarioDef to open in the Eclipse Text Editor.
  1. Added support for placing mod files in sub-directories in the Eclipse project.
    * For example [path](project.md)/mod/GameInfo, [path](project.md)/mod/String, etc.

6/21/2010 v.0.4
  1. Added support for projects that exist outside of the workspace. Allows a project to be created directly in the mod directories.
  1. Added Entity Definition View
  1. Added new Sose preferences for configuring reference case validation, decimal and integer validations.

http://dl.dropbox.com/u/5790092/SinsTools/soseplugin_v.0.3.zip (6/10)
Missing allegianceDecreasePerRoundTrip

http://dl.dropbox.com/u/5790092/SinsTools/soseplugin_v.0.2.zip (6/10)
Minor enhancements only

http://dl.dropbox.com/u/5790092/soseplugin_v.0.1.zip
Eclipse plugin tool adding visual Entity level editor support


Ant Tools:

http://dl.dropbox.com/u/5790092/SinsTools/sins_build_tools_v.0.5.jar.7z (6/10)
Missing allegianceDecreasePerRoundTrip

http://dl.dropbox.com/u/5790092/SinsTools/sins_build_tools_v.0.4.jar.7z
Integrated with new EntityParser
Definition files now stored in jar file

http://dl.dropbox.com/u/5790092/sins_build_tools_v0.3.7z (4/29)
Minor improvements to error checking and line number reporting.
Implemented entity\_definitions.xsd for definition language.
Modified all **.xml to use entity\_definitions.xsd**

http://dl.dropbox.com/u/5790092/sins_build_tools_v0.2.7z (4/22)
Adds support for ignoring case when validating Sounds, Explosions, and Brush entries.
Adds missing diplomacy buffs for credits, relationshipIncrease, planetHealthRestoreRate and allegianceRestoreRate.
Adds diplomacy missions.
Adds pirate armorType (common.xml).
Adds missing diplomacy buffInstantActionTypes, buffOverTimeActionTypes, buffEntityModifierTypes, modifierTypes (common.xml).
Adds missing diplomacy constraint in (common.xml).
Adds missing diplomacy entries in (player.xml).
Adds PactBonus to ResearchField validation in (research\_subject.xml).
Adds missing pact bonuses to allianceType (research\_subject.xml).
Adds AbilityDLevel to propertyType validation (star\_base\_upgrade.xml).

alpha release dated 04/22/2010 (v0.1)
http://dl.dropbox.com/u/5790092/sins_build_tools_v0.1.7z

Ant Tasks Supported:
sose.tools.BrushGenerator.java
sose.tools.EntityValidator.java
sose.tools.ManifestGenerator.java