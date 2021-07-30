# Research

My primary research interests lie in the field of Solar physics, specifically temporally variant magnetic features
and how these phenomena can be detected, tracked, and modeled for a variety of scientific uses.

Below are outlines of my research experiences while at UCLA. 


## Summer 2021: NASA Jet Propulsion Laboratory

This summer I am taking my knowledge and background in Solar physics and applying it to a new field -- radial velocity detection
of exoplanets. To explore activity signatures in Sun-like stars, we focus on studying variations in resolved space-based Solar images 
and ground-based disc-integrated spectra.

*Project Abstract:* Stellar activity is a key roadblock towards reaching the sensitivity required to 
recover Earth-like exoplanetary signals using the radial velocity (RV) detection 
method. High resolution Dopplergrams, magnetograms, and continuum filtergrams from the Helioseismic and 
Magnetic Imager (HMI) aboard the Solar Dynamics Observatory (SDO) allow us to independently derive ‘sun-as-a-star’ 
Solar RV variations due to rotationally modulated flux imbalances and convective blueshift suppression. We present a 
comparison of SDO/HMI-derived RVs and observables with ground-based disc-integrated Doppler measurements from the NEID 
spectrograph, showing that the dominant signal in NEID RVs is due to suppression of convective blueshift. Applying our 
techniques to archival Solar system planetary transits, we demonstrate the ability to recover RV variations in SDO data 
at the 5 cm/s level. We find a strong relationship between magnetic activity indicators and RV variation, supporting 
efforts to examine unsigned magnetic flux as a proxy for stellar activity in slowly rotating stars. Fitting for unsigned 
magnetic flux allows us to improve observed scatter in NEID RV measurements by more than 50%, down to ~30 cm/s over 
several months. We also explore potential correlations between individual and averaged spectral line shapes, and 
magnetic activity indicators, motivating future studies of these observables.

## Academic Period 2020-2021: Predictive Science Inc./UCLA Atmospheric Sciences Department

In a joint project with my advisor at Predictive Science Cooper Downs and UCLA Faculty Advisor Jacob Bortnik, I spent the school
year building machine learning algorithms to detect, track, and model coronal holes and other Solar active regions. I presented
my research at the American Geophysical Union's Annual Conference, AOS seminars, and UCLA Undergraduate Research Week. I was 
additionally awarded a UCLA Undergraduate Research Prize. We are currently in the process of publishing this project's results.

*Project Abstract:* Modelling and tracking the evolution of magnetic activity in the Solar corona is a vital piece to improving
our understanding of the near-Earth environment and for space weather prediction. In addition to temporal evolution, the Solar surface
is spatially variant making it difficult to build empirical models of the Sun. Detection of magnetically active Solar Coronal regions such as Coronal Mass Ejections,
Coronal Holes, and Active Regions is the next step towards building a robust and dynamic model of the Sun. We build upon previous threshold detection methods to improve 
our modelling of the temporal instability of Solar magnetic features. Long-term averages of EUVI/STEREO A/B (195 Å) and SDO/AIA (193 Å) images are used 
to build full-Sun maps for Coronal Hole (CH) and Active Region (AR) detection. After image 
processing, we detect CH/AR regions using two primary machine learning methods: a convolutional 
neural network (CNN) and K-means clustering. The CNN model is a supervised learning model for 
image segmentation while K-means is an unsupervised clustering model. These models both provide 
exceptional CH detections while the unsupervised method gives us the additional capability of detecting 
previously undetected Solar active regions. We find that the unsupervised clustering method provides the most user independent results as it mitigates
the relentless problem of observation bias. 


## March - Summer 2020: Predictive Science Inc.

I started working on the Solar Physics Project at Predictive Science in March 2020 where my goals were to build an analysis
pipeline to calculate data driven corrections to Solar disk images for detection and mapping purposes. This project fed into the machine
learning models I built during the following school year and provided the basis for my interest in Solar Physics. I presented
this updated data analysis pipeline and database structure at the American Geophysical Union's Annual Conference. We
are in the publication process for this work and have published the preliminary [Python package](https://github.com/predsci/CHMAP)
for use by the Solar physics community.  

*Project Abstract:* The detection and mapping of coronal holes in Solar EUV and X-Ray images is useful for a variety of scientific and
space weather prediction applications. We discuss a community oriented python package to facilitate the creation of science quality full-sun coronal hole maps. Our package builds upon a
previous pipeline for multi spacecraft synchronic mapping and detection (Caplan et al. 2016), where long-term
averages of EUVI/STEREO A/B (195 Å) and SDO/AIA (193 Å) images are used to compute data-derived
corrections for center-to-limb variations in images and intensity differences among instruments. The calculation of
these corrections has been greatly simplified through modern database storage and querying techniques implemented
in the image processing pipeline. After image processing, CH regions are detected using our two-threshold
region-growing algorithm, which uses pixel-connectivity requirements to avoid false detections. Results are mapped
on an image-by-image basis and merged to create full-Sun EUV and CH maps. The merge-mapping process favors lower
intensity data in areas of overlap, and an arbitrary number of images may be used, helping to mitigate the
systematics of obscuration and evolution. With this flexible new framework and data-driven approach to CH
detection, we explore methods for creating time-dependent coronal hole probability maps and evaluate their use for
model comparison and forecasting purposes.

## Summer 2019: Simons Observatory Small Aperature Telescope

I worked on the Simons Observatory Small Aperature Telescope at UCSD's Cosmology Lab. This is a small aperture cryogenic
telescope observed the Cosmic Microwave Background (CMB). The CMB is the remnant radiation from the origin of the universe
and can be used to confirm origin theory's. While working with this group, I primarily dealt with data analysis and monitoring
of cryogenic telescope components. I designed circuitry components for collecting thermometry data and ran load tests on the cryogenic
pulse tube. These results have recently been accepted for [publication](https://www.sciencedirect.com/science/article/pii/S0011227521000813?via%3Dihub).