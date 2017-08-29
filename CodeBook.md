# Code Book

This code book summarizes the resulting data fields in `tidy.txt`.

## Variables

* `Subject` - The ID of the test subject
* `Activity` - The type of activity performed when the corresponding measurements were taken
* `Domain` - It indicates the domain of the mearurements whether it is Time or Frequency
* `MeasureType` - These are the various measurement parameters like 'BodyAcceleration', 'BodyAngularSpeed' etc.
* `Axis` - The Axis of the measurement, It will be either X,Y,Z. Some mearurements doesn't have the axis which will be kept as sempty.
* `Mean` - Mean of the mearurements for the subject for a corresponding activity.
* `StandardDeviation` - Standard deviation of the mearurements for the subject for a corresponding activity



## Activity Labels

* `WALKING` (value `1`): subject was walking during the test
* `WALKING_UPSTAIRS` (value `2`): subject was walking up a staircase during the test
* `WALKING_DOWNSTAIRS` (value `3`): subject was walking down a staircase during the test
* `SITTING` (value `4`): subject was sitting during the test
* `STANDING` (value `5`): subject was standing during the test
* `LAYING` (value `6`): subject was laying down during the test
