# Interspeech2025-SEP28kWhisperBenchmarking

The python notebook contains the code used for the manual transcription of SEP-28k Clips- inference runs of Whisper 2 and 3 on this audio- the data analysis- and the graphing of results for this work.

There is also an audio folder with all the audio clips from SEP-28k used in this research. 

The CSV file contains the results of the project- and for each clip- it shows
- stutter_present: Binary label for whether the audio clip contains a stuttering event
- manual_prolongation: Binary label for whether the audio clip contains a Prolongation
- manual_block: Binary label for whether the audio clip contains a Block
- manual_soundRep: Binary label for whether the audio clip contains a Sound Repetition 
- manual_wordRep: Binary label for whether the audio clip contains a Word Repetition
- manual_interject: Binary label for whether the audio clip contains an Interjection
- hallucination_binary: Binary label for whether the audio clip contains a Hallucination
- manual_transcription_semantic: Transcription of audio clip with stuttering events removed
- manual_transcription_literal: Transcription of audio clip with stuttering events included
- Whisper2Annotation: Transcription of audio clip created by Whisper 2
- Whisper3Annotation: Transcription of audio clip created by Whisper 3
- audio_clip_name: (show name)\_(episode id)\_(clip id)


[![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.15559782.svg)](https://doi.org/10.5281/zenodo.15559782)
