// | Week          | Day 1          | Day 2          | Day 3          |
// | ------------- | -------------- | -------------- | -------------- |
// | 1             | Squat          | Bench Press    | Deadlift       |
// | 2             | Overhead Press | Squat          | Bench Press    |
// | 3             | Deadlift       | Overhead Press | Squat          |
// | 4 - Deload    | Bench Press	 | Squat 	      | Overhead Press |
# Week 1
## Day 1
main / warmup: 1x3 50% / used: none / 1x5 58%, 1x5 67%, 1x5+ 76%, 5x5 58% / progress: custom(increment: 10lb) {~
  if (dayInWeek > 1 && week % 4 == 0) {
    rm1 += state.increment
  } 
~}

accessory / warmup: none / used: none / 3x12 100% / progress: custom(increment: 5lb) {~
  if (week % 4 == 0 && dayInWeek == 3) {
    rm1 += state.increment
  }
~}

Squat / ...main
Seated Leg Curl, Leverage Machine / 5x10 / warmup: none / progress: lp(5lb)
Seated Row, Cable / 5x10 / warmup: none / progress: lp(5lb)

## Day 2
Bench Press / ...main / progress: custom(increment: 5lb) { ...main }
Triceps Extension / 3x12 / warmup: none / progress: lp(5lb)

## Day 3
Deadlift / ...main
Leg Extension, Leverage Machine / 5x10 / warmup: none / progress: lp(5lb)
Pull Up, Bodyweight / warmup: none / 3x10 0lb


# Week 2
## Day 1
main / 1x3 63%, 1x3 72%, 1x3+ 81%, 5x5 63%
Overhead Press / ...main / progress: custom(increment: 5lb) { ...main }
Triceps Extension / 3x12 / warmup: none / progress: lp(5lb)

## Day 2
Squat / ...main
Seated Leg Curl, Leverage Machine / 5x10 / warmup: none / progress: lp(5lb)
Seated Row, Cable / 5x10 / warmup: none / progress: lp(5lb)

## Day 3
Bench Press / ...main / warmup: none / progress: custom(increment: 5lb) { ...main }
Triceps Extension / 3x12 / warmup: none / progress: lp(5lb)


# Week 3
## Day 1
main / 1x5 67%, 1x3 76%, 1x1+ 85%, 5x5 67%
Deadlift / ...main
Leg Extension, Leverage Machine / 5x10 / progress: lp(5lb)
Pull Up, Bodyweight / 3x10 0lb

## Day 2
Bench Press / ...main / progress: custom(increment: 5lb) { ...main }
Triceps Extension / 3x12 / progress: lp(5lb)

## Day 3
Squat / ...main
Seated Leg Curl, Leverage Machine / 5x10 / progress: lp(5lb)
Seated Row, Cable / 5x10 / progress: lp(5lb)


# Week 4 - Deload
## Day 1
main / 1x5 50%, 1x5 60%, 1x5 65%
Overhead Press / ...main / progress: custom(increment: 5lb) { ...main }

## Day 2
Squat / ...main

## Day 3
Deadlift / ...main



