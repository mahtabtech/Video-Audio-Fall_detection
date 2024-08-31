# Video-Audio-Fall_detection
 A multimodal fall detection approach based on video and audio
 
A multimodal fall detection approach based on video and audio. In this multimodal we use RGB frames of video files plus audio files to create a multimodal for detecting falls in challenging conditions. For video stream we have used Inception+LSTM+attention, and for audio stream we have use M5+attention. This multimodal has been tested under 9 challengings conditions includings noisy video frames like blurred videos or low quality videos and the results of the multimodal are better compared to single modality models.

The code includes both audio and video models separately and the multimodal model with different fusing approaches including: mid-level fusion,  simple averaging, Majority Voting, Weighted Voting, weighted averaging.

Published paper:

