# gKreta
Based on Electron, this is a replacement for KRÉTA's web interface.

## Currently supported platforms:
* Windows (x64) (you can build the x86 libraries)
* Linux (x64) (you can build the x86 libraries)

## Functions
* You can easily select your school. (No need for that klik********* code.)
* A dashboard.
  * You can see statistics about your evaluations, absences... (In the future, much more.)
* All of your evaluations. 
* An organized timetable.
* All of your absences ordered by date.
* A settings panel.
* Two languages: English and Hungarian. (Again, in the future I add more.)

## Planned functions
* Display teacher notes.
* Create notes for yourself.
* Homeworks (Both student and teacher homeworks.)
* Refreshing data by auth token.
* In the timetable, switching between weeks.
* ...and much more!

### Current latest release:
0.2.1

## Setup the project
```
git clone https://github.com/thegergo02/gKreta.git
cd gKreta
npm install
npm start
```
## Build the project
(You need to get electron-packager)
(You need to be in the repository's root directory)
### Linux:
`electron-packager ./ --platform=linux --arch=x64`
### Windows:
`electron-packager ./ --platform=win32 --arch=x64`
### Mac:
**NOT SUPPORTED**
