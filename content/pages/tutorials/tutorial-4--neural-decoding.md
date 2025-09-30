---
content_type: page
description: This page presents a video-based tutorial on the Neural Decoding Toolbox.
is_media_gallery: true
learning_resource_types:
- Tutorials
ocw_type: SupplementalResourceSection
parent_title: Tutorials
parent_type: SupplementalResourceSection
parent_uid: 1991b27f-a447-8dc0-a6a2-79748088784f
title: Tutorial 4. Neural Decoding
uid: 6ddfcb58-85ac-c7b6-42ae-b8f2b44f6561
video_metadata:
  youtube_id: null
videos:
  content:
  - 0d13227b-2e2d-4426-8860-f6be86659176
  website: res-9-003-brains-minds-and-machines-summer-course-summer-2015
---

Tutorial Overview
-----------------

{{< tableopen >}}
{{< tropen >}}
{{< tdopen >}}
{{< resource 930de496-ac6e-6629-9da3-9f86ce7dde29 >}}
{{< tdclose >}}
{{< tdopen >}}
In experiments by Zhang et al. (2011), monkeys viewed images depicting different classes of objects while researchers measured the neural signals generated for each image in an area of the brain known as IT cortex. These signals were later _decoded_ to determine the particular object class that was viewed. This figure shows a _confusion matrix_ that captures how well the class predicted by the decoding model matches the true object class that was viewed. (Image courtesy of Ethan Myers, used with permission.)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

What information is contained in the neural signals generated in a region of the brain, and how is this information encoded? Is it possible to decode the neural signals to determine what information they represent? In this tutorial you will learn about _population decoding,_ a powerful method to analyze neural data in order to understand the information contained in the data and how it is encoded. The method is demonstrated through experiments that probe the neural representations underlying visual object recognition in primate visual cortex. The Neural Decoding Toolbox, implemented in MATLAB{{< sup "®" >}}, enables researchers to apply this analysis to many sources of neural data such as single cell recordings, fMRI, MEG and EEG.

Unit Activities
---------------

### Useful Background

*   Introduction to neuroscience
*   Introduction to machine learning, including simple pattern classification methods

### Videos and Slides

{{< video-gallery "6ddfcb58-85ac-c7b6-42ae-b8f2b44f6561" >}}


Further Study
-------------

Meyers, E. "[The Neural Decoding Toolbox](https://www.ncbi.nlm.nih.gov/pmc/articles/PMC3660664/)." _Frontiers in Neuroinformatics_ 7, no. 8 (2013).

Also see the website for the [Neural Decoding Toolbox](http://www.readout.info/).

Meyers, E., M. Borzello, et al. ["Intelligent Information Loss: The Coding of Facial Identity, Head Pose, and Non-Face Information in the Macaque Face Patch System." (PDF)](http://emeyers.scripts.mit.edu/emeyers/wp-content/uploads/2015/05/Meyers_JNeurosci_2015.pdf) _The Journal of Neuroscience_ 35, no. 18 (2015): 7069–81.

Zhang, Y., E. M. Meyers, et al. ["Object Decoding with Attention in Inferior Temporal Cortex." (PDF)](http://www.pnas.org/content/108/21/8850.full.pdf) _Proceedings of the National Academy of Sciences_ 108, no. 21 (2011): 8850–55.