---
layout: post
title: Aden and Todd's Makey Makey Project
description: Coding Post
categories: coding response
---
# Aden & Todd’s Makey Makey Project
### Goals:
In creating our Makey Makey project, we had a number of goals. Our project comprised two major components:
- Compression:
We wanted to demonstrate dynamic range audio compression both visually and aurally. Dynamic range audio compression, as its name suggests, limits the dynamic range of an audio signal. It is typically used in the service of verisimilitude. By reducing the level of loud sounds while leaving quieter sounds unaffected, the compressor enforces a parity or consistency in the signal, making the sound range more consistent.
 
Rather than compress audio files to increase verisimilitude, our aim instead was to *decrease* verisimilitude—to “break” the sound. We were inspired by Alvin Lucier’s *I Am Sitting in a Room*, in which the artist recorded himself speaking and then played the recording in a room, recording it again, and then repeating the procedure. After performing this playback and record procedure many times, Lucier’s voice becomes unintelligible and all that’s audible is the ambient sounds of the room itself. Like Lucier’s experiment with the limits of sound and meaning, we were interested in how far an audio file could be compressed before all that was intelligible was the sound of the code that comprised the file. We wanted to turn the sound inside out, so to speak.
 
For the compression aspect of our project, we wanted the user to be able to see and hear the compression as it was happening and to think about the ways sound can be manipulated without the hearer’s knowledge and the ways in which communication is mediated by technology.
 
- Makey Makey

For the Makey Makey component of our project, we were interested in showing how a user whose physical capabilities were somehow limited or who experienced discomfort with the normal operation of a computer mouse could still participate in the compression aspect of our project. Our goal was to employ the Makey Makey in a way that enabled the user to operate the computer, toggling between windows and starting and stopping audio playback without dependence on the mouse.
 
We also wanted to show how the use of Makey Makey could translate to other programs, controlling the mouse for various other software programs. For instance, if a user suffered from carpal tunnel syndrome and normal mouse operation caused them pain, they could instead use Makey Makey and simply press or tap an object to operate the mouse.
 
### Specifications:
Materials:
- Computer
- Makey Makey
- Play-Doh
- 4 Bananas
- Aluminum foil (optional)
 
1. Set up a control file and a file to compress.
  1. Download and install an audio editing software program, such as WavePad or Audacity.
  2. Import a sound file to the editing software to serve as the “control” file.
  3. Import a copy of the sound file to another window of the editing software to use for compression.
  4. Find the software’s compressor or limiter function, commonly located in an “Effects” or “Levels” drop-down menu.
  5. Adjust the compression ratio, compression hardness, floor, gate, amplitude, and attack to your desired level of compression. Most audio editors include a “Preview” option so that you can hear the result of the compression before you apply it to your file.
2. Set up the Makey Makey.
  1. Use Arduino to reprogram your Makey Makey so that the “click” function on the Makey Makey board operates the “alt-tab” keyboard shortcut. (learn.sparkfun.com/tutorials/makey-makey-advanced-guide) 
2. Form and arrange two discs of Play-Doh next to your computer keyboard.   
3. Connect an alligator cable between the “SPACE” input on the Makey Makey and one Play-Doh disc.
  4. Connect an alligator cable between the “CLICK” input on the Makey Makey and the other Play-Doh disc.
  5. Arrange the bananas vertically next to the Play-Doh discs.
  6. Connect wires between the arrow inputs on the Makey Makey and the bananas.
  7. Connect the Makey Makey’s USB cord to the Makey Makey and your computer.
  8. Connect an alligator cable to the “EARTH” input on the Makey Makey and yourself. (If you have a metal watchband or bracelet, connect the alligator clip to it. If not, you can fashion one out of aluminum foil.)
  9. Touch the bananas to navigate the cursor around your computer’s monitor.
  10. Tap the Play-Doh discs to toggle between windows and to start and stop audio playback.
 
 
### Rationale:

Our starting point for this project developed from the notion that lossy compression has become ubiquitous with the rise of storing digital media. In The *Language of New Media*, Lev Manovich writes, “the software and hardware used to acquire, store, manipulate, and transmit digital images rely uniformly on *lossy compression* - the technique of making image files smaller by deleting some information” (54). We wanted to show in our project that with digital compression, some data is always lost in the compression process. As Manovich notes, lossy compression “involves a compromise between image quality and file size- the smaller the size of a compressed file, the more visible the visual artifacts introduced in deleting information become” (54). Even before knowing how we would incorporate the Makey Makey, we wanted to perform digital compression to highlight how the technique negotiates the compromise between quality and file size that Manovich mentions. 

