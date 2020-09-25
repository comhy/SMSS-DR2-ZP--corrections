# SMSS-DR2-ZP--corrections
Here we provide detail descriptions for the zero-point (ZP) corrections for the SkyMapper Southern Survey (SMSS) DR2 (also suitable for DR3).
The whole re-calibrations are predented in Huang et al. 2020 (submitted).

#1 reddening depedent ZP trends for SkyMapper uv bands: 
1) look-up table: uv-zp-ebv.txt 
2) For convenient purpose, we also fit the trend as a function of SFD E (B - V) by seventh-order polynomial function.
The coefficients are provided in Delta_u/v_coef.fits.

#2 sptial variations for ZP in SkyMapper uvgr bands:
The ZPs of uv bands show spatial varitions along dec, and the trends are fitted by fifth- and fourth-order polynomial function for different RA ranges.
The coefficients are provided in Delta_u/v_dec_coef-****.fits.
The ZPs of gr bands show spatial varitions along gb, and the trends are fitted by Eq. 3 in our paper for different gl ranges.
The coefficients are provided in Delta_g/r_gb_coef-****.fits.
