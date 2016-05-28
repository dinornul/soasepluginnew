**[Planet](Planet.md)
  * meshInfoCount: [Iteration](Iteration.md)
    * [meshInfo](meshInfo.md)
      * typeNameStringID: [StringInfo](StringInfo.md)
      * [asteroidTemplate](asteroidTemplate.md): [Enumeration](Enumeration.md)
        * AlienRuins
        * Belt
        * Crescent
        * Dense
        * Empty
        * Field
        * Line
        * Moon3
        * Moon7
        * Ring
        * SpaceJunk
        * Sparse
        * Wall
      * [dustCloudTemplate](dustCloudTemplate.md): [Enumeration](Enumeration.md)
        * Dense
        * Empty
        * GrittyDense
        * GrittyDump
        * GrittySparse
        * IceSafe
        * PuffyDense
        * PuffySparse
        * Sparse
      * meshName: [Mesh](Mesh.md)
      * cloudColor: [Color](Color.md)
      * nullMeshRadius: [Decimal](Decimal.md)
      * nullMeshParticleEffect: [Particle](Particle.md)
      * hudIcon: [Brush](Brush.md)
      * smallHudIcon: [Brush](Brush.md)
      * infoCardIcon: [Brush](Brush.md)
      * mainViewIcon: [Brush](Brush.md)
      * undetectedMainViewIcon: [Brush](Brush.md)
      * picture: [Brush](Brush.md)
  * minZoomDistanceMult: [Decimal](Decimal.md)
  * glowColor: [Color](Color.md)
  * ringColor: [Color](Color.md)
  * cloudLayerTextureName: [Texture](Texture.md)
  * [planetResourceSetupInfo](planetResourceSetupInfo.md)
    * asteroidSpawnAngleVariance: [Decimal](Decimal.md)
    * totalMaxResourceAsteroids: [Integer](Integer.md)
    * [metalResourceAsteroidSetup](AsteroidSetup.md): [AsteroidSetup](AsteroidSetup.md)
    * [crystalResourceAsteroidSetup](AsteroidSetup.md): [AsteroidSetup](AsteroidSetup.md)
    * [neutralMetalResourceAsteroidSetup](AsteroidSetup.md): [AsteroidSetup](AsteroidSetup.md)
    * [neutralCrystalResourceAsteroidSetup](AsteroidSetup.md): [AsteroidSetup](AsteroidSetup.md)
  * isAsteroid: [Boolean](Boolean.md)
  * healthRegenRate: [Decimal](Decimal.md)
  * [planetUpgradeDef](planetUpgradeDef.md)
    * [path:Population]
      * stageCount: [Iteration](Iteration.md)
        * [stage](stage.md)
          * [price](Cost.md): [Cost](Cost.md)
          * upgradeTime: [Decimal](Decimal.md)
          * maxPopulation: [Decimal](Decimal.md)
          * populationGrowthRate: [Decimal](Decimal.md)
          * developmentTaxPenalty: [Decimal](Decimal.md)
    * [path:CivilianModules]
      * stageCount: [Iteration](Iteration.md)
        * [stage](stage.md)
          * [price](Cost.md): [Cost](Cost.md)
          * upgradeTime: [Decimal](Decimal.md)
          * maxModuleSlotCount:Civilian: [Decimal](Decimal.md)
          * maxModuleConstructorCount: [Integer](Integer.md)
    * [path:TacticalModules]
      * stageCount: [Iteration](Iteration.md)
        * [stage](stage.md)
          * [price](Cost.md): [Cost](Cost.md)
          * upgradeTime: [Decimal](Decimal.md)
          * maxModuleSlotCount:Tactical: [Decimal](Decimal.md)
          * maxModuleConstructorCount: [Integer](Integer.md)
    * [path:Home]
      * stageCount: [Iteration](Iteration.md)
        * [stage](stage.md)
          * [price](Cost.md): [Cost](Cost.md)
          * upgradeTime: [Decimal](Decimal.md)
          * isHomePlanet: [Boolean](Boolean.md)
          * homePlanetTaxRateBonus: [Decimal](Decimal.md)
          * homePlanetMetalIncomeBonus: [Decimal](Decimal.md)
          * homePlanetCrystalIncomeBonus: [Decimal](Decimal.md)
    * [path:ArtifactLevel]
      * stageCount: [Iteration](Iteration.md)
        * [stage](stage.md)
          * [price](Cost.md): [Cost](Cost.md)
          * upgradeTime: [Decimal](Decimal.md)
    * [path:Infrastructure]
      * stageCount: [Iteration](Iteration.md)
        * [stage](stage.md)
          * [price](Cost.md): [Cost](Cost.md)
          * upgradeTime: [Decimal](Decimal.md)
          * maxHealth: [Decimal](Decimal.md)
  * ringsChance: [Decimal](Decimal.md)
  * isColonizable: [Boolean](Boolean.md)
  * [planetTypeForResearch](planetTypeForResearch.md): [Enumeration](Enumeration.md)
    * Asteroid
    * Desert
    * Ice
    * Invalid
    * Terran
    * Uncolonizable
    * Volcanic
  * skyboxScalarsCount: [Iteration](Iteration.md)
    * [skyboxScalars](skyboxScalars.md)
      * diffuseScalar: [Decimal](Decimal.md)
      * ambientScalar: [Decimal](Decimal.md)
  * requiredPlanetBonusesCount: [Iteration](Iteration.md)
    * bonus: [Entity](Entity.md)
  * possibleRandomPlanetBonusesCount: [Iteration](Iteration.md)
    * bonus: [Entity](Entity.md)
  * ambienceSoundID: [Sound](Sound.md)
  * renderAsVolcanic: [Boolean](Boolean.md)
  * ShieldMeshName: [Mesh](Mesh.md)
  * renderShield: [Boolean](Boolean.md)
  * moveAreaRadius: [Decimal](Decimal.md)
  * hyperspaceExitRadius: [Decimal](Decimal.md)
  * isWormhole: [Boolean](Boolean.md)
  * maxStarBaseCountPerPlayer: [Integer](Integer.md)
  * maxSpaceMineCountPerPlayer: [Integer](Integer.md)
  * minShadow: [Decimal](Decimal.md)
  * maxShadow: [Decimal](Decimal.md)
  * ability:0: [Entity](Entity.md)
  * ability:1: [Entity](Entity.md)
  * ability:2: [Entity](Entity.md)
  * ability:3: [Entity](Entity.md)
  * ability:4: [Entity](Entity.md)**
