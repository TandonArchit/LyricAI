# LyricAI
LyricAI: Convert songs to a videos!

#### Step 1
We start by converting the mp3 file into two, one with just the instruments and another with just the vocals.
#### Step 2
We pass on the vocals to Assembly AI using their API and call the transcript.
#### Step 3
Now that we have the transcript, we split it into individual words and run our video and image function on each of the words.
#### Step 4
We now have hundreds of mini mp4 files, each one for each word. So, we combine all of these into one mp4 file.
#### Step 5
Finally, we add the instrument audio that we generated some time ago to the video and render the final video. Voila!
