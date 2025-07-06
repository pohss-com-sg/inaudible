![Logo](https://github.com/pohss-com-sg/inaudible/blob/main/image.png)

# inAudible
### This project was made by GESS Team 2 for MGS-NYP Young Catalysts Micro:bit Challenge 2022. 
Thank you, Chi Ieng and Amanda, for being amazing teammates! <3
> inAudible guides teachers and students to have a conducive learning space, one 'beep' at a time.

## Code
[**Access here!**](https://makecode.microbit.org/77137-70565-82481-95735)

## Table of Contents
* [General Information](#general-information)
* [Technologies Used](#technologies-used)
* [Ideation](#ideation)
* [Prototype](#prototype)
* [Discussion](#discussion)
* [Photos](#photos)
* [Acknowledgements](#acknowledgements)

## General Information
> Excessive noise negatively impacts both the students' learning and the teachers' teaching, whether it is in the same classroom or classrooms close to the noisy classroom, and can disrupt the serenity of the school environment.

### What we Want to Achieve
- Empower students and student leaders to be more self disciplined, with real time feedback
- Provide a more conducive learning environment
- Reduce disruption to other nearby classes and teachers
- Provide data to help teachers manage class

### Themes Covered
- Student well-being - Students enjoy a more conducive learning environment, and experience less stress
- Staff well-being - Teachers spend less time and effort managing class, and experience less stress
- Teachingand learning - Students enjoy a more conducive learning environment, learn to self-regulate, and exercise personal responsibility and leadership skills
- School environment - A more conducive environment for everyone

## Ideation
A noise level monitor with 4 preset levels of noise, and appropriate response:
* Noise level 1: Acceptable noise level (students may be discussing work)
* Noise level 2: Gentle reminder to the students to lower down their volume
* Noise level 3: Warning for students to lower their volume
* Noise level 4 (consistent): Warning for students to lower their volume. A message is also sent to the general office and form teachers to inform that the class is too noisy consistently, and from there send a nearby teacher to help manage the class.

## Prototype
### Design
![Prototype design](https://github.com/pohss-com-sg/inaudible/blob/main/prototype.jpg)

### How the code works
* Detect noise level using built-in microphone of microbit v2, and this is calibrated to match the dB measurement system (using another sound detection app in a smartphone, and a sound wave generator)
  ![Table](https://github.com/pohss-com-sg/inaudible/blob/main/table.png)
* At each noise level, the microbit LED display and extemal LED lights will show the appropriate facial expression symbols and LED colours
* At the same time, data (level and duration) is collected into the built-in storage, that the teacher can download and use.
* We also envision having the microbit wirelessly transmit the data to other receivers, and even made available on a web-app, so that the real time information can be accessed by the general office and teachers.

## Discussion
* Our prototype mainly benefits the students that want to study when no teacher is around and also helps reduce the need of Teachers having to come over and watch the class.
* The current InAudible prototype does not cost much as it is only powered by a microbit and simple components.
* However, we may enhance the display with larger and more visible graphics on larger screens to improve visibility for the whole class, and these may be costly to install.

### inAudible enhances leadership qualities in each student, and helps them concentrate on work when no teacher is around. There are some possible improvements to this system for future iterations, to improve effectiveness.

## Photos

## Acknowledgements
We had a really interesting time with this project, and learnt a lot from this experience.
We would like to thank the following for their support to our team:
* **Methodist Girls' School** and **Nanyang Polytechnic** for organising the competition, for the Microbit training, and for hosting our tour at the NYP MakerSpace.
* Our **teachers** for guiding and supporting us: Mr Tan, Mr Kwok, Mr Lim, Mr Quek.
* Our **mentors** for mentoring us.
* Our **friends** from the other teams for their encouragement and friendship.

