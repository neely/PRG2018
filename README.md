# PRG2018

LC Gradient<br />
The MS methods given below have included LC methods, but due to the diversity of LC systems as well as nano- or micro-flow applications, the PRG is assuming users can set up their gradients appropriately. Broadly, we assume you are doing a two-stage linear gradient lasting 110-130 min. Below are some options, or feel free to use a gradient you prefer for a complex mammalian tissue lysate like HeLa. If you use your own LC gradient there will be a csv in your upload folder where you can paste your gradient and mobile phase information.

(all % are acetonitrile, ACN, so adjust based on your mobile phase compositions)

130 min gradient<br />
equilibrate<br />
5-25% ACN over 100 min<br />
25-40% ACN over 20 min<br />
40-90% over 10 min<br />
Hold at 90% for 5 min<br />
90-5% over 1 min<br />
re-equilibrate<br />


Acquisition Settings<br />
The PRG has generated MS methods for this study. If you have never used DIA we feel these are excellent starting points, but also acknowledge you will be able to improve them as you grow more comfortable with your specific setup’s performance.

When constructing a DIA experiment, the MS2 mass range, number of MS2 windows, MS2 window width and time spent acquiring data all contribute to determining your instrument’s cycle time and therefore how many data points you will acquire over a peptide’s elution peak. For this study we have specified static MS2 window widths covering 400-1200 m/z, with a 1 Th overlap. We encourage you to learn more about other window strategies, but think these are adequate initial settings.

We are assuming a 30 sec peak width at base and therefore these methods all have 3.5 sec cycles to achieve between 7 and 10 data points per peak. This cycle time is slightly longer than some recommendations, and if you have shorter peaks they will be undersampled. Although not required, if you would like advice on how to generate a 3, 2.5 or 2 sec cycle method please email us at prg.abrf@gmail.com. For the Lumos (and likely the QE-HFX) running at 30k resolution for MS2, 34 windows will be 3 sec, 27 windows should be 2.5 sec, and 22 windows should be 2 sec. For the Lumos  running at 15k resolution for MS2, 54 windows will be 3 sec, 44 windows should be 2.5 sec and 34 windows should be 2 sec. When adjusting the given method you will need to adjust the quad isolation width and input a new table of center masses (and possibly change the MS1 mass range if needed).

![linreg](https://raw.githubusercontent.com/neely/PRG2018/master/misc/LinearRegression.PNG "Linear Regression of cycle time and number of DIA windows")


![Thermo Settings Table](https://raw.githubusercontent.com/neely/PRG2018/master/misc/ThermoSettingsTable.PNG "Abbreviated settings for Thermo instruments")

Method Files:<br />
Lumos/Fusion<br />
PRG2018_Lumos_130min_15kMS2_62_14mz.meth<br />
PRG2018_Lumos_130min_30kMS2_40_21mz.meth<br />

QE-HFX<br />
PRG2018_QE-HFX_145min_30kMS2_40_21mz.meth<br />

Waters<br />
PRG2018_SYNAPT_17_65V.luc<br />

SCIEX
PRG2018_TTOF_117min_80_11mz.dam<br />


# Check back later for tables here summarizing these methods.
