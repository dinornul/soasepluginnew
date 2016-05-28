**[Quest](EntrenchmentQuest.md)
  * titleStringId: [StringInfo](StringInfo.md)
  * infoCardDescStringId: [StringInfo](StringInfo.md)
  * [questType](EntrenchmentquestType.md): [Enumeration](Enumeration.md)
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
  * [reward](EntrenchmentCost.md): [Cost](Cost.md)
  * [priceDemanded](EntrenchmentCost.md): [Cost](Cost.md)
  * valueToKill: [Decimal](Decimal.md)
  * numReceiverConstraints: [Iteration](Iteration.md)
    * [ReceiverConstraint](EntrenchmentQuestTarget.md): [QuestTarget](QuestTarget.md)
  * numTargetConstraints: [Iteration](Iteration.md)
    * [TargetConstraint](EntrenchmentQuestTarget.md): [QuestTarget](QuestTarget.md)
  * weight: [Decimal](Decimal.md)**
