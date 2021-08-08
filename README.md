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

**Selector Tool** (F7):

![Screen Shot 2021-08-01 at 21 14 24](https://user-images.githubusercontent.com/51218415/127795627-6be0fdc0-87fb-455a-aec5-5a97ea9227ca.png)

Separate Clip ( Command + E ): 

Edit > Separate Clip > At Selection

Separating Clock audio in 3 clips:

![Screen Shot 2021-08-01 at 21 21 14](https://user-images.githubusercontent.com/51218415/127796123-ddda578d-fd59-4058-9987-53e568d685e0.png)

You can activate the grid by clicking in Grid:

![Screen Shot 2021-08-01 at 21 23 58](https://user-images.githubusercontent.com/51218415/127796300-8c2683be-6eb6-4293-b6b2-046d78d128d5.png)

And it would look like this:

![Screen Shot 2021-08-01 at 21 24 57](https://user-images.githubusercontent.com/51218415/127796370-d941ecaa-02a0-4885-95a0-68c43667fc74.png)

**Grabber Tool** (F8):

![Screen Shot 2021-08-01 at 21 26 05](https://user-images.githubusercontent.com/51218415/127796454-276f069a-7ec2-4848-b219-6ca8e267f4b8.png)

Double-click the first Clip and rename it as "ticking"

Double-click the first Clip and rename it as "windup"

Double-click the first Clip and rename it as "chime"

![Screen Shot 2021-08-01 at 23 19 57](https://user-images.githubusercontent.com/51218415/127803860-ae6f8681-486a-4c7a-aa5c-d224e1504c47.png)

If you select all (Command + A) and delete them, you are going to be able to recover them from the Clip Menu

![Screen Shot 2021-08-01 at 21 31 48](https://user-images.githubusercontent.com/51218415/127796817-8a017c9f-fc04-4be5-bcd4-d1d918931d50.png)

The bold clip is the parent one

## Smart Tools and Edit Modes

If you want to enable F1, F2, F3 and F4 you should go to:

System Preferences > Keyboard > Enable the checkbox

![Screen Shot 2021-08-01 at 23 30 39](https://user-images.githubusercontent.com/51218415/127804520-183e64f8-a3f0-40e8-a953-b41feefc009a.png)


ProTools Editing Modes:
- **Shuffle** (F1 / Option + 1) - Adds clip at the first gap is there, but can't move clips, just reattach
- **Slip** (F2 / Option + 2) - Adds clip where your cursor is
- **Spot** (F3 / Option + 3)
- **Grid** Absolute & Relative (F4 / Option + 4)

![Screen Shot 2021-08-01 at 23 23 19](https://user-images.githubusercontent.com/51218415/127804014-77e64b57-39d5-4654-831e-d8eccc317c3f.png)

Trim Tool (F6) - Change where a clip starts and ends:

- **Shuffle** - Change the start/end and fill the gaps
- **Slip** - Change the start/end but leave the space empty

![Screen Shot 2021-08-01 at 23 40 27](https://user-images.githubusercontent.com/51218415/127805110-a38c8aec-0e8f-4ff9-a0bd-0c7811867e1f.png)

Smart Tool (3 icons selected) (F6+F7):
- Upper Region - Region Selector
- Lower Region - Grabber 
- Middle Line - Trimmer

![Screen Shot 2021-08-01 at 23 46 11](https://user-images.githubusercontent.com/51218415/127805463-e4302179-d2bd-48a1-bddc-aeba2f31cfc2.png)

## Counters, Grid and Nudge

**Scrubber Tool** - scrubs whatever audio you select:

![Screen Shot 2021-08-02 at 0 06 27](https://user-images.githubusercontent.com/51218415/127806928-6f729aca-9c9b-4e32-aa44-40b878356238.png)

**Pencil Tool** - Automation moves, notes into a MIDI track:

![Screen Shot 2021-08-02 at 0 10 25](https://user-images.githubusercontent.com/51218415/127807166-d51abe7d-ffc4-4383-b0cb-5c43e193b83a.png)

### Counters

**Main Counter**

Tells you where the cursor is at any given second:

![Screen Shot 2021-08-02 at 0 14 08](https://user-images.githubusercontent.com/51218415/127807404-f8cbaa06-348e-4c70-9209-cdbb0ad1fe99.png)

You can change this counter and even add a subcounter:

![Screen Shot 2021-08-02 at 0 15 26](https://user-images.githubusercontent.com/51218415/127807521-85f20bea-aa5e-4496-8b20-261074c27c55.png)

**Edit Selection End**

While selecting a clip it tells you where it starts, ends and its length

![Screen Shot 2021-08-02 at 0 18 49](https://user-images.githubusercontent.com/51218415/127807775-cc5eaf02-f94c-4378-bd9d-e43543e0302d.png)

**Nudge Custom Value**
- **Grid** - Enables Grid 
- **Nudge** (Comma/Dot) - Move clip in those increments in "Keyboard Focus"
  - Comma - Move to the left
  - Dot - Move to the right

![Screen Shot 2021-08-02 at 0 20 24](https://user-images.githubusercontent.com/51218415/127807893-5dccba4d-d225-4866-a0f1-b8cd1b357755.png)

![Screen Shot 2021-08-02 at 0 23 07](https://user-images.githubusercontent.com/51218415/127808181-6db9519e-4e50-4dcb-bdc9-4c7ae5dfd1b0.png)

**Keyboard Focus**:

![Screen Shot 2021-08-02 at 0 27 18](https://user-images.githubusercontent.com/51218415/127808524-63e09451-084d-4e1d-8bd3-29db8e9455a5.png)

**Play** (Spacebar):

![Screen Shot 2021-08-02 at 0 34 18](https://user-images.githubusercontent.com/51218415/127809108-e9dfcb90-db30-4e18-b4bb-3eaa64f0a540.png)

**Output Meter Path**:

![Screen Shot 2021-08-02 at 0 36 53](https://user-images.githubusercontent.com/51218415/127809281-42739f82-7cf9-4e2e-b9b1-3a1fff4bd50d.png)

You can show/hide views by clicking the arrow at the top right:

![Screen Shot 2021-08-02 at 0 39 22](https://user-images.githubusercontent.com/51218415/127809505-698431a8-a3f9-4f3a-9b53-11199b069e1a.png)

You can rearrange the order of the views by clicking Command and drag and drop the views

## Trim, Clip Volume and Duplicate

**Trim Clip to Selection** (Command T):

Select a part of a clip > Edit > Trim Clip > To Selection

![Screen Shot 2021-08-02 at 4 25 20](https://user-images.githubusercontent.com/51218415/127838147-275ff73c-e439-4809-9819-bcbca908422a.png)

**Duplicate** (Commad D):

Select a part of a clip > Edit > Duplicate

![Screen Shot 2021-08-02 at 4 34 32](https://user-images.githubusercontent.com/51218415/127839559-b082100b-7f8a-4fbe-8edd-730db40714d6.png)

**Repeat** (Option R):

Select a part of a clip > Edit > Repeat

![Screen Shot 2021-08-02 at 4 36 05](https://user-images.githubusercontent.com/51218415/127839851-2fb3da9c-dd5b-4f9d-8a65-e96fa1db704b.png)

![Screen Shot 2021-08-02 at 4 37 08](https://user-images.githubusercontent.com/51218415/127839924-a24af655-d01d-4f07-a1d2-3bdb5f0fb7a0.png)

**Clip Volume**:

Is at the bottom left of every clip

![Screen Shot 2021-08-02 at 4 40 11](https://user-images.githubusercontent.com/51218415/127840394-9f1edc32-dc63-49c2-9567-652329e6f8b2.png)

**Crossfader**:

Smart Tool Selected > Bottom part in the separation of two clips

![Screen Shot 2021-08-02 at 4 47 57](https://user-images.githubusercontent.com/51218415/127841680-f8259d4e-35b3-435b-b2c5-34f627375974.png)

## Consolidate and Export

**Consolidate** (Option + Shift + 3):

Edit > Consolidate Clip

![Screen Shot 2021-08-02 at 4 56 14](https://user-images.githubusercontent.com/51218415/127843066-e981f5f5-050b-4475-8ed1-e5be5d8d2253.png)

Rename Clip - Double click on the Clip

![Screen Shot 2021-08-02 at 4 58 12](https://user-images.githubusercontent.com/51218415/127843367-7683ac6e-4cd4-4916-90d0-3339b9339058.png)

**Export Clip**:

Select the consolidated clip > Right Click > Export Clips as Files

![Screen Shot 2021-08-02 at 5 02 13](https://user-images.githubusercontent.com/51218415/127843965-a3203653-33b2-4c8e-a7ae-8d1ff32284a5.png)

**Export Options**
- File Type: 
  - WAV - for quality
  - MP3 - for faster transfer
- Format
  - (Multiple) Mono - if you are sending the files to another ProTools user
  - Interleaved - for final edition

Notes: consolidate is only when you only have 1 track, if you have multiple tracks you should use the Bounce command

# Customizing Pro Tools

Open System Preferences > Keyboard > Shortcuts > App shortcuts > +

**Application:** Pro Tools
**Menu Title:** Hide Pro Tools
**Keyboard shortcut:** Command+H

And click on **Add**

**Folder Structure in a Pro Tools Project:**
- Audio Files - imported or recorded audio files
- Bounced Files - default folder for bounced files
- Clip Groups
- Session File Backups
- Video Files
- WaveCache.wfm file
- .ptx file - Pro Tools Session 

Create 3 Mono Tracks and 3 MIDI Tracks:

![Screen Shot 2021-08-08 at 9 28 45](https://user-images.githubusercontent.com/51218415/128635495-e0afb5eb-c584-4a5b-8bdd-b812901da505.png)

## Options for Saving Sessions

- Save - save the last changes in the same session
- Save As - save in a different session

It's smart to have multiple session files for a project and use the date to reference the day

- Save Copy In - save the session and audio files of the session (you have to select the checkbox)

![Screen Shot 2021-08-08 at 9 53 12](https://user-images.githubusercontent.com/51218415/128636280-cdb856ef-b2a5-4781-8e56-42c5f53f9165.png)

You can also send a legacy version of the project in case you are going to send it to someone that hasn't updated ProTools in many years:
![Screen Shot 2021-08-08 at 9 54 47](https://user-images.githubusercontent.com/51218415/128636354-b852a357-f1a7-448d-8cf3-5ac0ac4cd28a.png)

- Save as Template
  - Install template in system - if you are working in your own computer
  - Select location for template - if you are working in school's computer

In the Music category, the names are different genres:

![Screen Shot 2021-08-08 at 9 58 05](https://user-images.githubusercontent.com/51218415/128636437-cfb1f371-b6b2-4680-85e1-43d5856a7ad3.png)

In the Postproduction category, the names are different setups:

![Screen Shot 2021-08-08 at 9 58 52](https://user-images.githubusercontent.com/51218415/128636456-eaf02f58-f68e-4976-85bd-58cae25733b8.png)

Or you can create a new Category:

![Screen Shot 2021-08-08 at 10 00 34](https://user-images.githubusercontent.com/51218415/128636497-853ebc93-78b9-4501-853b-62cc823a8618.png)

Or create a New Style by typing in the box

A Template is a `.PTT` file, is different from the session 

## Pro Tools Preferences - Part 1

Pro Tools (Menu) > Preferences

OR

Setup > Preferences

![Screen Shot 2021-08-08 at 10 59 02](https://user-images.githubusercontent.com/51218415/128638089-26444590-c74d-4ed6-b36e-a1ea279da147.png)

**Display** Tab
- Tool Tips - little yellow popups that are helpful when you're learning Pro Tools
- Edit Window Default Length - if you work in commercials you can set it to 30 or 60 seconds, if you work in pop music and your average song is 4 minutes you can set it to that value
- Organize Plug-In Menus By - 

By Category:

![Screen Shot 2021-08-08 at 11 07 17](https://user-images.githubusercontent.com/51218415/128638293-a0382ece-1e30-45b9-a1d2-807ed37f2880.png)

Flatlist:

![Screen Shot 2021-08-08 at 11 08 38](https://user-images.githubusercontent.com/51218415/128638329-86cfef59-5ec9-42ba-a987-2aec1edd00b6.png)

By Category & Manufacturer:

![Screen Shot 2021-08-08 at 11 10 00](https://user-images.githubusercontent.com/51218415/128638357-727fcc47-f84d-47d3-84b0-d3ff60630a04.png)

- Show Dashboard Window when Pro Tools starts
- MIDI Note Color Shows Velocity - high velocity notes show up as bright red, and low velocity notes show up as pale blue

**Operation** Tab
- Play Start Marker Follows Timeline Selection
- Auto Backup
- User Media and Settings Location
- Record - Automatically Create New Playlist When Recording Loop

**Editing** Tab
- Levels of Undo
- Tracks - New Tracks Default to Tick Timebase: useful for composing MIDI

**Mixing** Tab
- Setup - Default EQ - EQ3 7-Band

In the Mix Window is going to show at the top:

![Screen Shot 2021-08-08 at 11 26 21](https://user-images.githubusercontent.com/51218415/128638812-a46071d9-95e4-49cf-9bf0-e5f6528853f1.png)

- Automation - Latch

## Pro Tools Preferences - Part 2

**Metering** Tab
- Track and Meter Types - Track and Meter Types Linked
- Advanced Meter Type Settings - Color Break is when it goes from Green to Yellow to Red
- Peak/Clip
  - Peak Hold - 3 seconds
  - Clip Indication - Infinite   

**Processing** Tab
- Import
  - Convert imported ".wav" files to AES31/Broadcast Wave
  - Automatically copy files on import 
  - Sample Rate Comversion Quality - TweakHead
- TC/E 
  - TC/E plug-in - you can choose your default time compression plugin when you use TC/E trimer
  - Default Settings - you can choose the algorithm
- Elastic Audio

**MIDI** Tab
- Basics
  - Use MIDI to tap tempo
  - Use F11 Key to Wait For Note
  - Default Thru Instrument
  - Double-clicking a MIDI Clip opens - MIDI Editor

**Synchronization** Tab
- Machine Control

Hide Pro Tools, go to Finder > Go > Press `Option` > Library

When Pro Tools misbehaves you can trash the file:

`Library/Preferences/ByHost/com.avid.ProTools.plist`

If that doesn't work the trash the file:

`Library/Preferences/Avid/Pro Tools/Pro Tools Prefs`

## Windows Layouts and Scroll Options


