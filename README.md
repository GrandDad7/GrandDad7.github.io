## Welcome to the Synth Programming Language Website!

You can use find the link to GitHub Repository [here](https://github.com/GabrielGonzalez30/Synth). This site is meant to explain the documentation of what our language does.


## Synth: Interactive Audio Processing Language

Built by:
 - Gabriel González
 - Pedro Santiago
 - José Túa
 - Jaime Torrens

## Scope of the Project: What does the Language bring to the table?
### Overview
<body>
    <p>
		 The purpose of this project is to create an interactive audio synthesizer and music production software encapsulated in a interpreted programming language. The main motivation to develop this language is to help programmers (especially game developers, web developers; generally programmers concerned with UI/UX) to create distinct and original sounds and music for their projects in a way that they are familiar with. 
    </p>  
    <p> 
        Normally to create original audio, a person must pay for expensive software that is hard to get started withespecially when trying to edit specific audio files. This is not ideal for an independent/freelance game developer who doesn’t have much background in audio processing or sound/music in general. To remedy this, Synth will be developed so that the game developercan create and modify sounds without having to learn much about the specifics.
    </p>  
    <p>
        As stated before, this will be an interpreted programming language, indicating that it is high-level, as it carries some similarities from Python. While the person is editing/coding their sound (unless the user wants to create their own sound file), they would be able to hear the sound they are currently editing. As easily as they can grab their own existing sound file and edit it, they can do many edits such as adding reverb, reducing tone and pitch, and so much more.
    </p>
</body>

## Language Features
- Able to create, modify and store audio files (mp3, wav, etc) via sound synthesis and sound recording (called streams), as well as realtime playback of streams.
- Able to create & modify effects, add effects to different streams.
- Able to interface with MIDI controllers, as well as create a keyboard, soundboards, etc., using a computer keyboard


## Code Samples
```markdown
# Initializing Streams
`InitStream s1 as Synthesizer`
Intializes a stream of a Synthesizer instrument as any symbol, s1 in this case.

`InitStream s183 as Synthesizer`
Intializes a stream of a Synthesizer instrument as any symbol, s183 in this case.

**Initializing an existing stream will empty that existing stream and render it empty.**

# Adding Waves to Stream
**The following line will only happen if a Stream has been initialized.** 
**Otherwise, this cannot occur.**
1. `As s1 setWave(Sine,600)`
In the s1 stream, creates a Sine wave with a frequency of 600.

2. `As s1 setWave(Sine)`
In the s1 stream, creates a Sine wave with a default frequency of 200.

3. `As s183 setWave(Saw)`
In the s183 stream, creates a Saw wave with a default frequency of 200.

4. `As s1 setWave(Square,250)`
In the s1 stream, creates a Square wave with a frequency of 250.

# Changing Frequencies of Waves
1. `As s1 setFrequency(100)`
In the s1 stream, frequencies are changed to 100 as parameters imply.

# Playing Streams
**If no streams have been initialized, this will return an exception.**
**Streams must exist for this to work.**
1. `play(s1)`
Plays the s1 symbol waves stream.

#Pausing Streams
**If no streams have been initialized, this will return an exception.**
**Streams must exist for this to work.**
1. `pause(s183)`
Pauses the s1 symbol waves stream.
```


## Showcasing Video
<iframe width="560" height="315" src="https://www.youtube.com/embed/xRjBA49gyc8" frameborder="0" allow="accelerometer; autoplay; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>

## Built With/Tools
- Implementation Languages: C++ (gcc for Unix, Visual C++ for Windows)
- Git and GitHub for source control
- Synthesis Toolkit
	- STK is a set of open source audio signal processing and algorithmic synthesis classes written in the C++ programming language.
	- The STK can be found [here](https://ccrma.stanford.edu/software/stk/).


## Conclusion
<body>
	<p>
	Working together to form a project in a language that half of the group is not too skilled in was a challenge (to those not knowledgeable) but it was a feat nonetheless. We did choose C++ because all other projects would be implemented in languages that they are mostly familiar with, like Python (or even Scala in some cases as it seemed.) We had decided to not take the easy way out and challenge ourselves. 
	</p>
	<p>
	
	</p>
	<p>
	This has certainly been a good experience, learning how to provide a project report with its own progress chart. We would like to 
	</p>
</body>
