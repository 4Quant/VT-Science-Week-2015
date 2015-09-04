

# VT Science Week

The presentation and related material for the VT Science Week Imaging Workshop

- The introduction/business [slides](https://rawgit.com/4Quant/VT-Science-Week-2015/master/introslides.html)
- The workshop [slides](https://rawgit.com/4Quant/VT-Science-Week-2015/master/slides.html) can be seen here
- The version of the slides/workflows for the Biodesign Group (biomaterials, histology, etc) [here](http://4quant.com/Biodesign-Imaging-Workshop-2015)
- The workflows we made in the workshop (Cell Analysis/Counting, Chocolate Adhesion Analysis, and Bubble Detection) are [here](https://github.com/4Quant/VT-Science-Week-2015/blob/master/VTWeek.zip?raw=true) 

- A simple statistics workflow is available here [here](https://github.com/4Quant/Biodesign-Imaging-Workshop-2015/blob/master/BD2015.zip?raw=true)

- A simple example of the report which can be generated from the H&E images [here](Example-Report.pdf?raw=true)

## Movie Related Tools
### Video Lan Client
VLC - Video Lan Client
===
This tool is one of the most flexible that can plan and transform a large variety of video content.

Example

```
/Applications/VLC.app/Contents/MacOS/VLC ../DroneVideo.mov --video-filter=scene --vout=dummy --no-repeat --scene-ratio=6 --rate=0.01 --scene-prefix="drone"  --scene-path=./ vlc://quit
``` 

$PathToVLC PathToVideo$
- ```-video-filter=scene --vout=dummy --no-repeat``` fixed standard settings (no repeat prevents looping)
- ```-scene-ratio``` is the number of frames it skips (30 is every 30 frames $\rightarrow$ once every second)
- ```--rate``` is the playback rate (1 is 100%, 0.01 is 1%, the more frames you capture the slower this needs to be to make sure you keep up)

- Lucie's video to image command (must be adapted to where VLC is located)
```
/Applications/VLC.app/Contents/MacOS/VLC ../TrimmedVideo.mov --video-filter=scene --vout=dummy --no-repeat --scene-ratio=300 --rate=8 --scene-prefix="drone"  --scene-path=./ vlc://quit
```

## Relevant Links
- KNIME Image Procesing Forums (__missing link__), here you can ask questions about how to work and solve new problems in KNIME.
- [Report bugs in KNIME Image Processing](https://github.com/knime-ip/knip/issues)
- [KNIME Setup](https://github.com/kmader/Quantitative-Big-Imaging-2015/wiki/KNIME-Setup)

- [KNIME Youtube Video](https://www.youtube.com/watch?v=7HwCgleJMk4)

- [Quantitative Big Imaging Course](http://kmader.github.io/Quantitative-Big-Imaging-2015/)
- [Presentation at Spark Summit 2014](http://4quant.com/spark-summit-2014-presentation)
- A Demo of our [Quantitative Image Search Engine](https://kmader.shinyapps.io/SearchMachineDemo)

## Bio
Kevin Mader is the founder of 4Quant and a lecturer in the X-ray Microscopy Group within the Department for Information Technology and Electrical Engineering at ETH Zurich. His research focuses on turning big hairy 3D images into simple, robust, reproducible numbers without resorting to black boxes or magic. In particular, as part of several collaborations, he is currently working on automatically segmenting full animal zebrafish images, characterizing rheology in 3D flows, and measuring viral infection dynamics in cell lines.



