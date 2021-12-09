# Matching BMRB peaks

The purpose of this protocol is to demonstrate how to match an in-house ^1^H ^15N^ HSQC Protein spectrum to annotation downloaded in star format (.str) from the BMRB.

Youtube demos available [here](https://www.tinyurl.com/nmrbox).

## Download .str from BMRB

Look-up protein of interest on [BMRB]( https://bmrb.io/ ) and download associated star (version3) file (as text).



## Open in house ^1^H ^15^N Protein HSQC in CCPN software

> For ease of access it is recommended that you use [NMRbox](https://nmrbox.org/).

1.  Register for a free NMRbox account [here](https://nmrbox.org/signup).

	> NMRbox account activation can take up to 3 days.

2. Then install the free software [RealVNC viewer](https://www.realvnc.com/en/connect/download/viewer/).

3. OpenVNC viewer and input a suitable NMRbox host (such as carbon.nmrbox.org)
4. Login with your NMRbox username and password.

5. Launch CCPN assign (type `assign` in the terminal).
6. Drag `spectrum` folder provided by the NMR Facility into the window marked `drop area`.

You should now have an interactive view of the ^1^H ^15^N HSQC spectrum.



## Add BMRB star file to the CCPN project

You can now drag and drop the `.str` file you downloaded from the BMRB in to the CCPN project. 

A pop-up window called IMPORT from NMRSTAR should open.

Click on `Simulate peaks from atom` and proceed (ignore warning that this feature is to be updated).

Now in the right hand list you should have two items under `Spectra` one will have the number from the HSQC folder and the other will be the newly imported peaklist. Expand that item and the peaklist within you can drag the peaklist ‘PL:NH and overlay on top of your spectra. 



## Check the match between annotation and spectra

There may be a slight offset, but you should see that the location and number of annotations matches the peaks within your spectrum.

