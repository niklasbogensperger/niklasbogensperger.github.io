---
title: "brain"
subtitle: "3D printing"
weight: 80
date: "2024-05-01T12:00:00+02:00"
image: "gallery/80_brain.png"
alt: "brain"
draft: false
---


This is a 3D-printed model of my brain, created from an MRI image set.\
Below are the steps I followed to achieve this (based on [this guide I used&nbsp;{{< svg "static/link_modal.svg" >}}](https://printspired.shop/blogs/news/3d-printing-your-brain)):

{{< icon "arrow-right" >}}&MediumSpace;&MediumSpace;Raw DICOM images\
{{< icon "arrow-right" >}}&MediumSpace;&MediumSpace;[Slicer&nbsp;{{< svg "static/link_modal.svg" >}}](https://www.slicer.org/)&MediumSpace;to preview and export\
{{< icon "arrow-right" >}}&MediumSpace;&MediumSpace;[freesurfer&nbsp;{{< svg "static/link_modal.svg" >}}](https://surfer.nmr.mgh.harvard.edu/)&MediumSpace;to analyze the data and generate/reconstruct a 3D surface of the brain\
{{< icon "arrow-right" >}}&MediumSpace;&MediumSpace;[MeshLab&nbsp;{{< svg "static/link_modal.svg" >}}](https://www.meshlab.net/)&MediumSpace;to clean up the 3D surface before printing\
{{< icon "arrow-right" >}}&MediumSpace;&MediumSpace;[PrusaSlicer&nbsp;{{< svg "static/link_modal.svg" >}}](https://www.prusa3d.com/en/page/prusaslicer_424/)&MediumSpace;to generate the G-code for the 3D printer

![brain_stl](/brain_stl.png) ![brain_printed](/brain_printed.png)
