**[Quest](VanillaQuest.md)
  * titleStringId: [StringInfo](StringInfo.md)
  * infoCardDescStringId: [StringInfo](StringInfo.md)
  * [questType](VanillaquestType.md): [Enumeration](Enumeration.md)
    * BombAnyPlanet
    * GiveResources
    * KillCapitalShips
    * KillCivilianStructures
    * KillShips
    * KillTacticalStructures
    * SendEnvoy
  * duration: [Decimal](Decimal.md)
  * relationshipDecayRate: [Decimal](Decimal.md)
  * happinessChangeForSuccess: [Decimal](Decimal.md)
  * happinessChangeForFailure: [Decimal](Decimal.md)
  * [reward](VanillaCost.md): [Cost](Cost.md)
  * [priceDemanded](VanillaCost.md): [Cost](Cost.md)
  * valueToKill: [Decimal](Decimal.md)
  * numReceiverConstraints: [Iteration](Iteration.md)
    * [ReceiverConstraint](VanillaQuestTarget.md): [QuestTarget](QuestTarget.md)
  * numTargetConstraints: [Iteration](Iteration.md)
    * [TargetConstraint](VanillaQuestTarget.md): [QuestTarget](QuestTarget.md)
  * weight: [Decimal](Decimal.md)**
