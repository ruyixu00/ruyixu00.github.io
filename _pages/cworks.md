---
layout: archive
title: "Current Work(s)"
permalink: /cworks/
author_profile: true
---
{% include base_path %}

## Organic Molecules in Star Formation Regions

Currently, I am working with Professor Rachel Friesen and Dr. Duo Xu looking at long carbon chains in star forming regions. I am using a [machine learning package](https://github.com/jdhenshaw/acorns) to identify clusters of different organic molecules as seen below 
<div style="text-align: center;">
  <figure style="width:800px">
	  <img src="/HC5N_C2S.png" alt="HC5N C2S plot">
	  <figcaption>clusters of HC5N and C2S identified in B18 </figcaption>
      </figure>
    <figure style="width:800px">
	  <img src="/NH3.png" alt="NH3 plot">
	  <figcaption>clusters of NH3 identified in B18 </figcaption>
      </figure>
        </div>
Using these results together with Dust maps from the James Clark Maxwell Telescope and Carbon Monoxide maps from the Five College Radio Astronomical Observatory. We set out boundries of each cores using dust and then compute the virial parameters of each of these molecules and compare them to the abundance of the complex molecules. Initial analysis shows us that there are some positive relations between the stability of such cores and the abundance of complex molecules. 
<div style="text-align: center;">
  <figure style="width:800px">
	  <img src="/Virial%20Analysis.png" alt="Plot of Virial Parameters against observed intensities of Complex molecules">
	  <figcaption> Plot of Virial Parameters against observed intensities of Complex molecules. Here a smaller Virial parameter indicates a more stable system, stability is achieved at α=2. From the diagram we can clearly see that as observed intensities inceas Virial Parameter decreases indicating a more stable core.  </figcaption>
      </figure>
        </div>
**Future Plans**
Future work currently I am working on include adding in pressure parameters to the model and publishing my results as a paper. Other possible work that can be explored with the project include increasing the complexity of our modules by considering factors such as magnetic fields, rotational kinematics and probing into the chemistry of such regions.

## Project Stars

Project Stars is a Research Course Project done in collaboration with Aditya Khandewal under the supervision of Prof. Roberto Abraham. The project utilises 3-5 ZWO Seestar S50 controlled by a [SEESTAR_ALP API](https://github.com/smart-underworld/seestar_alp). My work in this project mainly revolves around data collection, such as wrting Server Messaging Block (SMB) scripts for the transfer of data from the SEESTAR to a cloud location and debugging issues with the SEESTAR. Currently we are resolving some issues with calibration but otherwise have a well developed pipeline to acquire, store, analyse and visualise observable scientific interests like variable stars such as the one below
<div style="text-align: center;">
  <figure style="width:800px">
	  <img src="/light%20curve.png" alt="Seestar lightcurve">
	  <figcaption>Light Curve of 44 Boötes B a variable star with a period of 6.43Hrs. between 300 and 400 minutes we can see issues with the magnitude not following the curve and throught the plot we can roughly see 2 distinct light curves as a result of the seestars not calibreated the same.</figcaption>
      </figure>
        </div>
**Future Plans**
Future work involve resolving our current calibration issues and then developing a manual for the usage of our pipeline. Once this is done we aim to make comparisons with ore expensive telescopes to see the cost to snr ratio of using such methoods, we aim to publish a paper on this topic as well.

## Exposure Time Calculator for UofT E.C Carr observatory

This is a Work Study Project involving developing a exposure time calculator for non-science students to use the Half-Meter telescope at the E.C Carr Astronomical Observatory for their coursework. Currently the exposure calculator assumes all object are point source targets and takes into account the sky brightness of the location, twilight brightness and moon brightness. The current version of the calulator can be found here.
 **Future Work**
Currently there are plans to add in more weather factors into the calculator such as atmospheric extinction, humidity, pressure and etc. Aside from this there are plans to develop an extended object version of this calculator and add a search catalogue to atoumatically find the magnitude of the object observed.

