Audio Transcription AIED 
===============================

The Audio Transcription Intelligent Tutoring System is a series of learning exercises with automated feedback for developing skills related to audio
transcription. 

The primary knowledge components for the system is the transcription of rhythm into classical notation, and the recognition of intervals in music
provided a starting note. The system does not aim to teach students to recognize certain notes, merely the intervals and chord qualities associated with certain 
sounds. Furthermore, the system assumes a basic understanding of musical knowledge before entering the system, only providing an interface to hone these skills, 
rather than teach them in the first place.

This means that the system will help hone the ability to recognize intervals, but will not provide a specific lesson on different intervals in the first place. 
Additionally, the system assumes student are familiar with note lengths and classical musicial notation before beginning tutoring sessions. Thus the 
system assumes knowledge of sixteenth, eighth, quarter, half, and whole notes; both in their appearance and the length of the components in musical notation. The
sustem hopes to help students recognize these components in music, not learn these components on their own. 



Interval Recognition
-----------------------------

Students will hear two notes, then the two notes together in a defined interval chord. For example, an audio playback would play a G note, then a D note, then a G and D note 
together to create a major 5th. Learners would need to choose the defined interval from a list of options below. The options would hope to include all possible 
intervals. Intervals may include:

Minor 2nd
Major 2nd
Minor 3rd
Major 3rd
Perfect 4th
Diminished 5th
Major 5th
Minor 6th
Major 6th
Dominant 7th
Major 7th
Octave

Files for Interval Recognition and Learner Model Updating
------------------------------

Lessons would be loaded from an existing file. This file would contain simply the mp3 file for interval playback, and the correct answer. These are loaded directly into the 
system when navigating to the page for the specific lesson. The learner model will contain a log of competency for each interval. Following the student selection
the system will determine whether the answer is correct, or incorrect. Provided the model is correct, a positive response will be given, and the learner model will be updated
with the percentage of correct recogntiions of the interval. provided an incorrect response, the system will player the user's selection, as well as the original recording back
to back as feedback. Then the system will update the percentage of correct recognitions will a negative impact on the total percentage. 

Rhythm Transcription
------------------------------

Students will be expected to hear an audio playback of music, both with melody, and without. Though, all sequences are expected to be monophonic due to systems and learner limitations. 

 Following the listening of the given excerpt, students will be expected to represent the sequence in rhythm notation. 

Students will be presented with a clear four bar music sheet, and a series of drag and drop icons for differing lengths of music. Students will be expected to listen to the
music, and transcribe the rhythm onto the sheet music. 

For example, a musical sequence may play four quarter notes, one for each bar. The learner will then be expected to place four quarter notes at the start of each 
measure as well as the corresponding number of rests.

The original piece for transcription is played from a stored mp3 files, configured specially for the lessons. At any point of transcription students can 
choose to play their written transcription. This is acheived through MIDI playback based on the configured midi inputs. 

Reading Rhythm Transcription Files
-------------------------------

The rhythm transcription files are structured in terms of 16th notes. No transcription will exceed sixteenth subdivison intervals and triplets 
will not be considered. Rhythm transcription files will appear as such. "," characters represent a 16th note rest. q represents a quarter note. 


        q,,,,q,,,,;q,,,,q,,,,;q,,,,q,,,,;q,,,,q,,,,;

This can be expaded to differeing characters. For example, 

w -> whole note
h -> half note
q -> quarter note
e -> eigth note
s -> sixtheenth note

Rhythm transcription files may appear in any valid combination as appears above and are read from a static file. 


