**[Quest](Quest.md)
  * titleStringId: [StringInfo](StringInfo.md)
  * infoCardDescStringId: [StringInfo](StringInfo.md)
  * [questType](questType.md): [Enumeration](Enumeration.md)
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
  * [reward](Cost.md): [Cost](Cost.md)
  * [priceDemanded](Cost.md): [Cost](Cost.md)
  * valueToKill: [Decimal](Decimal.md)
  * numReceiverConstraints: [Iteration](Iteration.md)
    * [ReceiverConstraint](QuestTarget.md): [QuestTarget](QuestTarget.md)
  * numTargetConstraints: [Iteration](Iteration.md)
    * [TargetConstraint](QuestTarget.md): [QuestTarget](QuestTarget.md)
  * weight: [Decimal](Decimal.md)**
