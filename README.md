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

## Importing Audio

File > Import > Audio 

OR

Shift + Command + i

- Select clockwork.aif
- Convert/Copy
- Apply SRC (Sample Rate Conversion) Checked
- Tweak Head (Slowest)
- Done
- Audio Files folder
- Open
- New Track, Location: Session Start

Space Bar: Play Audio

## Tracks and Track Information

Window > Mix 

Input: No needed right now
Output: The default analog output

You can hide Tracks and Groups using this arrow at the bottom
![Screen Shot 2021-05-30 at 23 20 19](https://user-images.githubusercontent.com/51218415/120139211-9b08bf00-c19d-11eb-8eb9-54ecf3786c88.png)

You can see a mirror equivalent for Clips at the bottom right
![Screen Shot 2021-05-30 at 23 21 49](https://user-images.githubusercontent.com/51218415/120139320-d1463e80-c19d-11eb-8d64-eef828ea7d1e.png)

Edit Window View Selector

![Screen Shot 2021-05-30 at 23 25 55](https://user-images.githubusercontent.com/51218415/120139595-634e4700-c19e-11eb-84c3-9d1785b51e87.png)

Option + Click: Hide Edit View Option

A track can be resized vertically

Show/hide automation lanes

![Screen Shot 2021-05-30 at 23 29 16](https://user-images.githubusercontent.com/51218415/120139796-db1c7180-c19e-11eb-83f5-06e01e3b79fa.png)

- Volume
- Mute
- Pan
 
![Screen Shot 2021-05-30 at 23 30 53](https://user-images.githubusercontent.com/51218415/120139911-15860e80-c19f-11eb-9567-3ccbdb3555b7.png)

Elastic Audio

![Screen Shot 2021-05-30 at 23 47 16](https://user-images.githubusercontent.com/51218415/120141070-61d24e00-c1a1-11eb-8028-6b86fc88b7bc.png)

We can display:

![Screen Shot 2021-05-30 at 23 48 32](https://user-images.githubusercontent.com/51218415/120141141-8d553880-c1a1-11eb-81f4-dcaca2594ac7.png)

![Screen Shot 2021-05-30 at 23 51 37](https://user-images.githubusercontent.com/51218415/120141371-fa68ce00-c1a1-11eb-857f-0db0c9c5b77f.png) Record

![Screen Shot 2021-05-30 at 23 52 13](https://user-images.githubusercontent.com/51218415/120141412-0f456180-c1a2-11eb-9e3d-fbc7d19ab1ed.png) Solo

![Screen Shot 2021-05-30 at 23 52 28](https://user-images.githubusercontent.com/51218415/120141433-18363300-c1a2-11eb-9718-8b27427768fc.png) Mute

![Screen Shot 2021-05-30 at 23 54 30](https://user-images.githubusercontent.com/51218415/120141581-60edec00-c1a2-11eb-8876-6254ee597d20.png) Choose between Samples and Ticks

- Audio: Samples
- MIDI: Ticks

Double-click on name to rename a track:

![Screen Shot 2021-05-30 at 23 55 36](https://user-images.githubusercontent.com/51218415/120141676-88dd4f80-c1a2-11eb-87e6-bd6d73f1f781.png)

You can use a predefined vertical size by clicking the gray metric ruler:

![Screen Shot 2021-05-30 at 23 58 08](https://user-images.githubusercontent.com/51218415/120141842-e4a7d880-c1a2-11eb-84e6-9c8f9ed42903.png)

You can create a new track by:

Track > New

OR

Shift + Command + N

![Screen Shot 2021-05-31 at 0 00 04](https://user-images.githubusercontent.com/51218415/120142021-29337400-c1a3-11eb-8a98-8ce277974b87.png)

Create New Mono Audio Track:

![Screen Shot 2021-05-31 at 0 04 23](https://user-images.githubusercontent.com/51218415/120142327-c393b780-c1a3-11eb-98d7-66473ebd8b91.png)

If I bring the Stereo Audio File into the new Mono Track it won't go

It will go into the Stereo Track above it, but not in the Mono Track below

However if I grab one of the Mono files, it will go

![Screen Shot 2021-05-31 at 0 07 21](https://user-images.githubusercontent.com/51218415/120142623-2d13c600-c1a4-11eb-9db3-ad7c78f80a08.png)

Control + Rigth click on track name: I can delete it

## Clips And Clip Edits

You can remove time measure indicator with:
Opton + Click

Or simply by selecting the checkboxes

![Screen Shot 2021-08-01 at 20 06 17](https://user-images.githubusercontent.com/51218415/127791660-57c7252b-8224-4e57-b333-a79282852e7e.png)

You can also adjust the height of the waves by clicking the ruler that is just before the wave:

![Screen Shot 2021-08-01 at 20 08 57](https://user-images.githubusercontent.com/51218415/127791803-e13a4254-e3e7-4486-a75f-e7e966935101.png)


![Screen Shot 2021-08-01 at 20 11 42](https://user-images.githubusercontent.com/51218415/127791964-94e5f671-0c43-4dfd-8070-089a87353a19.png)

The left arrow to Zoom Out ( Commamd + [ )

The right arrow to Zoom In ( Commamd + ] )

![Screen Shot 2021-08-01 at 20 14 50](https://user-images.githubusercontent.com/51218415/127792114-110de352-b4b7-41a0-a3ae-613a123e337b.png)

Selector Tool:

![Screen Shot 2021-08-01 at 21 14 24](https://user-images.githubusercontent.com/51218415/127795627-6be0fdc0-87fb-455a-aec5-5a97ea9227ca.png)

Separate Clip ( Command + E ): 

Edit > Separate Clip > At Selection

Separating Clock audio in 3 clips:

![Screen Shot 2021-08-01 at 21 21 14](https://user-images.githubusercontent.com/51218415/127796123-ddda578d-fd59-4058-9987-53e568d685e0.png)

You can activate the grid by clicking in Grid:

![Screen Shot 2021-08-01 at 21 23 58](https://user-images.githubusercontent.com/51218415/127796300-8c2683be-6eb6-4293-b6b2-046d78d128d5.png)

And it would look like this:

![Screen Shot 2021-08-01 at 21 24 57](https://user-images.githubusercontent.com/51218415/127796370-d941ecaa-02a0-4885-95a0-68c43667fc74.png)

Grabber Tool:

![Screen Shot 2021-08-01 at 21 26 05](https://user-images.githubusercontent.com/51218415/127796454-276f069a-7ec2-4848-b219-6ca8e267f4b8.png)

Double-click the first Clip and rename it as "ticking"

Double-click the first Clip and rename it as "windup"

Double-click the first Clip and rename it as "chime"

If you select all (Command + A) and delete them, you are going to be able to recover them from the Clip Menu

![Screen Shot 2021-08-01 at 21 31 48](https://user-images.githubusercontent.com/51218415/127796817-8a017c9f-fc04-4be5-bcd4-d1d918931d50.png)

The bold clip is the parent one

