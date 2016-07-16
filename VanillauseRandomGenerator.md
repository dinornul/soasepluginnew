
[useRandomGenerator](VanillauseRandomGenerator.md): [Condition](Condition.md)
  * FALSE
    * galaxyWidth: [Decimal](Decimal.md)
    * galaxyHeight: [Decimal](Decimal.md)
    * nextStarNameUniqueId: [Integer](Integer.md)
    * nextPlanetNameUniqueId: [Integer](Integer.md)
    * starCount: [Iteration](Iteration.md)
      * [star](VanillaGalaxyStarType.md): [GalaxyStarType](GalaxyStarType.md)
    * interStarConnectionCount: [Iteration](Iteration.md)
      * [interStarConnection](VanillainterStarConnection.md)
        * starIndexA: [Integer](Integer.md)
        * planetIndexA: [Integer](Integer.md)
        * starIndexB: [Integer](Integer.md)
        * planetIndexB: [Integer](Integer.md)
        * spawnProbability: [Decimal](Decimal.md)
        * [type](Vanillatype.md): [Enumeration](Enumeration.md)
          * Wormhole
          * PhaseLane
    * playerCount: [Iteration](Iteration.md)
      * [player](Vanillaplayer.md)
        * designName: [Any](Any.md)
        * inGameName: [Any](Any.md)
        * overrideRaceName: [Any](Any.md)
        * teamIndex: [Integer](Integer.md)
        * startingCredits: [Integer](Integer.md)
        * startingMetal: [Integer](Integer.md)
        * startingCrystal: [Integer](Integer.md)
        * isNormalPlayer: [Boolean](Boolean.md)
        * isRaidingPlayer: [Boolean](Boolean.md)
        * isInsurgentPlayer: [Boolean](Boolean.md)
        * themeGroup: [Any](Any.md)
        * themeIndex: [Integer](Integer.md)
        * pictureGroup: [Any](Any.md)
        * pictureIndex: [Integer](Integer.md)
  * TRUE
    * [randomizerParams](VanillarandomizerParams.md)
      * [starPosOffsetRange](VanillastarPosOffsetRange.md)
        * minPercentage: [Decimal](Decimal.md)
        * maxPercentage: [Decimal](Decimal.md)
      * [playerParams](VanillaplayerParams.md)
        * startingCredits: [Integer](Integer.md)
        * startingMetal: [Integer](Integer.md)
        * startingCrystal: [Integer](Integer.md)
        * homePlanetType: [Any](Any.md)
        * [homePlanetStarRadiusRange](VanillahomePlanetStarRadiusRange.md)
          * minPercentage: [Integer](Integer.md)
          * maxPercentage: [Integer](Integer.md)
        * areExtraPlanetsColonized: [Boolean](Boolean.md)
        * extraPlanetsMaxRadius: [Integer](Integer.md)
        * [extraPlanetsRadiusRange](VanillaextraPlanetsRadiusRange.md)
          * minPercentage: [Integer](Integer.md)
          * maxPercentage: [Integer](Integer.md)
        * extraPlanetGroupCount: [Iteration](Iteration.md)
          * [extraPlanetGroup](VanillaPlanetGroupType.md): [PlanetGroupType](PlanetGroupType.md)
      * starCount: [Iteration](Iteration.md)
        * [star](VanillaRandomStarType.md): [RandomStarType](RandomStarType.md)