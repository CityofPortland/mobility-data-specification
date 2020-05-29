# Terminology and Measure Definitions
This document provides definitions of terms enumerated in TRN 15.10 section 4, part C, metrics for compliance and incentives, and guidance for determining measured values for those terms and metrics. These terms may reference terms that are part of the Mobility Data Specification (MDS) as a whole, and should be used in conjunction with this repository's definitions. Where the definitions in this document and MDS are not aligned, this document should take precedence.

Measured values for this document may be retrieved from [Ride Report](https://ridereport.com) and this document describes which specific values will be used in measures. Operators should contact Ride Report for technical support using their web applications, for clarification of how Ride Report determines a value referenced in this document, and for resolution of discrepancies of measured values between the operator and Ride Report.

PBOT reserves the right to change how it defines and measures data terms in order to adapt to evolving industry best practices. Any changes that PBOT makes to definitions and measures of data terms will be communicated to permittees with at least 30 days’ notice.

## Shared Scooters in the Right of Way
A shared scooter is considered to be in the right of way if it is reported as being in either the _available_ or _unavailable_ state as defined in MDS.

## Allotment
An operator's maximum number of alloted shared scooters in the right of way for a given day is provided by their permit. To retrieve the number of shared scooters in the right of way for a given day use the "Max Parked" metric from Ride Report for that day.

## Deployment
A deployment is measured by the "Morning deployment" value provided by Ride Report. As of this writing, that measure is determined by counting the nubmer of vehicles Ride Report has determined to be in the available state at 8:00:00 AM on a given day.

This measure of deployments is used to determine compliance with deployments required in the East Portland pattern area. Operators are required to ensure that at least 15.00 percent of their measured deployments occur in the East Portland pattern area. To calculate the percentage of deployments occuring in the East Portland pattern area, use the Area of Interest Metrics section for a given day's report from Ride Report. From the Area of Interest Metrics section, divide the "Eastern Neighborhoods Parking" area's value for "Morning Deployment" by the "Portland City Limits" area's value, then multiply by 100. That value, rounded to two decimal precision, is the measured value of deployments in the East Portland pattern area.

As detailed in our January 15, 2020 memo, companies must satisfactorily meet East Portland deployment requirements to be eligible for performance incentives. These requirements are measured in multiple ways for incentive purposes. The ways compliance is measured are daily, average daily over a time period, and the number of days in compliance over a given time period.

### Daily compliance
Daily compliance is calculated by using a given day's daily report. Follow the calculation method described above to determine the value of deployment percentage for the East Portland pattern area.

### Average daily compliance
Average compliance over a given period is determined by summing the individual daily compliance values at two decimal precision as described above, and dividing by the number of days measured.

### Percentage of days in compliance
The percentage of days in compliance is the percentage of days within a given period where the measured value of daily compliance as described above is at least 15.00 percent, rounded to two decimal precision. To be eligible for incentives, companies should have a minimum compliance rate of at least 50.00 percent.

### Example
For a period of three days, the following deployment values and resulting percentages were measured:

| Day | Portland city limits deployments | East portland deployments | Percentage |
| - |:-:| :-:| -: |
| 1 | 300 | 50 | 16.67 |
| 2 | 350 | 50 | 14.29 |
| 3 | 250 | 40 | 16.00 |

In this example, the operator is in compliance on days 1 and 3, their average daily compliance is 15.65 = (16.67 + 14.29 + 16.00) / 3, and their number of days in compliance is 66.67 = (2 / 3) * 100.

## Available
A shared scooter is considered available in a given period by Ride Report. Ride Report provides measures for max availability in a given day and an average over other periods of time. Availability for these measures is only taken as the max availability for a given day.

## Trip
A trip is measured as the start of a trip that occured in "Portland City Limits" as determined by Ride Report. To find this measure,  select "Portland City Limits" from the "Areas" section within the "Pages" panel and use the "Start Trips" value from the resulting report.

## Utilization
It is important to balance consumer demand and vehicle availability with agency needs to maintain safety in the public right of way. Utilization is a key performance indicator for measuring both vehicle supply and consumer demand. Utilization is defined as both a daily measure and an average measure.

### Daily utilization
Daily utilization is measured by dividing the number of measured trips as described above by the measure of shared scooters that were available for that same day as described above, rounded to two decimal precision. To find this measure select "Portland City Limits" from the "Areas" section within the "Pages" panel and use the "Trips per Vehicle" value from the resulting report.

### Average daily utilization
Average utilization is over a given time period is measured by summing the daily utilization as described above for each day in the time period and dividing by the number of days in the time period, rounded to two decimal precision. To be eligible for performance incentives during a time period, companies should have an average utilization measurement of 3.00 or greater for the time period.

### Example
For a period of three days, the following availble scooters and trips were measured:

| Day | Trips per Vehicle |
| - | -: |
| 1 | 3.00 |
| 2 | 2.96 |
| 3 | 3.14 |

In this example, the operator has the daily utilization measures shown in the table, and an average daily utilization of 3.03 = (3.00 + 2.96 + 3.14) / 3.