# Changelog

## 2025-10-01

### Added
- *State*

### Changed
- Define *Situation* as supercategory of *State*, *Process*, and *SituationAggregate*

### Removed
- *CohesiveSituation*
- *CohesiveProcess*
- *ProcessAggregate*
- *hasProcessPart/processPartOf*

### Migration
- Use *SituationAggregate* instead of *ProcessAggregate*
- Use *Process* instead of *CohesiveProcess*
- Use *State* instead of *CohesiveSituation*
- Use *hasSituationPart/situationPartOf* instead of *hasProcessPart/processPartOf*

## 2025-04-07

### Added
- **gfo-core** as part of **gfo-light**

### Changed
- Rename *Situation* to *CohesiveSituation*
- Rename *Process* to *CohesiveProcess*
- Rename *SituationalEntity* to *Situation*
- Rename *ProcessualEntity* to *Process*

### Migration
- Use *CohesiveSituation* instead of *Situation*
- Use *CohesiveProcess* instead of *Process*
- Use *Situation* instead of *SituationalEntity*
- Use *Process* instead of *ProcessualEntity*

## 2025-03-17

### Added
- *SituationalEntity*
- *SituationAggregate*
- *ProcessualEntity*
- *ProcessAggregate*

### Removed
- *RelationalRole*
- *SituationalRole*
- *ProcessualRole*
- *ContinuantPartRole*

### Migration
- Use *Role* for all role types

## 2025-01-06
Initial release