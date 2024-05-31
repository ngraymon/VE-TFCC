Temporary public repo for sharing code (if needed).
Most likely will be used for continuing support of VE-TFCC on an ongoing basis.
For questions or information about the code please reach out to me at neil.raymond@uwaterloo.ca.


# VE-TFCC

Software for running the vibrational electronic-thermofield coupled cluster (VE-TFCC) approach as outlined in [https://doi.org/10.1021/acs.jctc.4c00338](https://doi/10.1021/acs.jctc.4c00338).
The TF-VECC method is aimed at extending the vibrational electronic coupled-cluster (VECC) approach ([https://doi.org/10.1063/5.0190034](https://doi.org/10.1063/5.0190034))  to calculate thermal properties of non-adiabatic vibronic models.
The repo may also contain assorted scripts for generating spectra[^1] and managing vibronic models[^2].
The original equations-of-motion (EOM) were generated using the package [termfactory](https://github.com/ngraymon/termfactory) although they may have been modified due to the introduciton of thermofield (TF) theory.


[^1]: using `autospec` from MCTDH
[^2]: using the `vIO` module, with a fairly recent version available [here](https://github.com/ngraymon/vmio). (Most of the module originated from [these scripts](https://github.com/ngraymon/Pibronic/tree/master/pibronic/vibronic)).

