## Welcome to the Synth Programming Language Website!

You can use find the link to GitHub Repository [here](https://github.com/GabrielGonzalez30/Synth). This site is meant to explain the documentation of what our language does.


### Synth: Interactive Audio Processing Language

Built by:
 - Gabriel Gonzalez
 - Pedro Santiago
 - José Túa
 - Jaime Torrens

### Language Features

- Able to create, modify and store audio files (mp3, wav, etc) via sound synthesis and sound recording (called streams), as well as realtime playback of streams.
- Able to create & modify effects, add effects to different streams.
- Able to interface with MIDI controllers, as well as create a keyboard, soundboards, etc., using a computer keyboard


### Code Samples
```markdown
# Initializing Streams
-_InitStream s1 as Synthesizer_-
Intializes a stream of a Synthesizer instrument as any symbol, s1 in this case.

-_InitStream s183 as AudioStream_-
Intializes a stream of an Audiostream as any symbol, s1 in this case.

# Adding Waves to Stream
The following line will only happen if a Stream has been initialized. Otherwise, this cannot occur.
1. -_As s1 setWave(Sine,600)_-
In the s1 stream, creates a Sine wave with a frequency of 600.

2. -_As s1 setWave(Sine)_-
In the s1 stream, creates a Sine wave with a default frequency of 200.

3. -_As s183 setWave(Saw)_-
In the s183 stream, creates a Saw wave with a default frequency of 200.

4. -_As s1 setWave(Square,250)_-
In the s1 stream, creates a Square wave with a frequency of 250.

# Changing Frequencies of Waves
1. -_As s1 setFrequency(100)_-
In the s1 stream, frequencies are changed to 100 as parameters imply.

# Playing Streams

#Pausing Streams



Syntax highlighted code block

# Header 1
## Header 2
### Header 3

- Bulleted
- List

1. Numbered
2. List

**Bold** and _Italic_ and `Code` text

[Link](url) and ![Image](src)
```

### Requirements
***WIP***

### Built With/Tools
- Implementation Languages: C++ (gcc for Unix, Visual C++ for Windows)
- Git and GitHub for source control
- Synthesis Toolkit
	- STK is a set of open source audio signal processing and algorithmic synthesis classes written in the C++ programming language.
	- The STK can be found [here](https://ccrma.stanford.edu/software/stk/).
