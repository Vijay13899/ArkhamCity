# ArkhamCity
## Question link: https://github.com/fincity-india/interviewquestions/blob/master/arkhamcity.md

## Solution:
In the scenario described in the problem statement, where the relationship between the number of patients and the number of steps taken by the first patient is linear, you can calculate the total number of steps required by simply multiplying the number of patients by the number of steps taken by the first patient.

```
function findNumOfStepsRequired(num_patients, start_step){
    return num_patients * start_step;
}
```
```
//Sample inputs
console.log(findNumOfStepsRequired(3, 10)) // --> 30
```