One of our aesthetic motivations was to replicate Lucas Hilderbrand’s notion of ‘bootleg aesthetics’, which was mentioned in Jonathan Sterne’s “Compression: A Loose History” and Nicole Starosielski’s “Fixed Flow: Undersea Cables as Media Infrastructure”.  According to Sterne, “Lucas Hilderbrand coins the phrase ‘bootleg aesthetics’ to describe the grainy images of analog video that gave rise to fair-use law and presaged many file-sharing practices in the United States” (34). Starosielski describes ‘bootleg aesthetics’ further and writes, “the copying and recopying of bootleg VHS tapes, which led to their deterioration over time, marked them with a distortion and fuzziness” (61). By taking high-quality, uncompressed audio files and compressing them, we intended to imbue our speech and music recordings with bootleg aesthetics by making our audio tinnier, more degraded, and distorted. This marking of the audio files via compression can be considered a trace left on the compressed files. We realized that most, if not all, forms of compression, whether related to audio, video, or language, leave an aesthetic trace- noticeable or not. A compressed audio file sounds differently than an uncompressed one, a compressed video file looks and sounds differently than its original version, a message is composed of different letters and words when written in code, and so on. 

While we did not compress our audio files to the point of complete unintelligibility, we compressed them enough that the distortion was discernible enough to our ears. When synopsizing Katherine Hayles’ writing on codebooks, Sterne emphasizes that in Hayles’ codebook example “communication is meant to be efficacious rather than verisimilar” (45). We would argue that this “ ‘good enough’ dimension of communication” (45) is relevant to how often compression of audio, video, or language just has to be passable enough to understand. Just as messages derived from code only have to be clear enough to comprehend, digitally compressed audio files lose sound quality but usually retain enough quality to still be intelligible. By playing our uncompressed audio recordings and then our compressed audio files in our presentation, we tried to show that everyday digital compression can be noticeable to the ear when comparing and contrasting between uncompressed and compressed files though this often doesn’t matter when the listener just wants to hear a recording and be able to get the gist of a song or speech recording. 

We attempted to think beyond digital compression, and expanded our humanistic and materiality rationales to acknowledge the compression of labor. The digital audio software we used, Audacity, is an application that heavily relies on using the computer mouse. As a device that reduces the labor of coding or typing, the mouse can be thought of as a tool that compresses work and movement. Computer keyboard and mouse use, especially the kind that involves heavy dragging with the mouse, can put physical strain on the body of the person using these tools. Repetitive stress on the hands and wrists can lead to carpal tunnel syndrome and other physical injuries. This is what Matthew Kirschenbaum describes when writing about the trace of labor being written on the human body. In Mechanisms: *New Media and the Forensic Imagination*, Kirschenbaum writes that there are “material circumstances that leave material (read: forensic) traces- in corporate archives, on whiteboards and legal pads, in countless iterations of alpha versions and beta versions and patches and upgrades, in focus groups and user communities, in expense accounts, in licensing agreements, in stock options and IPOs, in carpal tunnel braces” (15) and so on. We think that using the Makey Makey instead of the computer mouse might limit the physical strain that comes with repeatedly clicking on and dragging with the mouse in a mouse-intensive application such as Audacity.

Another mouse-dependent application that came to mind was GarageBand, which users utilize to create music and speech recordings through built-in instrument samples. With the Makey Makey connected to the laptop instead of a mouse, a user would hopefully put less stress on their body by using the Makey Makey to drag and drop instrument loops on the GarageBand interface. We thought about musicians with physical limitations such as carpal tunnel or multiple sclerosis who could use the Makey Makey to create music through GarageBand and professionally compress the recordings with Audacity instead of struggling to play physical instruments or adding physical damage by primarily using a computer keyboard and mouse. By connecting the Makey Makey to our laptop and using bananas and Play-Doh in place of the keyboard and mouse, we hoped to make working with Audacity and other mouse-centered music applications such as GarageBand easier. We believe that we succeeded in showing that the Makey Makey can make working in certain mouse-heavy applications easier for users with certain physical injuries, illnesses, and disabilities. 

We learned to expect technical difficulties even when working outside of coding. Our friend Rudy, the music programmer at the Detroit Institute of Arts, originally showed us how to compress audio files using the software Digital Performer. Rudy’s older version of Digital Performer included a compression feature that showed the signal ranges for the back-range, mid-range, and front-range of an audio recording on three separate graphs. We thought that these signal graphs would be very helpful to visualize in our presentation how signals are altered using compression. Unfortunately, the newest version of Digital Performer that we downloaded did not have this compression feature. This is why we used Audacity for our presentation, and this software also presented obstacles. Audacity’s free version did not come with any compression features so Todd paid for the compression add-ons. Once we had ability to compress audio files with Audacity, we also had to mess around with the software for hours to learn through trial and error how its compression process worked. We were also pleased to learn that the Makey Makey’s code can be written and altered to accommodate keys not included on the Makey Makey circuit board. Originally, we wanted to toggle between six different Audacity windows using Alt+Tab, but Alt was missing from the Makey Makey board. If we continue with this project, we will be able to access the Alt+Tab keyboard shortcut on the Makey Makey by rewriting the code using the Arduino Add-On software. 

