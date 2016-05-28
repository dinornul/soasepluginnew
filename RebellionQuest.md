**[Quest](RebellionQuest.md)
  * titleStringId: [StringInfo](StringInfo.md)
  * infoCardDescStringId: [StringInfo](StringInfo.md)
  * [questType](RebellionquestType.md): [Enumeration](Enumeration.md)
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
  * [reward](RebellionCost.md): [Cost](Cost.md)
  * [priceDemanded](RebellionCost.md): [Cost](Cost.md)
  * valueToKill: [Decimal](Decimal.md)
  * numReceiverConstraints: [Iteration](Iteration.md)
    * [ReceiverConstraint](RebellionQuestTarget.md): [QuestTarget](QuestTarget.md)
  * numTargetConstraints: [Iteration](Iteration.md)
    * [TargetConstraint](RebellionQuestTarget.md): [QuestTarget](QuestTarget.md)
  * weight: [Decimal](Decimal.md)**
