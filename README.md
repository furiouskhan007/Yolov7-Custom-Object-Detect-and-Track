# Yolov7-Custom-Object-Detect-and-Track
# Must train model for custom object
## Dependencies
* pip install -r requirements.txt

How to run for file:
<pre><code>python detect.py</code></pre>
* From CMD Terminal for live detection
<pre><code>python detect_or_track.py --weights best.pt --no-trace --view-img --nosave --source sample.mp4 --show-fps --seed 2 --track </code></pre>
<pre><code>python detect_or_track.py --weights best.pt --no-trace --view-img --nosave --source sample.mp4 --show-fps --seed 2 --track --nobbox</code></pre>
<pre><code>python detect_or_track.py --weights best.pt --no-trace --view-img --nosave --source sample.mp4 --show-fps --seed 2 --track --show-track</code></pre>
<pre><code>python detect_or_track.py --weights best.pt --no-trace --view-img --nosave --source sample.mp4 --show-fps --seed 2 --track --nobbox --nolabel --thickness 3</code></pre>

* this will make the output windows size to 720*1080
<pre><code>python Track_output_View720.py --weights best.pt --no-trace --view-img --nosave --source sample.mp4 --show-fps --seed 2 --track </code></pre>

# result

![ezgif com-video-to-gif](https://github.com/furiouskhan007/Yolov7-Custom-Object-Detect-and-Track/assets/135207625/beee9fbd-952f-40c3-acf7-fc665f6c4cb8)
