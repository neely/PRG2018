# PRG2018

LC Gradient
The MS methods given below have included LC methods, but due to the diversity of LC systems as well as nano- or micro-flow applications, the PRG is assuming users can set up their gradients appropriately. Broadly, we assume you are doing a two-stage linear gradient lasting 110-130 min. Below are some options, or feel free to use a gradient you prefer for a complex mammalian tissue lysate like HeLa. If you use your own LC gradient there will be a csv in your upload folder where you can paste your gradient and mobile phase information.

(all % are acetonitrile, ACN, so adjust based on your mobile phase compositions)

130 min gradient
equilibrate
5-25% ACN over 100 min
25-40% ACN over 20 min
40-90% over 10 min
Hold at 90% for 5 min
90-5% over 1 min
re-equilibrate


Acquisition Settings
The PRG has generated MS methods for this study. If you have never used DIA we feel these are excellent starting points, but also acknowledge you will be able to improve them as you grow more comfortable with your specific setup’s performance.

When constructing a DIA experiment, the MS2 mass range, number of MS2 windows, MS2 window width and time spent acquiring data all contribute to determining your instrument’s cycle time and therefore how many data points you will acquire over a peptide’s elution peak. For this study we have specified static MS2 window widths covering 400-1200 m/z, with a 1 Th overlap. We encourage you to learn more about other window strategies, but think these are adequate initial settings.

We are assuming a 30 sec peak width at base and therefore these methods all have 3.5 sec cycles to achieve between 7 and 10 data points per peak. This cycle time is slightly longer than some recommendations, and if you have shorter peaks they will be undersampled. Although not required, if you would like advice on how to generate a 3, 2.5 or 2 sec cycle method please email us at prg.abrf@gmail.com.

Method Files:
Lumos/Fusion
PRG2018_Lumos_130min_15kMS2_62_14mz.meth
PRG2018_Lumos_130min_30kMS2_40_21mz.meth

QE-HFX
PRG2018_QE-HFX_145min_30kMS2_40_21mz.meth


Waters
PRG2018_SYNAPT_17_65V.luc (right-click and save-as)


SCIEX
PRG2018_TTOF_117min_80_11mz.dam


# Check back later for tables here summarizing these methods.
