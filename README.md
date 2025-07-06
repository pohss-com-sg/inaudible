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
  

## Room for Improvement
- Personalisation page
- Nutrition tracker
- Multilingual UI
- Voice-powered AI (speech-to-text with vosk)
- Image recognition of food items (ChatGPT)
- UI/UX Improvement


## Acknowledgements
- This project was inspired by our conference group name 'i8' (a homophone of 'I ATE')
- Many thanks to...
  - [https://buildingblocs.sg/] for very helpful coding and AI workshops
  - [https://gemini.google.com] for the API and database jsonfile
  - [https://bulldogjob.com/readme/how-to-write-a-good-readme-for-your-github-project] for the README.md reference
  - [https://chatgpt.com/?model=gpt-4o] for research of prevalence of dietary restrictions
  - [https://www.ncbi.nlm.nih.gov/] for research of prevalence of dietary restrictions
