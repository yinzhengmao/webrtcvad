#webrtcvad.py
VAD切割语音
VAD mode可选0-3  
0是过滤掉非语音最不积极的，3是最具侵略性的，
其中可调试的参数有：Channels、sample_with、sample_rate、vadmode、frame_duration(10,20,30)、 padding_duration_ms；