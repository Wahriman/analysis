<h1>READ ME</h1>

<h2>Help scripts for data analysis</h2>

<h3>Get_staircase.m</h3>

+ 1<sup>st</sup> version by Florian Kasten: <code>tACSChallenge_ImportData.m</code>
+ 2<sup>nd</sup> version by Giuseppe Di Dona: <code>tACSChallenge_AnalyzeStaircase.m</code>
+ 3<sup>rd</sup> version by Wahriman Andrade de Araújo: <code>Get_staircase.m</code>

The new script adds the used Base Brightness (variable <code>a</code> in the tACS Challenge GUI) and the Target Brightness (variable <code>b</code> in the tACS Challenge GUI).

**Output example:**
<img width="1344" height="808" alt="sub-L19_S01_StaircaseResults_DATE_15_09_2026_12_45_31" src="https://github.com/user-attachments/assets/c4d4a512-7025-474f-b1a0-b8e41aef859a" />

<h3>swap_left_right_buttons_press.m</h3>

This script swaps the values of the variables <code>LeftButton</code> and <code>RightButton</code> inside the designated block files (e.g., <code>sub-L19_S01_B1_Sh_2026_03_03_14_32_06.tsv</code>).

**Why?**

The button box used by lab 19 had a malfunctional right button. As a solution, during the data collection, we turned the button box in 180° allowing the participant to continue using their dominant hand (right hand) while pressing the assigned left button. In turn, during the data analysis, to avoid the miss assumption that the data was collected with only left-handed participants, we used a script to fix the participants handiness based on the demographic information provided by the them. 
