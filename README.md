# avid-protools-12-fundamentals

# Introduction

A soundtrack for a cinematic movie or a commercial or a game has 3 elements (DME):
- Dialogue - is shorthand for any spoken word like an announcer track
- Music - is anything from a symphony orchestra to a drone from a didgeridoo 
- Effects - is anything from breathing to giant explosions

Plugins are software enhancements to the application that let you perform specialized processing


## Installing and Authorizing Pro Tools
Pro Tools - Software Installation Guide
- iLok

## Application Manager and Hardware Options
Setup > Hardware

![alt text](https://user-images.githubusercontent.com/51218415/119301762-99347e00-bc28-11eb-9dc2-0fb21beed563.png)


Setup > Disk Allocation - you can assign where you want to put the audio for that track

![alt text](https://user-images.githubusercontent.com/51218415/119301854-bec18780-bc28-11eb-9ed9-d1b59480a140.png)

Note: Recoding to your system drive is allowed but not recommended

Pro Tools System Requirements and Compatibility
- https://avid.secure.force.com/pkb/articles/compatibility/Pro-Tools-System-Requirements

## Playback Engine Options

Setup > Playback Engine 

![Screen Shot 2021-05-27 at 1 11 25](https://user-images.githubusercontent.com/51218415/119774882-7902fa00-be88-11eb-8d49-44b0cdf82723.png)

When you change the output Pro Tools has to quit your session make the change and then reopen your session

**Hardware Buffer Size**
The simple choice here is you want to use the one that's the fastest without compromising your sound
If I go to 32 in the regime that I've set up here with running the app, running the operating system, recording audio and making movies at the same time I'm probably going to get a glitch. 
I'm content with 256. Most of the time that's going to be fine. 
Notch up if your system can handle it. Smaller is better. But not if it causes you a glitch.

Ignore Errors during Playback/Record - DISABLE
Video Engine - DISABLE

## Signal Flow in Pro Tools

Setup > Hardware
Setup > I/O

**SHORTCUT: Command + Left/Right Arrow to move between tabs**

Inputs:
Examples are microphones, musical instruments like guitars and basses, keyboards, turntables, things that would send audio signals into Pro Tools

Outputs:
Examples are speakers which in the world of audio production we call monitors and headphones.
We can also output digitally to other devices, that's what S/PDIF is all about

Buses:
When you want to send multiple signals to the same place you put them on a bus 

Inserts:
Are things that come between the input and the output.
Examples are reverbs, delays, compressors, other types of digital sound processing gear and sometimes we put the insert on a track and sometimes we put it on a bus.

Preamps:
This would be a digital patch bay where you could set up your Pro Tools routing.

**ADVICE: When you find settings that are working for you, export them. This will export them to the correct place**
If you import settings from that file it will only import the active tab, you can apply it to all tabs using "Apply to all tabs"

## Digital Audio 101
ProTools process audio digitally as zeros and ones.
Our ears can hear from about 20 cycles on the low end to about 22000 cycles on the high end.
In the world of music you're going to use 44.1kHz
In the world of video you're going to use 48kHz

Bit Depth:
Let us perceive dynamic range, the louds and the softs
Most people these days are comfortable at 24
Legacy sessions are more likely to be 16
So a 24 bit resolution is 50 percent higher quality than a 16 and that gives you a more accurate dynamic range

File Type:
BWF - Broadcast Wave File

# Basic Editing in The Timeline

## Creating A Session

- Importing
- Editing
- MIxing
- Exporting

Create

- Name: clock
- File type: BWF
- Bit Depth: 24-bit
- Sample Rate: 48kHz
- I/O Settings: Last Used
- Interleaved: Unchecked

Basic Editing Window of Pro Tools
![Screen Shot 2021-05-30 at 22 48 02](https://user-images.githubusercontent.com/51218415/120137054-19169700-c199-11eb-863d-aa2ceb61a173.png)

Transport Window
![Screen Shot 2021-05-30 at 22 50 22](https://user-images.githubusercontent.com/51218415/120137210-6c88e500-c199-11eb-9051-0623fbb7c765.png)

Mix Window


![Screen Shot 2021-05-30 at 22 52 14](https://user-images.githubusercontent.com/51218415/120137340-b1148080-c199-11eb-956b-474620851564.png)

