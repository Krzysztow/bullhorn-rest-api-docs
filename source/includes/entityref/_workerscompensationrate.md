# WorkersCompensationRate

Represents workers compensation rate data.

| **WorkersCompensationRate field** | **Type** | **Description** | **Not null** | **Read-only** |
| --- | --- | --- | --- | --- |
| id | Integer | Unique identifier for this entity. | X | X |
| compensation | To-one assocation | WorkersCompensation entity related to this rate. | X | |
| endDate | Timestamp | End date set for this WorkersCompensationRate. | X | |
| rate | Double | Value of the rate. | X | |
| startDate | Timestamp | Start date set for this WorkersCompensationRate. | X | |
