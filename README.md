# (In)validating environmental hypotheses in Cyprus: an econometric analysis

Code for my group project about (in)validating environmental hypotheses in Cyprus. 
Authors: Andrea Bisbjerg, Theresa Bensch, Julia Lunardi. 

This project was developed to answer the following research questions: 
  Main question: Are the pollution haven, pollution halo, and/or Environmental Kuznets Curve hypotheses valid in the case of Cyprus?
  Subquestions: 
    1. Does FDI demonstrate the possible validation of the pollution haven or halo hypotheses in Cyprus?
    2. Does GDP demonstrate the possible validation of the EKC in Cyprus?
    3. What type of causality can be established among the dependent/independent variables?

# The full paper can be accessed here: https://rucforsk.ruc.dk/ws/files/75407360/Environmental_hypotheses_in_Cyprus.pdf

# Main findings
Inductive data mining, undertaken as a preliminary exploratory step, narrowed the focus onto Cyprus and, upon closer examination, identified FDI and GDP as noteworthy variables to investigate. The research question, derived from these findings, marked the start of a deductive process to validate or invalidate the three given hypotheses. Employing ARDL bounds and Granger causality tests, the authors sought to identify correlation among the variables and thereby confirm or reject the presence of these hypotheses. Prior to testing, certain assumptions were established:

1. a significant, positive correlation between FDI and CO2 emissions would indicate the presence of a pollution haven
2. a significant, negative correlation between FDI and CO2 emissions would indicate the presence of a pollution halo
3. a significant, positive correlation between GDP and CO2 emissions, in tandem with a significant, negative correlation between GDP2 and CO2 emissions would support the EKC.

In addition to the above-mentioned variables, net imports (a proxy for trade openness) and energy consumption were also included as control variables, as they were assumed to have a demonstrated effect on environmental degradation. The ARDL model results did confirm significant correlations of GDP and GDP2 with CO2 emissions, but inverse to the EKC’s theoretical proposition. Instead, this project found a negative correlation for GDP, but a positive correlation for its square, thereby identifying a U-shaped curve. This means that CO2 emissions decrease with GDP growth until a certain turning point, after which CO2 emissions increase with GDP growth. This finding supports the scale effect theory, which postulates that as economic production increases, so does demand for natural resources, which in turn results in increased environmental impact.

Furthermore, the energy consumption variable also demonstrated a significant, positive relationship with CO2 emissions. This signifies that Cyprus’ increasing energy consumption, which runs alongside its economic growth, could have grievous consequences environmentally if changes are not made. Cyprus’ growing tourism sector, for instance, consumes high amounts of energy. A transition to cleaner energy could mitigate this and lead to a shift from the current scale effect to the actualization of the technique effect. Thus, policy initiatives encouraging the development of sustainable tourism would be beneficial by supporting one of Cyprus’ critical economic sectors, while simultaneously reducing environmental harm. Overall, however, the rejection of the EKC hypothesis highlights the potential for climate regulations to have a negative impact on the Cypriot economy and its development. Thus, further research is required, e.g. on a micro-level or on individual pollutants, in order to adopt more precise, effective policies.

Concerning the pollution haven/halo hypotheses, the unrestricted ARDL model results could not identify a significant relationship between FDI and carbon emissions, thus preventing the confirmation of either theory. However, a Granger causality test revealed FDI as a significant Granger-cause of CO2. This suggests that Cypriot FDI inflows are still a noteworthy phenomenon requiring further investigation. The history of FDI in Cyprus is volatile, spiking erratically in the late 2000s and early 2010s. Cyprus has an open economy which is tightly interlaced with the greater global economy; this, at least in part, can account for the complex FDI behavior. Evidence of tax avoidance measures, e.g. transfer pricing issues and profit shifting, further prove this economic interdependence. The regulatory leniency perpetuates phantom FDI and has thereby created an unofficial, special economic zone of sorts with numerous bilateral double taxation treaties. MNCs, incentivized by increased profits to take advantage of this tax haven, inject empty FDI into the country which inflates reported statistics. This can interfere with statistical analyses, including those performed in this project, and cause spurious results. In combination with its tax haven status, Cyprus’ extreme energy inefficiency drastically increases emissions and could further convolute results.
 

