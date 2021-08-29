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

## Window Layouts and Scroll Options

There are 2 Main Windows in Pro-Tools
- Edit Window
- Mix Window

**Edit Window**:

![Screen Shot 2021-08-08 at 12 36 44](https://user-images.githubusercontent.com/51218415/128640613-017dca41-5d50-487f-9f6b-00c69f4fe0c8.png)

**Mix Window**:

![Screen Shot 2021-08-08 at 12 36 24](https://user-images.githubusercontent.com/51218415/128640601-52e21cec-17ba-4957-b7a8-c4b37ccf3e06.png)

You can shift between both windows using `Commad + =`/`Command + Shift + 0`

In Window Menu > Arrange > Tile - to have both windows

Window > Configurations > New Configuration - When you found a Configuration that you liked

**Transport Window** (Command + Keypad 1):

![Screen Shot 2021-08-08 at 12 45 16](https://user-images.githubusercontent.com/51218415/128640822-e23d5234-6fa2-40a5-81a0-76b545e9fb7e.png)

![Screen Shot 2021-08-08 at 12 46 06](https://user-images.githubusercontent.com/51218415/128640846-1eb74509-da52-436f-9e75-578739421ef4.png)

**Big Counter Window** (Command + Keypad 3):

![Screen Shot 2021-08-08 at 12 47 12](https://user-images.githubusercontent.com/51218415/128640872-ac60fc4f-9d7f-41a8-8875-58fed488f964.png)

**Zoom Out** (Command + [)

**Zoom In** (Command + ])

**Normal Zoom / Single Zoom** (F5)

![Screen Shot 2021-08-08 at 12 52 31](https://user-images.githubusercontent.com/51218415/128641018-680a9aa8-2129-4350-acc5-3b3ac5bc36c9.png)

Choose Single Zoom Tool > Be sure you're in Keyboard Focus > Press E

It will go from this:

![Screen Shot 2021-08-08 at 13 00 18](https://user-images.githubusercontent.com/51218415/128641241-00bd95d1-18a6-4878-a949-b1fd14a41fdf.png)

To this:

![Screen Shot 2021-08-08 at 13 00 44](https://user-images.githubusercontent.com/51218415/128641251-5c2cad11-295c-4217-b6d5-eff99cbc5a4f.png)

**Link Playback Cursor and Edit Cursor**:

![Screen Shot 2021-08-08 at 13 04 05](https://user-images.githubusercontent.com/51218415/128641340-422317c1-e41f-4926-9cb2-4a1affc5a07f.png)

OR

Options (Menu) > Link Timeline and Edit Selection

Options (Menu) > Edit Window Scrolling

![Screen Shot 2021-08-08 at 13 23 52](https://user-images.githubusercontent.com/51218415/128641868-0a012fd2-c7ca-4d3f-809c-38af36595867.png)

## Sorting in the Clip Bin

Clips > Timeline Drop Order
- Top to Bottom - If dragged and drop, the clips will go in different tracks
- Left to Right - If dragged and drop. the clips will go in the same track

![Screen Shot 2021-08-08 at 17 38 26](https://user-images.githubusercontent.com/51218415/128647733-c10fb6d0-5431-48b3-8ae8-b64673e1a1b5.png)

## Clearing and Deleting Files

Clips > Clear

## Showing and Hiding Tracks

Each Track Type has a different Icon:

![Screen Shot 2021-08-08 at 17 45 21](https://user-images.githubusercontent.com/51218415/128647890-e50b64d2-9b8d-4872-bb5c-d50485cb1758.png)

You can reorder the tracks by reordering them in the Track Bin

Recommended Order:
- Audio Stuff (Audio Tracks)
- Scoring Stuff (MIDI Tracks)
- Our Processing (Aux and Master Tracks)

We want to have Master as the last so it appear at the right in the Mix Window:

![Screen Shot 2021-08-08 at 17 49 19](https://user-images.githubusercontent.com/51218415/128647980-a7333034-805e-4b3a-b369-6bb094efc266.png)

We can Show or Hide Tracks with different options:

![Screen Shot 2021-08-08 at 17 50 46](https://user-images.githubusercontent.com/51218415/128648006-571f1897-5905-47e4-9429-2821fee16d88.png)

The M is for muting the track:

![Screen Shot 2021-08-08 at 17 52 27](https://user-images.githubusercontent.com/51218415/128648033-08a48f59-00a3-4dea-b702-90d7ee97ef3a.png)

## Track and Clip Colors

If you double-click in the color at the left of the track you can change it:

![Screen Shot 2021-08-08 at 17 56 06](https://user-images.githubusercontent.com/51218415/128648099-e9c90417-e6b0-4fd8-8d00-3ce64df0fefe.png)

You can change the color of the entire spectrum information by clicking this button:

![Screen Shot 2021-08-08 at 17 57 25](https://user-images.githubusercontent.com/51218415/128648124-d0278719-ffa5-4670-9b10-f75415cc573e.png)

You can select the color for Clips or Tracks:

![Screen Shot 2021-08-08 at 17 58 50](https://user-images.githubusercontent.com/51218415/128648154-9e6857e8-940f-4db3-93ec-e5c657807658.png)

By clicking in the bottom left icon you can add extra info as Volume, Mute and Pan:

![Screen Shot 2021-08-08 at 18 02 14](https://user-images.githubusercontent.com/51218415/128648217-77bb2fd1-debe-4cc7-8217-ff5c3a24d265.png)

## Session Parameters

Setup > Session (Command + Keypad 2)

![Screen Shot 2021-08-08 at 18 04 33](https://user-images.githubusercontent.com/51218415/128648257-f1b49123-38ff-48a7-a791-13383427877f.png)

Sample Rate is fixed, I cannot change that at the middle of the game

## New Workspace Browser

![Screen Shot 2021-08-08 at 18 09 01](https://user-images.githubusercontent.com/51218415/128648343-5a32d1e6-a3da-4c72-a1d2-011afcfc38ca.png)

You can search for audio files for example

You can setup 5 presets with different columns/window size

# Recording and Editing a Voice Track

## Setting Mic Input Levels

Power On Phantom Power After you plug it 
Power Off Phantom Power Before you unplug it

Once your interface and microphone are connected

Setup > Playback Engine > Select your Audio Interface

![Screen Shot 2021-08-08 at 19 10 13](https://user-images.githubusercontent.com/51218415/128649834-fb165362-0202-4adc-9bfb-44ec5a58afe5.png)

In you I/O options assign an input to your Audio Track:

![Screen Shot 2021-08-08 at 19 12 35](https://user-images.githubusercontent.com/51218415/128649886-01e936f7-40a6-4e21-82c2-476fe0fc49b7.png)

Then select the red circle icon and will be able to see audio being detected

![Screen Shot 2021-08-08 at 19 14 30](https://user-images.githubusercontent.com/51218415/128649938-793e5549-1742-4c5b-a9d9-e29d20a5b823.png)

- Gain Level - Set the perfect one for your specific recording and performer
- Room tone - is the term for ambient sound in a recording, be careful where you record
- Plosives - `p` and `s` are the main culprits
- Proximity effects - closer to the mic, the lower frequencies become more dominant

## Setting Up a Cue

![Screen Shot 2021-08-08 at 19 48 31](https://user-images.githubusercontent.com/51218415/128651016-6dd3acba-f7fc-4bc8-aeed-dae73b1376b6.png)

Options > Enable Delay Compensation

Options > Enable Low Latency Monitoring

Click the Record Icon and the Play Icon to start recording

![Screen Shot 2021-08-08 at 19 51 40](https://user-images.githubusercontent.com/51218415/128651106-a912b3c1-6515-48ae-8e0b-95fa50c4a3f0.png)

You can move to the Mix Window and add a Reverb:

![Screen Shot 2021-08-08 at 19 58 40](https://user-images.githubusercontent.com/51218415/128651346-26c1af46-3017-4697-82a5-48381a5cf29e.png)

With this option you can select how Wet/Dry the reverb is:

![Screen Shot 2021-08-08 at 20 00 42](https://user-images.githubusercontent.com/51218415/128651411-b11d6dbf-a454-47dc-a9c1-38f6c6edb7c5.png)

Create a Mono Aux Track:

You can drag and drop the reverb

Set AVO Track Output to Buses 3-4

Set Input for Aux Track for Bus 3

And now you can adjust the volume of the reverb independently

![Screen Shot 2021-08-08 at 20 14 51](https://user-images.githubusercontent.com/51218415/128651839-0796589b-15af-4124-968e-38be2b05bcfb.png)

## The 1-2-3 System

![Screen Shot 2021-08-08 at 21 48 52](https://user-images.githubusercontent.com/51218415/128655675-d40b8517-6a88-495e-bd7b-c08ba63ab8f5.png)

## The Separation Grabber

Right Click the Grabber:

![Screen Shot 2021-08-08 at 21 50 19](https://user-images.githubusercontent.com/51218415/128655762-e1c66df8-9949-4649-9ded-33b1af2df8e7.png)

Enable Suffle Mode

With the Smart Tool Enable Select the first part that you want

With `Option` pressed drag from the bottom part 

![Screen Shot 2021-08-08 at 21 57 41](https://user-images.githubusercontent.com/51218415/128656094-94c4250b-e999-45d9-bb5c-804f31c4a464.png)

Remember that you can cut adjust volume just for certain clip in the bottom left

![Screen Shot 2021-08-08 at 22 04 36](https://user-images.githubusercontent.com/51218415/128656399-87d267ec-ca4f-40d8-8098-cc70aed395c6.png)

If you go to Mix Window and `press option while dragging and drop` a send you can duplicate it

![Screen Shot 2021-08-08 at 22 07 11](https://user-images.githubusercontent.com/51218415/128656516-90cce9fb-130b-4764-90b4-6c619df794a2.png)

![Screen Shot 2021-08-08 at 22 09 44](https://user-images.githubusercontent.com/51218415/128656640-5a657350-faf5-4a5a-b748-82b5090f5cbf.png)

## Music in the Cue

Using music in the cue it's one way to enhance the performance that you record

![Screen Shot 2021-08-08 at 23 00 42](https://user-images.githubusercontent.com/51218415/128659087-68664d28-833c-467e-9c87-fcebdb541485.png)

## FX in the Cue

If a Bus is Post-Fader (Default) then if you lower the volume of the origin is not going to send much audio to the aux track

Selecting the PRE button will make the bus to be Pre-Fader

Using Pre-Fader bus you can lower the volume of the original voice and just hear the processed output

![Screen Shot 2021-08-08 at 23 08 57](https://user-images.githubusercontent.com/51218415/128659579-4a5e4031-333a-46d3-baa9-3ffd1a63a457.png)

## Breathless

You can cut and remove the duplicates in Shuffle Mode to make a dialog that looks like there were no pauses to take a breath

![Screen Shot 2021-08-08 at 23 32 54](https://user-images.githubusercontent.com/51218415/128660670-44717af6-db0b-4e97-b70c-33f2761d1885.png)

## The TCE Trimmer

TCE Trimmer = Time Expansion and Compression Trimmer

Right Click the Trimer Icon and you'll see this options

![Screen Shot 2021-08-08 at 23 39 05](https://user-images.githubusercontent.com/51218415/128660972-b116281c-6417-421b-a943-11e9c613c9ef.png)

If you use this trimmer it will make the audio go faster or slower

In the Clip Bin you'll see the original and the Timeshifted version

![Screen Shot 2021-08-08 at 23 43 13](https://user-images.githubusercontent.com/51218415/128661193-bfc16b5b-237d-4884-8c92-b235bc5a3486.png)

# Editing Music Tracks

## Editing Library Music

Remember that you can you `Option + Click` to disable timeline info that's not useful

![Screen Shot 2021-08-09 at 0 03 34](https://user-images.githubusercontent.com/51218415/128662141-81fc7e37-d10f-483f-a2e6-9d3e1ea79ac6.png)

**How to measure Tempo**

Option 1 - Tap Tempo

If keyboard focus is off 

![Screen Shot 2021-08-09 at 0 08 34](https://user-images.githubusercontent.com/51218415/128662562-5d90ceb4-d0c2-4507-ba62-9bfe3b1722c4.png)

And the conductor is inactive (Transport Window)

![Screen Shot 2021-08-09 at 0 09 39](https://user-images.githubusercontent.com/51218415/128662606-b6885390-9158-41cf-a45a-4ad0699705a7.png)

You can actually control the tempo

Setup > Preferences > MIDI > Use MIDI to Tap Tempo

![Screen Shot 2021-08-09 at 0 13 44](https://user-images.githubusercontent.com/51218415/128662815-221e4bdc-acbe-4f15-82f1-d4b9c3d7e85a.png)

You can use letter T while the tempo is highlighted

![Screen Shot 2021-08-09 at 0 14 08](https://user-images.githubusercontent.com/51218415/128662830-941e5a08-7431-407d-b737-7f09a8203b8b.png)


## Using Identify Beat

Option 2 - Identify Beat

Enable Conductor

Select where the 2nd bar should be and use `Command + I`

And set the value to 2|1|000

![Screen Shot 2021-08-09 at 0 24 39](https://user-images.githubusercontent.com/51218415/128663424-c780f338-0758-452e-8171-6e5987f488d7.png)

Select where the 3th bar should be and use `Command + I`

And set the value to 3|1|000

Select where the 4th bar should be and use `Command + I`

And set the value to 4|1|000

## Slicing Music using the Grid

Option 3 - 

Enable Grid Mode

Select 1/8 in the Grid Value

![Screen Shot 2021-08-09 at 0 37 08](https://user-images.githubusercontent.com/51218415/128664058-603c3be3-6900-45c9-a2d9-382944480557.png)

Highlight the Tempo and scroll until you see it's aligned

![Screen Shot 2021-08-09 at 0 38 45](https://user-images.githubusercontent.com/51218415/128664164-0d2a322a-2d4c-4113-b309-4c6a76fc4a22.png)

Use Grid Mode to Select, `Command + D` to duplicate your selection

Select the duplicates using Grid Mode, move to Shuffle Mode and move them at the beginning

![Screen Shot 2021-08-09 at 0 47 29](https://user-images.githubusercontent.com/51218415/128664585-b30341cc-4232-4cb4-8fca-371b71e8268b.png)

Put Grid 1/4 Notes

Select All 

Edit > Separate Clip > On Grid

![Screen Shot 2021-08-09 at 0 52 30](https://user-images.githubusercontent.com/51218415/128664883-59ae40da-6898-4aec-8bdc-94d60bcf5ef1.png)

## Splices and Crossfades

Import audio files and put 123 as tempo

Go to Bar 9, and select it in Grid Mode, Command + E to cut it, and rename it as "Intro"

![Screen Shot 2021-08-29 at 0 29 18](https://user-images.githubusercontent.com/51218415/131239686-434c9bac-d6f3-4dcd-a667-2ef3ca9d2cce.png)

Move to Shuffle Mode, and drag it to the beginning, Command + D to add 3 more of those

Add crossfades between the repeated intros we added

![Screen Shot 2021-08-29 at 0 40 41](https://user-images.githubusercontent.com/51218415/131239924-b6aac66a-4099-44eb-b39c-bd05e45ce5dd.png)

You can also Fade Down after the intros:

![Screen Shot 2021-08-29 at 0 44 14](https://user-images.githubusercontent.com/51218415/131240030-0fa7b2f8-bd34-4c7e-b346-ece7098ffa25.png)

Switch to Grid Mode

Move the first audio track to Bar 5:

![Screen Shot 2021-08-29 at 0 46 36](https://user-images.githubusercontent.com/51218415/131240094-ee33459d-44ce-46aa-9411-2ee21b31b508.png)

Now mute the clip with Command + M:

![Screen Shot 2021-08-29 at 0 48 17](https://user-images.githubusercontent.com/51218415/131240132-0ac9af6a-5562-42ae-a5fd-0fe968edd5c6.png)

Select the Upper Track, change Tempo to 96

You can select Bar 5 and Option + Drag will duplicate the Bar

Fade In the Upper Track, Full One Bar Fade In

![Screen Shot 2021-08-29 at 0 53 36](https://user-images.githubusercontent.com/51218415/131240256-b7f422f5-4dec-4fdf-81be-e4840869453e.png)

And Full Bar Fade Out in the Lower Track

![Screen Shot 2021-08-29 at 0 57 15](https://user-images.githubusercontent.com/51218415/131240322-490a80d0-3012-4ab5-b04b-f9a78760197f.png)

![Screen Shot 2021-08-29 at 0 58 51](https://user-images.githubusercontent.com/51218415/131240355-164dd920-6993-4f46-b575-3bbf8116eb65.png)

Consolidate VS Bounce
- Consolidate will give us each track independently
- Bounce will give us the combination of the tracks

Select from End to Beginning what you want to bounce

File > Bounce > To Disk

Format: Interleaved
Check Offline


## Fade and Crossfade Options

Setup > Preferences > Editing > Fades

![Screen Shot 2021-08-29 at 1 25 45](https://user-images.githubusercontent.com/51218415/131240866-be860e01-5a53-43e7-9631-efabe3067dd0.png)

You can change the curve of the Fade-Out, Fade-In or CrossFades:

![Screen Shot 2021-08-29 at 1 30 06](https://user-images.githubusercontent.com/51218415/131240965-22c81943-894e-4790-bfed-f3f9835162bb.png)

![Screen Shot 2021-08-29 at 1 31 07](https://user-images.githubusercontent.com/51218415/131240986-6f62d540-6049-4bdf-9725-2f3e39b6c0b5.png)

Edit > Fades > Create

Even in a selection at the end, click Command + F to add a Fade Out

![Screen Shot 2021-08-29 at 1 33 56](https://user-images.githubusercontent.com/51218415/131241061-d8443334-9d2d-442c-976c-8c088edce604.png)

![Screen Shot 2021-08-29 at 1 34 55](https://user-images.githubusercontent.com/51218415/131241091-d1107d38-b037-4599-b235-d515a128633e.png)

Put the selector in the middle of a Clip

![Screen Shot 2021-08-29 at 1 36 44](https://user-images.githubusercontent.com/51218415/131241134-33feaae0-c143-40df-9505-465b2d2a2197.png)

Edit > Fades > Fade to Start

![Screen Shot 2021-08-29 at 1 37 44](https://user-images.githubusercontent.com/51218415/131241157-3d30d9b7-95e5-48e7-a9e9-b59ccd20a8c0.png)

Select other part

![Screen Shot 2021-08-29 at 1 38 31](https://user-images.githubusercontent.com/51218415/131241177-cccc3b69-b8e8-4937-af61-44cdcc4b7595.png)

Edit > Fades > Fade to End

![Screen Shot 2021-08-29 at 1 39 08](https://user-images.githubusercontent.com/51218415/131241197-b7d72d88-96b2-4eac-b9ad-2564ad79a3e8.png)


## Changing Tempo of Library Music Tracks

Let's move our 123 Tempo track to 100

Select the Track, put the Tempo to 100

![Screen Shot 2021-08-29 at 2 47 06](https://user-images.githubusercontent.com/51218415/131242861-19e6b5a8-66b9-4be3-aa24-a28324d60b4a.png)

Change to Time Compressor 

![Screen Shot 2021-08-29 at 2 39 01](https://user-images.githubusercontent.com/51218415/131242623-f17bb200-2890-40cb-a3e2-42e8390098ef.png)

Select the Track Again and move it to the calculated length

![Screen Shot 2021-08-29 at 2 47 54](https://user-images.githubusercontent.com/51218415/131242881-f9de7d21-0d60-4107-826a-e9fe54c2a0e7.png)

## Setting Triggers in Beat Detective

Event > Tempo Operations > Tempo Operations Window

Select a Drum or Ritmic Track

Event > Beat Detective > Analyze

![Screen Shot 2021-08-29 at 3 03 18](https://user-images.githubusercontent.com/51218415/131243289-e45de01c-e303-4296-8922-a67f3b35e0bc.png)

Adjust the Sensitivity to get the correct amount of bars

![Screen Shot 2021-08-29 at 3 10 40](https://user-images.githubusercontent.com/51218415/131243465-06bd66cc-2b77-4344-bdcf-3dbdf11002af.png)

You can manually adjust the bars in case of misdetection

![Screen Shot 2021-08-29 at 3 16 22](https://user-images.githubusercontent.com/51218415/131243602-0f76dc1d-905f-4f43-8ed9-246b0a112272.png)

## Conforming Trigger in Beat Detective

After detecting the Beats correctly

Select "Clip Separation" > Separate

![Screen Shot 2021-08-29 at 3 18 11](https://user-images.githubusercontent.com/51218415/131243656-4511f15f-152a-4cd0-9795-0e6f915f9d42.png)

Event > Tempo Operations > Tempo Operations Window

Change from 100 to 105 Tempo

Select "Clip Conform" > Conform

![Screen Shot 2021-08-29 at 3 25 45](https://user-images.githubusercontent.com/51218415/131243870-e3e80d01-d45e-4f4b-8ddd-d18c8f6b58ae.png)

You could also try to change it to 95 Tempo

Event > Tempo Operations > Tempo Operations Window

Change from 100 to 95 Tempo

Select "Clip Conform" > Conform

![Screen Shot 2021-08-29 at 3 30 13](https://user-images.githubusercontent.com/51218415/131243985-7787ecf8-f5b5-4857-a37d-18d4ac3735ec.png)

But we have some gaps between the clips

Select "Edit Smoothing" > Smooth

![Screen Shot 2021-08-29 at 3 32 29](https://user-images.githubusercontent.com/51218415/131244115-701248bb-4baf-4f88-b8df-ccb98d93df4f.png)

Let's try "Fill and Crossfade" 

![Screen Shot 2021-08-29 at 3 35 22](https://user-images.githubusercontent.com/51218415/131244206-5870c04e-1002-4ed6-9ee1-eb7f8bee62ec.png)


# Elastic Audio

## Elastic Audio for a Voice Track

These are the algorithms available for elastic audio
These 3 doesn't affect the pitch:
- Polyphonic - when you have more than one tone at the same time (chords)
- Rhythmic - when you don't have any pitches
- Monophonic - just one voice
These one will not only change the timing but also the speed 
- Varispeed

![Screen Shot 2021-08-29 at 12 29 22](https://user-images.githubusercontent.com/51218415/131259644-fc3aa7d6-a995-46d1-9a09-76caea3c501f.png)

If you select Monophonic and change from Waveform to Analysis, you should see something like this:

![Screen Shot 2021-08-29 at 12 34 40](https://user-images.githubusercontent.com/51218415/131259841-f322535d-48c2-41e1-91ed-e8e8eaa23a50.png)

There are more markers than we want, so we can adjust markers and Option + Click to remove a marker

![Screen Shot 2021-08-29 at 12 39 11](https://user-images.githubusercontent.com/51218415/131259993-0ea3ec54-c0b5-460b-b21d-c42cc7985163.png)

That's the Analysis, now we can move to Warp

Double-Click to add an Anchor Point

![Screen Shot 2021-08-29 at 12 41 28](https://user-images.githubusercontent.com/51218415/131260057-4d96d036-9007-43fe-9818-c9a0b557d026.png)

And now you can stretch:

![Screen Shot 2021-08-29 at 12 42 09](https://user-images.githubusercontent.com/51218415/131260079-5cddaa9c-2331-4746-8a42-494f169174b3.png)

We notice the Monophonic sounds robotic, so we can to Polyphonic and it sounds better

You'll know if Elastic Audio was applied to a Clip because of that icon:

![Screen Shot 2021-08-29 at 12 45 57](https://user-images.githubusercontent.com/51218415/131260223-0a0a8834-41fd-4e2f-8d32-4ec88eea2801.png)

![Screen Shot 2021-08-29 at 12 47 14](https://user-images.githubusercontent.com/51218415/131260254-24870d3e-4bca-4d4c-a487-4176ac27d378.png)

## Elastic Audio for Music

We want to keep the Kick Parts and move the Snare Parts

![Screen Shot 2021-08-29 at 12 52 00](https://user-images.githubusercontent.com/51218415/131260381-fc942c9b-1beb-4609-9945-c794cc85216d.png)

In this case we will use Rhythmic algorithm

Track > Create Click Track

You can Enable/Disable the Click with that icon in Transport Window

![Screen Shot 2021-08-29 at 12 54 26](https://user-images.githubusercontent.com/51218415/131260450-9910f287-8e32-4e37-9fad-4333983b35dc.png)

Now we switch to Analysis

![Screen Shot 2021-08-29 at 12 56 06](https://user-images.githubusercontent.com/51218415/131260504-272aeb1d-d991-426b-afe4-c71001cf8a90.png)

We move to Warp and start Anchoring the good parts

It's easier if we move to Grid Mode and we are sure that the grid is a 1/4 note

![Screen Shot 2021-08-29 at 12 59 41](https://user-images.githubusercontent.com/51218415/131260615-070d9b6d-2421-48b6-aacc-b6e5ffceb425.png)

![Screen Shot 2021-08-29 at 13 00 47](https://user-images.githubusercontent.com/51218415/131260661-797d3d53-5a24-4827-99da-6430ee6c12f7.png)

## Pitch Adjustments using Elastic Audio

Clip > Elastic Properties

![Screen Shot 2021-08-29 at 13 05 52](https://user-images.githubusercontent.com/51218415/131260798-20459be8-3477-41ae-9d88-44274da5c443.png)

Select the Clip using Polyphonic and you would be able to change Pitch Shift Positive/Negative

![Screen Shot 2021-08-29 at 13 08 06](https://user-images.githubusercontent.com/51218415/131260884-c8adb48d-ef20-4268-9fb5-4e81f0043ad5.png)

![Screen Shot 2021-08-29 at 13 09 48](https://user-images.githubusercontent.com/51218415/131260931-8c5f8b4f-4044-4b48-93c7-09f049dfadde.png)

# MIDI in Pro Tools - LATER
## Connecting a MIDI Keyboard
## Editing MIDI Notes
## XPand!2 - Virtual Instrument Library
## Recording and Editing MIDI
## MIDI Merge and Wait for Note
## Play it Slow, Hear it Fast
## MIDI Step Load
## Performance Transpositions using Xpand!2
## Virtual Instruments
## MIDI Import and Export

# Tracking Instruments
## Adding Rhythm Guitar
## Arranging using the Timeline
## Guitar Amp Simulators
## Loop Record and Playlists
## Comping a Playlist
## Quick Punch
## Dynamic Punch
## Half Speed Recording

# Sound Design - LATER
## Sound Design
## Dialog Phone EFX
## Creating New SFX with Plug-Ins
## Using Plugins to Process SFX
## Timing Music to SFX
## Tuning SFX to Music
## Exploring the Structure Interface
## Putting Structure to Work

# Working with Video - LATER
## Importing Movie
## Spotting the Movie
## Setting the Tempo of the Music
## Using Spot Mode for Precise Placement
## Building an Alternative Version in the Timeline
## Bouncing the Movie

# Mixing and Automation
## The Philosophy of Mixing
## EQ and Volume
## Busses, Sends, Auxes and Inserts
## Panning, Marker Locations and the Universe
## Automating Plugin Parameters
## Compression and Customing Templates
## Printing Effects and Stems
## Archiving your Session






