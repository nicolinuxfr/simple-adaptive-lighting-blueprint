# Changelog

## 2026.3.5

- Greatly reduce the transition when the lights turn on, to minimize the display of the old settings (can't avoid flash, unfortunately) ;
- The transition after that stays smooth, and even longer now (15 seconds). 

## 2026.3.4

- New option to automatically reactivate the control entity when all lights are off. 

## 2026.3.3

- New option to automatically deactivate the control entity if you change the lights to display colors :
  - It's purely optionnal, by default you have to deactive the entity yourself ;
  - The blueprint do not handle the reactivation of the control entity, you have to it manually or in a different automation.

## 2026.3.2

- Simplification of the blueprint, with only three sections now : 
  - Main settings (brightness min/max and white temp min/max)
  - Advanced settings (control mode, weather adaptation)
  - Night mode

## 2026.3.1

- Full rewrite of README.md and texts inside the blueprint

## 2026.3

- Add night mode
- Add german translation