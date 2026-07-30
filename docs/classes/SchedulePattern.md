![Draft for review only](https://isotc204.org/assets/img/draft_for_review.svg)

# Time Ontology for ITS - Schedule Pattern

This ontology defines concepts related to schedules for temporal validity in traffic and transport situations. This pattern is one module of the Time Ontology for ITS.

This pattern imports the following files:

- [https://w3id.org/itsdata/time/v1/FuzzyTimePattern](https://w3id.org/itsdata/time/v1/FuzzyTimePattern)

This pattern consists of the following classes:

- [Calendar Week Within Month](CalendarWeekWithinMonth.md)
- [Date Within Month](DateWithinMonth.md)
- [Day Week Month](DayWeekMonth.md)
- [Instance Of Day Within Month](InstanceOfDayWithinMonth.md)
- [Overall Period](OverallPeriod.md)
- [Period](Period.md)
- [Public Event Code](PublicEventCode.md)
- [Public Holiday](PublicHoliday.md)
- [Schedule](Schedule.md)
- [Schedule Thing](ScheduleThing.md)
- [Special Day](SpecialDay.md)
- [Special Day Type Code](SpecialDayTypeCode.md)
- [Time Period Of Day](TimePeriodOfDay.md)
- [Validity Status Code](ValidityStatusCode.md)
- [Week Code](WeekCode.md)
This module defines the following properties:

- [applicableArea](../properties/applicableArea.md)
- [applicableDayOfMonth](../properties/applicableDayOfMonth.md)
- [applicableDayOfWeek](../properties/applicableDayOfWeek.md)
- [applicableInstanceOfDayWithinMonth](../properties/applicableInstanceOfDayWithinMonth.md)
- [applicableMonth](../properties/applicableMonth.md)
- [applicableWeek](../properties/applicableWeek.md)
- [dailyEndTime](../properties/dailyEndTime.md)
- [dailyStartTime](../properties/dailyStartTime.md)
- [endOfPeriod](../properties/endOfPeriod.md)
- [exceptionPeriod](../properties/exceptionPeriod.md)
- [hasApplicableFuzzyTimePeriod](../properties/hasApplicableFuzzyTimePeriod.md)
- [hasPublicEventType](../properties/hasPublicEventType.md)
- [hasRecurringDayWeekMonthPeriod](../properties/hasRecurringDayWeekMonthPeriod.md)
- [hasRecurringSpecialDay](../properties/hasRecurringSpecialDay.md)
- [hasRecurringTimePeriodOfDay](../properties/hasRecurringTimePeriodOfDay.md)
- [hasSpecialDayType](../properties/hasSpecialDayType.md)
- [hasValidityStatus](../properties/hasValidityStatus.md)
- [intersectWithApplicableDays](../properties/intersectWithApplicableDays.md)
- [isOverrunning](../properties/isOverrunning.md)
- [overallEndTime](../properties/overallEndTime.md)
- [overallStartTime](../properties/overallStartTime.md)
- [reverseInstance](../properties/reverseInstance.md)
- [ScheduleDataProperty](../properties/ScheduleDataProperty.md)
- [ScheduleObjectProperty](../properties/ScheduleObjectProperty.md)
- [startOfPeriod](../properties/startOfPeriod.md)
- [validityTimeSpecification](../properties/validityTimeSpecification.md)
- [validPeriod](../properties/validPeriod.md)


The formal definition of this pattern is available in TURTLE Syntax in two files, the [core semantics](../schedule-pattern.ttl) and the SHACL [restrictions](../schedule-shacl.ttl).
