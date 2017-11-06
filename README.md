# SALTAD
The SALTAD software package is comprised of a series of "C" language function modules for image processing multiframe image data to detect moving asteroids in a star cluttered background. The software utilizes a matched filter detection algorithm to enhance moving point sources propagating with a linear, constant velocity. The software registers each frame of the multi-frame set, estimates and removes the stationary background, estimates the second order noise statistics (covariance matrix) and suppresses the clutter (whitens) the demeaned imagery. A hypothesis set of motion directions and speeds are used to form the matched filter output, tested via CFAR detection, screened for false alarms, to produce a final list of moving object detections. The software is highly modularized for interfacing to existing NEA search facility software and has been used at the Spacewatch facility of the University of Arizona.

SALTAD Software Distribution Instructions.

The matched filter software package SALTAD, trajectory generator software TGEN, and pattern matcher software PMATCH, have a limited release status with NASA's Office of Technology Transfer. Thus to obtain a copy of the software, the prospective user must fill out and have signed the two documents found in the folder with this readme. The forms must be signed by a authorized representative of the individual, company, university, or organization making the request. The two documents are the software users agreement and recipient's information form. In addition, a short description of how the software will be utilized should be included as a third document.

Please email the signed documents as PDFs to either peter.s.gural@leidos.com  or  paul.r.otto@leidos.com

If no reply, then contact NASA's Office of Technology Transfer and reference NASA case number GSC-16050-1.