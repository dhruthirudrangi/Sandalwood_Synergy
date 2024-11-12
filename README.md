Task Overview-
Task 1: Automatic Speech Recognition (ASR) for Kannada
Objective: Convert a dataset of Kannada audio files related to Sandalwood cultivation into text. This transcription step is essential to make the audio content searchable for Task 2.

Steps Involved:

Preprocessing Audio Files: Convert audio files to a consistent format (e.g., WAV at 16kHz) and apply noise reduction.
Transcribing Audio: Use an ASR model, specifically OpenAI’s Whisper, to transcribe the Kannada audio files into text.
Translation to English (Optional): Translate the transcriptions to English if the end-user requires it.
Output: A text file (transcriptions.txt) containing transcriptions of each audio file, which can be queried for relevant information.

Task 2: Speech-Based Question Answering (QA)
Objective: Build a pipeline that allows users to ask questions in Kannada (via audio), transcribe the question, search the transcriptions generated in Task 1, and return relevant segments as answers.

Steps Involved:

Recording/Uploading the User’s Question: Capture the user’s question via an audio file, then transcribe it using Whisper.
Search Transcriptions: Search through the transcriptions created in Task 1 to find segments that are relevant to the question. This can be done using keyword matching or semantic search.
Return Relevant Segments: Display or play the audio segments that contain relevant answers to the question.
Output: Relevant answers (text segments) from the transcriptions that match the user’s question, and optionally, the playback of the original audio segments

The DataSet and the processed Audio files are present here: https://drive.google.com/drive/folders/1iwueDauXtamC9xGurxsiICOuxmtXgtJG?usp=sharing
