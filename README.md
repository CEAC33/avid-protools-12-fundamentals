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

Create a Project from "Songwriter - Guitarist" Template

![Screen Shot 2021-08-29 at 13 36 25](https://user-images.githubusercontent.com/51218415/131261592-6e984870-8500-42f4-b60a-89d1fa32aac7.png)

Open Mix Window, select first Track

![Screen Shot 2021-08-29 at 13 37 48](https://user-images.githubusercontent.com/51218415/131261637-c928c896-d34d-4f28-97fb-f48eee97a00d.png)

Then press Shift and select last Track; that will select all the tracks

![Screen Shot 2021-08-29 at 13 38 50](https://user-images.githubusercontent.com/51218415/131261661-f1bc7a8d-1bc2-4f1f-9c62-4da4eb75f099.png)

Command and click headphone to deselect it

![Screen Shot 2021-08-29 at 13 40 20](https://user-images.githubusercontent.com/51218415/131261713-3d2a3353-8c8b-449c-a8d5-bd7e7e57c745.png)

Press Shift + Control + Option

Select an output and that will apply it to all the Tracks

![Screen Shot 2021-08-29 at 13 42 58](https://user-images.githubusercontent.com/51218415/131261790-332fb362-5899-4175-a7fe-f7d49a016e1e.png)

Now let's record a guitar:

![Screen Shot 2021-08-29 at 13 47 48](https://user-images.githubusercontent.com/51218415/131261966-1cd988e4-1aeb-4e54-8178-232536f3b214.png)

## Arranging using the Timeline

Let's say we want an intro, so let's move the drums and guitar to Bar 5:

![Screen Shot 2021-08-29 at 13 49 54](https://user-images.githubusercontent.com/51218415/131262016-857da265-3da6-4d7c-b98f-004c3e8e8146.png)

Use the Loop Trimmer, that shows automatically if you have a loop in the timeline

![Screen Shot 2021-08-29 at 13 52 24](https://user-images.githubusercontent.com/51218415/131262089-5f72e228-6a07-49e2-8540-13e9c2872455.png)

You can open by Double-Clicking the Drum Clip, select the notes you want to Mute and press Command + M

![Screen Shot 2021-08-29 at 13 53 02](https://user-images.githubusercontent.com/51218415/131262105-2d0f3f71-8a77-43f6-a2f8-d246b7ac2ce6.png)

Count Off gives you two Bars before recording so you can prepare:

![Screen Shot 2021-08-29 at 13 55 10](https://user-images.githubusercontent.com/51218415/131262162-6918ecb9-cfd4-4bc9-8b0d-b869fd6e1c22.png)

You can change that in Setup > Click/Countoff

![Screen Shot 2021-08-29 at 13 57 47](https://user-images.githubusercontent.com/51218415/131262227-b0cb8c63-d0bb-484f-9a30-383ce1edc399.png)

Now let's record the intro for the Guitar:

![Screen Shot 2021-08-29 at 13 59 09](https://user-images.githubusercontent.com/51218415/131262292-bd02b7db-76e2-4a71-89a8-f20257725628.png)

And add a crossfade if necessary

## Guitar Amp Simulators

Go to Mix Windows and to the Guitar Effects

Eleven Lite:

![Screen Shot 2021-08-29 at 14 03 13](https://user-images.githubusercontent.com/51218415/131262356-c0d11766-228d-4db3-b160-e7365c0e0860.png)

PSA-1:

![Screen Shot 2021-08-29 at 14 06 15](https://user-images.githubusercontent.com/51218415/131262413-0ee1e4e6-d9e5-4ca9-aedc-f00438ea2f9e.png)

## Loop Record and Playlists

Select 4 Bars that you want to record:

![Screen Shot 2021-08-29 at 14 13 09](https://user-images.githubusercontent.com/51218415/131262635-bf7763fd-6bfd-4c3a-9df8-3948022f9bf6.png)

Options > Loop Record

You'll see that now Playback and Record have the Loop icon:

![Screen Shot 2021-08-29 at 14 14 49](https://user-images.githubusercontent.com/51218415/131262666-0700e445-6aee-44d8-8cd2-63cd8cd7821c.png)

Click in the inverted triangle and you'll see all the recordings:

![Screen Shot 2021-08-29 at 14 17 31](https://user-images.githubusercontent.com/51218415/131262747-3014c594-56b8-49c8-8f57-8292d5c5473a.png)


## Comping a Playlist

You can also see the waveform of all the recordings in the Playlist:

![Screen Shot 2021-08-29 at 14 19 27](https://user-images.githubusercontent.com/51218415/131262799-c6f18051-3362-482d-8beb-d8e8e9c91881.png)

![Screen Shot 2021-08-29 at 14 20 27](https://user-images.githubusercontent.com/51218415/131262820-be3e132a-fbcd-4f24-851b-0046e61f1873.png)

Select Grid Mode and 1/4 notes

You can select a part and elevate it:

![Screen Shot 2021-08-29 at 14 21 43](https://user-images.githubusercontent.com/51218415/131262847-11d9e674-df07-479e-be32-23f58482379d.png)

![Screen Shot 2021-08-29 at 14 22 21](https://user-images.githubusercontent.com/51218415/131262860-7a1c33b4-f7d5-4e7f-a218-6bbe241f926e.png)

## Quick Punch

Check these options:

![Screen Shot 2021-08-29 at 14 28 22](https://user-images.githubusercontent.com/51218415/131263006-12be5af9-ff47-42b7-b9ec-8a0b3c5b0622.png)

Disable Loop Recording

You can set an Start and End points for recording: 

![Screen Shot 2021-08-29 at 14 29 24](https://user-images.githubusercontent.com/51218415/131263038-fbd5486c-7012-49cc-939f-6c21537dc45b.png)

![Screen Shot 2021-08-29 at 14 30 20](https://user-images.githubusercontent.com/51218415/131263065-6126e80c-b115-4526-bc99-4b8381604228.png)

Options > Quick Punch

Now you can use F12 to stop recording

This will for example give a new bar 9 but keep original bar 10

![Screen Shot 2021-08-29 at 14 31 25](https://user-images.githubusercontent.com/51218415/131263082-009ab6f1-a9c9-4d8a-93db-dc41f5d6327f.png)

Or record some part, keep the original part and recording a new part after

![Screen Shot 2021-08-29 at 14 33 29](https://user-images.githubusercontent.com/51218415/131263126-d90aff9e-8b1c-44cc-be30-aa8b1ce9e2b5.png)

## Dynamic Transport

Options > Dynamic Transport

You can set Bar 6 as reference and jump to Bar 10 to Record:

![Screen Shot 2021-08-29 at 14 53 02](https://user-images.githubusercontent.com/51218415/131263609-d8882e9f-1677-4980-9378-992f29224a63.png)

And you can combine it with Quick Punch

## Half Speed Recording

Shift + Command + Space = Half Speed Recording

You'll have a record with the speed doubled and a higher pitch

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

Create a Session with "24+EQ+Dyn+FX Returns" Template (Record+Mix Category)

The beauty of mix is in how the sounds blend and compliment one another and not how a single instrument sound by itself

## EQ and Volume

**Volume - OPTION 1**

Anytime you have more than 1 Track happenning at the same time you want a Master Fader

The idea is to move individual faders so that you can leave the Master Fader at 0, and have the peak from -3 to 0.3

RECOMMENDATION: Line the tracks up in their orden of importance  

If your tracks were recorded right your faders are going to be loud, a little softer, a little softer ...

**EQ - OPTION 2**

Another option is to carve out a space in the frequency spectrum that lets that part stand out

Let's say you want the guitar to have more presence in the middle frequencies; rather than boost the middle frequencies of the guitar try reducing those same frequencies in the bass

If two sounds are fighting one another, try EQ

You can boost the good stuff or cut the bad stuff

![Screen Shot 2021-08-29 at 19 07 10](https://user-images.githubusercontent.com/51218415/131269875-bfc7ae6a-8b93-4e87-90b7-4e47ddcf403b.png)

Thinking about the texture of each element:
- Does it need Reverb?
- Does it need Delay?
- Does it need Compression?
- Is the Volume perfect from End to End?

## Busses, Sends, Auxes and Inserts

These are some effects that are common for a Pop Song:

![Screen Shot 2021-08-29 at 19 12 34](https://user-images.githubusercontent.com/51218415/131270044-d670e8e8-b485-4e51-9679-390f03c06667.png)

- Verb - AIR Reverb
- Slap - ModDelay 3, Lo-Fi (Harmonic Section), EQ3 1-Band
- StereoDel1
- ChurchVerb
- Master 1

**SLAP**

ModDelay 3

![Screen Shot 2021-08-29 at 19 16 43](https://user-images.githubusercontent.com/51218415/131270161-692b503d-cee3-4d0a-bbcd-cdec22785f31.png)

Lo-Fi (Harmonic Section)

EQ3 1-Band - Shelf

![Screen Shot 2021-08-29 at 19 17 37](https://user-images.githubusercontent.com/51218415/131270192-de9fa07d-4d56-4a1a-a5ea-0d96f9593c11.png)

![Screen Shot 2021-08-29 at 19 19 49](https://user-images.githubusercontent.com/51218415/131270259-899e58cf-e115-4415-af0a-08247f0631f4.png)

You can Rename Buses: Setup > IO

![Screen Shot 2021-08-29 at 19 21 23](https://user-images.githubusercontent.com/51218415/131270315-8be6b564-43d2-48ce-ac6b-a32fa6559c59.png)

You can Bypass Inserts and Mute Sends in Track Menu

![Screen Shot 2021-08-29 at 19 23 38](https://user-images.githubusercontent.com/51218415/131270395-ce316632-afdc-41a0-90db-a65353cb6c1b.png)

![Screen Shot 2021-08-29 at 19 23 57](https://user-images.githubusercontent.com/51218415/131270406-0f8a13e1-0a29-4e83-b6af-aef74708b7c1.png)

If the tile is blue it means is bypassed

![Screen Shot 2021-08-29 at 19 24 40](https://user-images.githubusercontent.com/51218415/131270432-4961944e-0851-46d1-8a3e-0e4b2d22ade2.png)

If it's red it means the Send Level has been exceeded , there's been digital clipping

Transport Windows > Fade-in (it saves you from having an instant full volume when you hit play)

## Panning, Marker Locations and the Universe

**Panning**

It's important to equilibrate the panning and not just have it at 100 left and right in Stereo, and at the center if it's Mono

![Screen Shot 2021-08-29 at 19 29 28](https://user-images.githubusercontent.com/51218415/131270609-fa800e86-2239-49b2-b098-d658f8c68715.png)

**Markers**

Window > Memory Locations

![Screen Shot 2021-08-29 at 19 31 39](https://user-images.githubusercontent.com/51218415/131270673-ce3c9744-aa5c-4d66-af11-8c6ad58d18d6.png)

![Screen Shot 2021-08-29 at 19 32 40](https://user-images.githubusercontent.com/51218415/131270708-515a81cc-0f3a-4713-ba13-46a36559a5ed.png)

## Automating Volume, Pan and Send Levels

### VOLUME Automation

#### Auto Write

1.- Go from "auto read" to "auto write"

![Screen Shot 2021-09-25 at 23 40 32](https://user-images.githubusercontent.com/51218415/134793934-1c2dcc4a-c2a1-4099-8bc6-46fe76f1e923.png)

2.- Hit space bar to start playing

3.- Make a volume move

4.- The button changes to "auto latch" 

(if it's not switching to latch):
Setup > Preferences > Mixing > Automation > After Write Pass, Switch To: Latch

![Screen Shot 2021-09-25 at 23 44 11](https://user-images.githubusercontent.com/51218415/134793982-3505c838-666d-4952-8841-cafe1a50a29a.png)

latch - in case you want the fader where you left it

touch - in case you want the fader where it was originally

There's the volume move:

![Screen Shot 2021-09-25 at 23 57 32](https://user-images.githubusercontent.com/51218415/134794269-6a9b257e-6225-43e3-9b4e-e4d60cbce08c.png)


### PANNING Automation

Jump to Edit Window

Go "auto read"

Add another line with the panning

![Screen Shot 2021-09-26 at 0 06 02](https://user-images.githubusercontent.com/51218415/134794459-6aa3506a-c4a5-4f63-a952-b03a83e75b02.png)

**PENCIL Automation**

Use the Pencil Tool

![Screen Shot 2021-09-26 at 0 06 58](https://user-images.githubusercontent.com/51218415/134794479-2c79de59-c949-4f06-bcf1-04dfbce766ae.png)

Select Line

![Screen Shot 2021-09-26 at 0 07 28](https://user-images.githubusercontent.com/51218415/134794496-ca3dcb1c-4ea4-4609-9246-ef92c9cca608.png)

Start writing some lines in the pannning

![Screen Shot 2021-09-26 at 0 08 38](https://user-images.githubusercontent.com/51218415/134794529-479704d3-bb6c-42ad-aa88-802a38dd350b.png)

You can reduce the points in the automations by:
Edit > Thin Automation

Select the Automation

![Screen Shot 2021-09-26 at 0 10 37](https://user-images.githubusercontent.com/51218415/134794567-f102d65a-254f-4649-aafd-e4521d27c6fc.png)

Edit > Thin Automation

**FADER Automation**

Change to "auto write"

![Screen Shot 2021-09-26 at 0 14 02](https://user-images.githubusercontent.com/51218415/134794629-0345affa-1ff5-488c-8fbe-134104453bad.png)

Play and start writing the panning

![Screen Shot 2021-09-26 at 0 14 33](https://user-images.githubusercontent.com/51218415/134794644-b334c08b-0eb7-4ed5-a243-2fc5645d7c00.png)

Automating the Panning will erase the automation of the Volume
So if you want to automate particular items we can enable and disable those

Jump to the Mix Window

If you want to record automation during the recording process:

Setup > Preferences > Operation > Record > Enable Automation in Record

![Screen Shot 2021-09-26 at 2 06 00](https://user-images.githubusercontent.com/51218415/134797482-83c0c9b2-dbb8-4a9f-ab02-7e3af21191b2.png) 

## Automating Plugin Parameters

Select "auto read"

In the Mix Window add a "D-Verb" plugin:

![Screen Shot 2021-09-26 at 2 13 20](https://user-images.githubusercontent.com/51218415/134797695-617478d8-3007-496e-816f-41716c5fe7a6.png)

![Screen Shot 2021-09-26 at 2 14 05](https://user-images.githubusercontent.com/51218415/134797713-67deae1a-f563-4c19-91d1-ef492d682633.png)

Click in th auto icon:

![Screen Shot 2021-09-26 at 2 14 43](https://user-images.githubusercontent.com/51218415/134797729-ea76f717-5b9c-43c0-89fd-0812b3a7ae75.png)

They are in the left:

![Screen Shot 2021-09-26 at 2 15 17](https://user-images.githubusercontent.com/51218415/134797748-1aa18bdb-2088-41e2-8fb6-61f42cd66f2c.png)

Select the ones you want to automate, and move them to the right:

![Screen Shot 2021-09-26 at 2 16 02](https://user-images.githubusercontent.com/51218415/134797783-4d073719-5107-4b97-ae7d-0c89b9cbc34d.png)

After that they'll be colored green:

![Screen Shot 2021-09-26 at 2 16 35](https://user-images.githubusercontent.com/51218415/134797798-cf34957d-7d70-4f5b-bd4a-3ef96ef7c1a3.png)

If you change to "auto write", they'll be colored red:

![Screen Shot 2021-09-26 at 2 18 36](https://user-images.githubusercontent.com/51218415/134797866-c65aecd0-9a42-4206-9a19-2afff8ea996e.png)

Be careful if you change the type of reverb in the middle of mix or even in tracking

You'll likely hear a click as it changes the algorithm

These are automatable, but you might want to just change it in a muted spot 

For example if you automate a change in the Decay of the Reverb

You can see the automation in LongVerb > Decay

![Screen Shot 2021-09-26 at 2 25 40](https://user-images.githubusercontent.com/51218415/134798062-fecd999e-077a-420d-af92-070cf02fe4f5.png)

## Compression and Customing Templates

**Simple Limiter**

20:1 is pretty agressive

![Screen Shot 2021-09-26 at 17 09 09](https://user-images.githubusercontent.com/51218415/134825839-dccf5bf8-e445-4c45-9126-78d7f18713db.png)

**Gentle Limiting **

100:1 

![Screen Shot 2021-09-26 at 17 11 04](https://user-images.githubusercontent.com/51218415/134825869-15061ae0-1eb0-4fb2-abba-587cf124ac19.png)

**Hard Limiting**

100:1

![Screen Shot 2021-09-26 at 17 12 31](https://user-images.githubusercontent.com/51218415/134825898-1fab43e2-1540-4031-b09a-bc3df35fb320.png)

**Fatten**

20:1

![Screen Shot 2021-09-26 at 17 13 13](https://user-images.githubusercontent.com/51218415/134825920-7d348d93-f7aa-4e75-b835-aa9429c696e0.png)

**Pump**

10:1

![Screen Shot 2021-09-26 at 17 13 57](https://user-images.githubusercontent.com/51218415/134825936-e26da6d5-acfa-4bb0-b5c9-32c9bd57ea97.png)

We've sort of flattened this whole thing out so that: 
- the very soft stuff is now being amplified a lot 
- the very loud stuff isn't presumably loud at all

You have several settings for how aggresive you want to be with this:

![Screen Shot 2021-09-26 at 21 28 01](https://user-images.githubusercontent.com/51218415/134836908-bc1a04c5-97e1-4e4a-b764-9cdf4351ca2b.png)

Control + Click: Mute Inserts

The compression depends a lot on whether you plan to master or not

If you're mixing and this is the final output then some compression is advisable

If you're going to a Mastering Engineer and you use up all the headroom, you're locking your mastering engineers ability to do his job

If your mastering leave about 6dB of headroom for your master, yoiu shouldn't compress a lot. Because the Mastering Compressor probably has a better multichannel commpressor than you do, probably has better monitors than you do. And if you compress a lot you're killing the dynamics and that's part of a mastering engineers job

You can save a session as a Template:

File > Save As Template


## Printing Effects and Stems

**Issue 1**

Let's say the master has a plugin which you don't have:

![Screen Shot 2021-09-26 at 21 47 44](https://user-images.githubusercontent.com/51218415/134838370-d9842221-3ab0-43e1-90e4-30c4fdbbe7d0.png)

We see this a lot; people use a plugin that they own and then they send the session to somebody who doesn't have that plugin

And this is what happens, the plugin gets italicised

**Issue 2**

Sometimes you'll be tying up a lot of processing power of your computer by sending a bunch of tracks to a reverb or a delay or some other processing unit. and you'll be doing that every time you hit play

**Workaround**

The tip is to print the effects as an audio file

In the old days we would solo the lead vocal, solo the effects and then bounce whatever was soloed and then import it

That system works fine but as ProTools 11 we have the ability to route this bus to a track:

![Screen Shot 2021-09-26 at 21 56 27](https://user-images.githubusercontent.com/51218415/134839047-89d360ab-ff1b-439e-8105-f4e6fe2d47ac.png)

Or make a new track for it:

![Screen Shot 2021-09-26 at 21 57 02](https://user-images.githubusercontent.com/51218415/134839082-3e6353a3-d2c7-45eb-9381-8e55fa21fd9c.png)

![Screen Shot 2021-09-26 at 21 58 12](https://user-images.githubusercontent.com/51218415/134839179-c825f55c-979e-4a63-86c7-f6c3874b5298.png)

The new track now is there, but we need to route it

![Screen Shot 2021-09-26 at 21 59 44](https://user-images.githubusercontent.com/51218415/134839282-d89921e8-ff6e-425b-b551-a86453ec65ca.png)

We can use the same system when a client asks you for **stems**

Stems are typically all the vocals from the front of the song to the back of the song, all the rhythm might be the drum part from the front of the song to the back of the song

## Archiving your Session

Let's say that we perfected our mix, got the levels right, got the textures right. Everything sounds great. The client is happy and it's time to archive this session and move to the next project

Go to Clips > Select > Unused

![Screen Shot 2021-09-26 at 22 11 06](https://user-images.githubusercontent.com/51218415/134840057-2b55bfbf-7782-4176-a25d-80962f5b222a.png)

File > Save Copy In ...

Items to Copy > Check "Audio Files" and "Root Plugin Settings Folder"

![Screen Shot 2021-09-26 at 22 12 56](https://user-images.githubusercontent.com/51218415/134840187-70b6b2af-dd70-4928-aea9-64a6fb46a31d.png)

Use the word "Archive" in the title somewhere so it's clear when you see it that was the final archive of this session

Then go to Clips and clear the Unused Clips

![Screen Shot 2021-09-26 at 22 15 50](https://user-images.githubusercontent.com/51218415/134840411-4e341240-ea24-4eef-ab92-b622322adb5c.png)

Remove - just remove the clips form the session, but keep the files in the hardrive
Delete - it's the efficient way to also remove the files from the hardrive

![Screen Shot 2021-09-26 at 22 17 28](https://user-images.githubusercontent.com/51218415/134840537-e961e878-047d-42c5-b960-8043ef2f95e0.png)

Some Pages to find Plugins:
- Avid - https://www.avid.com/avid-plugins-by-category
- Waves - https://www.waves.com/plugins
- iZotope - https://www.izotope.com/
- McDSP - https://www.mcdsp.com/plugin-index/

# Find an Avid Learning Partner

https://www.avid.com/education/find-an-avid-learning-partner

Online (Berklee):
- Level 1
  - Pro Tools 101 - 1,250 USD - https://online.berklee.edu/courses/pro-tools-101
- Level 2
  - Pro Tools 110 - 1,250 USD - https://online.berklee.edu/courses/pro-tools-110
- Level 3
  - Mixing and Mastering with Pro Tools - 1,250 USD - https://online.berklee.edu/courses/mixing-and-mastering-with-pro-tools
  - Remixing - 1,250 USD - https://online.berklee.edu/courses/remixing
  - Audio Post Production for Film and TV - 1,250 USD - https://online.berklee.edu/courses/audio-post-production-for-film-and-tv
- Level 4
  - Advanced Mixing and Mastering with Pro Tools - 1,250 USD - https://online.berklee.edu/courses/advanced-mixing-and-mastering-with-pro-tools
