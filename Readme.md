

# VT Science Week

The presentation and related material for the VT Science Week Imaging Workshop

- The introduction/business [slides](https://rawgit.com/4Quant/VT-Science-Week-2015/master/introslides.html)
- The workshop [slides](https://rawgit.com/4Quant/VT-Science-Week-2015/master/slides.html) can be seen here
- The version of the slides/workflows for the Biodesign Group (biomaterials, histology, etc) [here](http://4quant.com/Biodesign-Imaging-Workshop-2015)
- The workflows we made in the workshop (Cell Analysis/Counting, Chocolate Adhesion Analysis, and Bubble Detection) are [here](https://github.com/4Quant/VT-Science-Week-2015/blob/master/VTWeek.zip?raw=true) 

- A simple statistics workflow is available here [here](https://github.com/4Quant/Biodesign-Imaging-Workshop-2015/blob/master/BD2015.zip?raw=true)

- A simple example of the report which can be generated from the H&E images [here](Example-Report.pdf?raw=true)

## Simulation Related Tools
- [CompuCell3D](http://www.compucell3d.org/), a simulation tool based on the Cellular Potts Model.
- A talk we held at EUFOAM in 2014: "COARSENING IN LIQUID FOAMS: A HYBRID SIMULATION-EXPERIMENTAL TECHNIQUE"
 - [Presentation Slides](CoarseningFoams.pdf?raw=true)
- [Rheology Simulation](https://rawgit.com/4Quant/VT-Science-Week-2015/master/FoamAnimation.avi)

## Movie Related Tools
### Video Lan Client
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
- [KNIME Image Procesing Forums](https://tech.knime.org/forum/knime-image-processing), here you can ask questions about how to work and solve new problems in KNIME.
- [Report bugs in KNIME Image Processing](https://github.com/knime-ip/knip/issues)
 - Provide anonymous feedback on the course [here](https://docs.google.com/spreadsheet/embeddedform?formkey=dEtIX1ZXMzFacmdhRF9mQVpNaWtWTXc6MA)
 - Or send direct email (slightly less anonymous feedback) to [Kevin](mailto:mader@biomed.ee.ethz.ch)
- [KNIME Setup](https://github.com/kmader/Quantitative-Big-Imaging-2015/wiki/KNIME-Setup)

- [KNIME Youtube Video](https://www.youtube.com/watch?v=7HwCgleJMk4)

- [Quantitative Big Imaging Course](http://kmader.github.io/Quantitative-Big-Imaging-2015/)
- [Presentation at Spark Summit 2014](http://4quant.com/spark-summit-2014-presentation)
- A Demo of our [Quantitative Image Search Engine](https://kmader.shinyapps.io/SearchMachineDemo)


# 4Quant Use Cases
A few of the examples of technology that 4Quant has been developing.

### Medicine
- [Planning surgery and radiotherapy with real time segmentations](http://4quant.com/Realtime-MRI-Segmentation)
- [Segmenting organs from archived chest CT images](http://4quant.com/Organ-Segmentation/)
- [Finding lesions in Capsule Based Endoscopy](http://4quant.com/Capsule-Endoscopy)

### Geographic Information Systems
- [Calculating Flood Risk for Insurance Companies](http://4quant.com/Flood-Risk)
- [Counting Cars in Satellite Images](http://4quant.com/countingcarsdemo)
- [Finding buildings and forests in Satellite Images](http://4quant.com/geospatialdemo/)

### Surveillance
- [Count people from drone footage](http://4quant.com/Drone-People-Counting)
- [Finding criminals with traffic cameras](http://4quant.com/Pursuing-Criminals/)

### Real-time QA
- [Check train tracks in real time](http://4quant.com/Railway-Check)

### Fun
- [Untangling the flood of Online Dating](http://4quant.com/Online-Dating)
- [Quantitative Image Search Machine](http://kmader.shinyapps.io/SearchMachineDemo)

## Bio
Kevin Mader is the founder of 4Quant and a lecturer in the X-ray Microscopy Group within the Department for Information Technology and Electrical Engineering at ETH Zurich. His research focuses on turning big hairy 3D images into simple, robust, reproducible numbers without resorting to black boxes or magic. In particular, as part of several collaborations, he is currently working on automatically segmenting full animal zebrafish images, characterizing rheology in 3D flows, and measuring viral infection dynamics in cell lines.



