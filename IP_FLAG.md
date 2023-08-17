Last updated: 8. 17. 2023

# Material 
- Sigma Millipore, Anti-FLAG M2 Magnetic Beads (Cat #: M8823)
- Sigma Millipore, FLAG Peptide (Cat #: F3290)
 

# Equibilrate beads with binding buffer
  > M2 beads are already FLAG-antibody attached, so no 'antibody conjugation to beads' step.

1. Prepare lysis buffer (below example for ribosome purification, note MgCl2 and RNasin)

|Component| Final| 1mL | 20mL|
|---------|----------|--|--|
|1M Tris-HCl, pH 7.5|50mM Tris-HCl, pH 7.5|50|1000|
|5M NaCl| 135mM NaCl|27|540|
|1M MgCl2|5mM MgCl2|5|100|
|50% Glycerol|10% Glycerol|200|4000|
|1M DTT|1mM DTT|1|20|
|10% Igepal|1% Igepal|100|2000|
|25X cOmplete protease inhibitor|1X cOmplete protease inhibitor|40|800|
|RNasin|1X RNasin|recommended amount||
|H2O| .|577|11540|
> I have used Tris pH btw 7.4~8.0, and within that range, no major differences.<br>
> Do not use EDTA as we need MgCl2

[below example for 4 IPs]
1. Take 100uL FLAG-magenetic beads (25uL/IP)
> Mix beads well before taking an aliquot.
> M8823, 0.6ug/uL binding capacity. Assume half of 25uL is bead vol. Then you can pull down 7.5ug of target protein.

2. Use magnet to attract beads and remove the supernatant.
   
4. Immediately replace liquid (before beads dry) with 500uL lysis buffer.
   
6. (Magnet, aspirate and wash with another 500uL lysis buffer) x 2
   
8. Store beads in the lysis buffer at 4C before stating IP incuation.
  
# Immunoprecipitation
 
> Making a good lysate (solubilizing your protein of interest) is the crucial step. It can be a balancing act of detergents, salt concentration, and physical force (homogenization, sonication, freeze-thaw) to maintain protein-protein interaction while breaking up cellular components for solubilization. 

20. Methods for homogenization.
    - Cell pellets, embryos, or very soft tissues will be readily dissolved
    - Soft tissues, you can try homogenizing using blue pestles (fitting 1.7mL test tubes) or going through successive 22G->25G needles (up&down about 10 times).<br>
      Instead of needles, you can also use a 1mL sized Dounce homogenizer.
    - Hard tissues, first grinding in LN2 and then homogenizing, work the best for me.

21. Add lysis buffer (See above recipe. Add protease inhibitor).
    - 30-50uL per 1mg tissue (1mg/30-50uL = 20-33ug/uL range. But since it's not' dry protein weight', actual conc. will be far lower) 
    - 10-25uL per 1M cells (assuming 50ug total protein/1M cells, to get 2-5ug/uL range lysate)
      > Lyse first try with 1mL of lysis buffer per testis

22. Homogenize with your favorite method.
    > Mechanically disrupt testis with a syringe (1mL syringe and a 21/23/25G sequential needles)
 
23. Incubate lysate at 4C for 30 minutes on a rotator.
    > Not sure if this step is absolutely necessary. 
 
24. Spin the lysates down at max speed for 10 minutes at 4C. Take supernatant. 
    > If you are making lysates for the first time, do not throw away pellets. Check with Western later to see if you are not losing your protein in the pellet. 

26. Measure concentration using Bradford Assay (Blank, 5, 10, 15, 20). Use 1~2uL. 
 
27. Take out ~5ul (~30ug lysate, ~2% of IP) of lysate for Western. (INPUT). Freeze.
 
28. Preclear the cell lysate: Add lysates to the washed beads (w/o Ab), and incubate on the rotator for 30min @ 4C.

29. Block the antibody-conjugated beads in 3% BSA PBSt for 30 min @ 4C. 
 
30. Using magnet, remove the supernatant from antibody-conjugated beads.
 
31. Take pre-cleared lysates after magnet separation.
 
32. Add lysates to the blocked antibody-conjugated beads and incubate for 4 hrs to O/N on rotator @ 4C

 
<b>Post incubation:</b><br>
Elution buffer
|Component| Final| 1mL |
|---------|----------|--|
|1M Tris-HCl, pH 8.0|50mM Tris-HCl, pH 8.0|50|
|10% SDS| 1% SDS|100|
|0.5M EDTA, pH 8.0| 5mM EDTA, pH 8.0|10|
|25X cOmplete protease inhibitor|1X cOmplete protease inhibitor|40|
|H2O| .|800|

33. Turn heat block to 70C. 
    > I like to use oven because solution evaporates to the tube tops in heat blocks.

34. Using magnet, collect supernatant. Save as 'flow through' for Western blot later. 
 
35. Wash. Immediately replace the depleted supernatant with 1mL cold lysis buffer and incubate beads on rotator for 5 min @ 4C
Wash with lysis buffer.
 
36. Repeat wash 2x with 1mL lysis buffer wash (don’t spin between washes, use magnet!)
 
37. Resuspend dynabeads in 100uL lysis buffer and transfer to new tube.
    > This step is supposedly not to collect contaminants sticked to the tubes. Not sure if this is that helpful. 
 
38. Add 15~50 uL fresh elution buffer to the Dynabeads (made fresh + protease inhibitors) 
 
39. Vortex lightly briefly. 
 
40. Incubate bead in elution buffer @ 70C for 30 min. with frequent (every 5 min) light vortexing. 
 
41. Spin tubes at RT for 10 seconds to take evaporated liquid down. 
 
42. Hold beads in place with magnet and transfer all the supernatant to a new tube. This is your IPed material.


# TCA precipitation 

> Sometimes you want to load all the IPed material for Western or mass spec. TCA precipitation can effectiverly precipitate protein to reduce sample volume. 
 
1. Add 50uL of TCA to 200uL eluate (20% TCA final)
 
2. mix and incubate >1hr in 4C.
 
3. 14K 15min spin
 
4. -20C acetone wash (1mL) (– leave on ice 5min before cfg.)
 
5. remove acetone, dry, resuspend in 13uL 1X western loading buffer.
    > You can also submit TCA-precipiated pellet (pellet may not be visible) to mass spec facility.
