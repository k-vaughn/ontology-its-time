# SpecialDay

![SpecialDay Diagram](../diagrams/itsTime__SpecialDay.dot.svg)

<a href="../../diagrams/itsTime__SpecialDay.dot.svg">Open interactive SpecialDay diagram</a>

## Specializations of SpecialDay

| Class | Description |
|-------|-------------|
| [Public Holiday](itsTime__PublicHoliday.md) |  |

## Formalization for SpecialDay

| Property | Constraint |
|----------|------------|
| intersectWithApplicableDays | all xsd::boolean |
| intersectWithApplicableDays | exactly 1 owl::Thing |
| publicEvent | all code::Code |
| publicEvent | max 1 owl::Thing |
| specialDayType | all code::Code |
| specialDayType | exactly 1 owl::Thing |
| subClassOf | TimeThing |

## Used by classes

| Class | Property |
|-------|----------|
| [Period](itsTime__Period.md) | recurringSpecialDay |

## Other annotations

| Annotation | Value |
|------------|-------|
| xsd::pattern | TimePattern |

