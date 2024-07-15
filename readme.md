## Steps for setting up benchmark
* Important file: `video_questions/video_questions_n=10.txt` (generated by `generate_video_questions.py`)
* Run `python download_videos.py` and then run `python concat_mp4s.py` to get the longer videos

problematic examples:

29 --> asks for timelapse but it shows 3 videos??
30 --> unclear which is budapest?
35 --> toronto?
45 --> Should change the question 
from:
    What was the girl doing before she answered her cellphone?
to:
    What was the girl doing before the woman answered her cellphone?
47 --> Should change question and answer
Q from:
    What activities did the two men perform on the beach?
Q to:
    What activities did the two men perform together in the snow?
A from: 
    They built a snowman and played snowball volleyball.
A to:
    They threw the snow to each other and built a snowman.
48 --> Remove references to Kyiv Ukraine. General trned
55 --> Remove the word "hispanic"
59 --> Not answerable?
63 --> Should change the question and answer
Q from: 
    What was the gift box in one of the videos representing?
Q to:
    What was the gift box in one of the videos full of?
A from:
    The concept of Merry Christmas and Happy New Year.
A to:
    It is full of money, specifically $100 bills.
65 --> change hotel to resort?
66 --> change question
Q from: 
    Did the person see any wildlife during the video sequence?
Q to:
    Was there any wildlife during the video sequence?
71 --> bird species are hard for humans to answer
80 --> change question and answer
Q from:
    What can you do to save energy during the winter?
Q to:
    What is shown as a way to save energy?
A from:
    Adjusting a wall thermostat from 68�F to 62�F can save energy during the winter.
A to:
    Adjusting a wall thermostat to better match the outdoor temperature.
88 --> change question
Q from: 
    What type of landscape was shown in the video from Washington, United States of America?
Q to:
    What type of landscape was shown in the video containing snow?
89 --> change question
Q from:
    "young pople"
Q to:
    'young adults"