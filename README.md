# DogFeeder
## Requirements
- Record datetime of feeding w/ amount on sd card (for transfer to PC)
- Display datetime since last feeding w/ amount.
- Buzz when feeder switch detected.
- Read configured amount (ounces) per switch from SD card.
- LED Error Indicator
  - SD Error (2 blinks)
  - RTC Error (3 blinks)
  - Other Error (4 blinks)
- Reservoir view window(s):
  - almost empty
  - almost full
- Reservoir food chute.
- Reservoir dispenser (w/ knob) ... wondering if 45 degree hole is ok or if a sweeper is needed.
- Future: Record datetime the feeder reservoir was filled. 
- Future: Display last three feedings datetime w/ amount.
- Future: Autofeeder (12vdc motor, extra feeder switch to detect 1/2 rotation)

## Assumptions
- Full amount of food released with each pull of the feeder arm.
- (Not Critical) Reservoir if completely filled each time the lid is opened. (Possibly used to provide a gross measure of the amount of food eaten over a long time).
- Future: Reservoir is filled to the top each time the lid is raised.
## HW Design Components
- Realtime Clock
- Feeder arm switch
- OLED Display (128x64)
- SD Card R/W
- LED
- Buzzer
- Processor
- Future: Reservoir lid switch
