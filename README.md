# Modern microscopy

This repo serves as an archive for the information about microscopy gathered during my studies.

## Modern light microscopy
Classic microscopy focuses a lot on lenses and the interaction of light and matter and how that light is transported to the human eye. Today, with the invention of CCD cameras and nanometer scale semiconductors, microscopy has taken a turn towards being a more data-driven field. This also implies software and understanding of the data obtained from the microscope as well as how to present that information to other researchers. This manuscript aims to present the basics and best practices for new microscopy users to get their points clear across.
The microscope

Modern microscopy extends way beyond the magnification of objects using a lens. It is normal for modern microscopes to have several lenses and different light paths which can vary between different setups as well. The process of capturing the interaction between a sample and light we can consider the following elements of the microscope:
Illumination source, illumination path, signal creation and signal detection. 

## Wide-field methods
In light microscopy using white light, the whole spectrum from the light source is used to illuminate the sample. This is used for bright-field and phase-contrast microscopy. In bright-field microscopy, the sample is illuminated and due to scattering and absorption (attenuation)of light by interaction with the sample, the light collected on the other side, will have less intensity resembling the sample structure. The sample will look like dark structures on a light background.
In phase-contrast microscopy, a dark-field technique, white light interacts with the sample. Herein, the scattered light will have -90-degree phase shift. Using this knowledge, the scattered light is guided back onto the detector or eyepiece in such a way that the scattered light is constructively interfering with the background light. This makes the sample, usually the edges, appear lighter than the background.

## Monochromatic light
Monochromatic light is the term for light of only one color (wavelength). This can be achieved with different sources and excitation filters. Widefield illumination is created by light-emitting diodes (LEDs) or LASERs. LEDs utilize the bandgap in a semiconductor to create an energy difference that, when relaxed, emits light of a specific wavelength. Light amplification by stimulated emission of radiation (LASER) is the technology in which a diode has a gain medium with many excited electrons. If one photon is released, it can stimulate the other excited electrons to emit their photons too whereby the two photons will be of both same wavelengths and phases. This is termed “monochromatic” and “coherent”. The photons in the medium are reflected back and forth using mirrors to further amplify the number of photons. One of the mirrors can have a small hole where light can escape. From there, the beam can be focused and reflected to illuminate the sample.

![image](https://github.com/user-attachments/assets/aae180f9-93d9-4ac3-b881-d7ac6db8f991)

Lectures for inspiration:
MIT OpenCourseWare, “Laser Fundamentals I | MIT Understanding Lasers and Fiberoptics”,  (https://youtu.be/saVE7pMhaxk?si=qXl-480BIJUslpQF)

MIT OpenCourseWare, “Laser Fundamentals II | MIT Understanding Lasers and Fiberoptics”, (https://youtu.be/urbZ8CTceu0?si=L0w3Iv4W3LyN0IED)

## Illumination path
Like the effect of using interference in phase-contrast microscopy, the light path into the sample can be modified to achieve different angles of illumination and thereby sample interactions and the pattern of the light going out from the sample.
In a widefield microscope the sample is evenly illuminated by angling the light beam vertically to the sample axis. This results in the outgoing light interfering with the light beam. For widefield microscopy, the microscope can have oculars for the viewer, a camera mounted to detect the signal or a combination using mirrors to split the signal beam.
In contrast to widefield methods, scanning confocal microscopes only illuminate a small area of the sample and collect the signal from a single point, which removes the effect of out-of-focus light. However, the scanning mechanism results in increased time per image the higher the image resolution.

## Signal detection
Following the light-matter interaction at the sample, the signal is collected. This can be achieved in different ways. For scanning confocal microscopes, a point detector is used. This detector converts photons collected over a set time into voltage which is then converted into intensity for that image area (pixel). Cameras are chips with an array of small photo detectors. Having several data points collected for each time of exposure, the data must be transmitted to the computer to empty the camera chip and allow for collection of a new set of photons for a new voltage reading and a new frame.

Lectures for inspiration:
iBiology Techniques, “Microscopy: Cameras and Detectors I: How Do They Work? (Nico Stuurman)”, (https://youtu.be/8WpCov8iYCU?si=Ob5b70PGPa_CEIgZ)

iBiology Techniques, Microscopy: Introduction to Digital Images (Kurt Thorn), (https://youtu.be/SNl3kRBgW10?si=3t8Jbkno9HcdcsLH)
