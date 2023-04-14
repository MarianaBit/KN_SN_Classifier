# Kilonova Spectroscopic Identification Using Deep Learning
This project seeks to understand how the use of Deep Learning can help in the identification of Kilonovae's spectral energy distribution (SED), testing different networks and studying which model achieves the best results when trying to differ between Supernovae e Kilonovae by its spectrum. If successful, the research in question can be used, for example, as a follow-up for the O4 LIGO-Virgo-KAGRA observing run.

Here you will see the code runned and its last results. This project is still in development, so we expect to continue at the improvement of the code and its results. Feel free to contact for more information.


### **About the data**

We utilized a diverse dataset composed of semi-curated data. To train the network, as its input, we used real Supernovae's SEDs and simulated Kilonovae's SEDs. We also used real SEDs from the Kilonova GW170817, applied as a final test for the neural network, to evaluate its performance on Kilonova's real data.

The Supernovae data were imported from the [Astrocats module for the Open Supernova Catalog](https://github.com/astrocatalogs/supernovae), from where we selected all Supernovae types I and II discovered between the years 2000 and the present.

The Kilonovae simulations where sourced from [KilonovaNet: Kilonova Surrogate Modelling](https://github.com/klukosiute/kilonovanet), and used the Bulla binary neutron star model, covering the whole range of parameters, and go from 0.2 to 6 days after the burst.
