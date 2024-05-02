Last updated 2. 29. 2024


# Material 
- Concanavalin A beads (POLYSCIENCES INC, Cat #: 86057-3)

- Bead binding buffer (okay up to 6 months at 4C)

|Component| Final| 100mL | 
|---------|----------|--|
|1M HEPES-KOH pH 7.9|20mM HEPES|2000uL|
|3M KCl| 10mM KCl|333uL|
|1M CaCl2|1mM CaCl2|100uL|
|1M MnCl2|1mM MnCl2|100uL|
|H2O| .|97.467mL|

- Wash buffer (okay up to 6 months at 4C)

|Component| Final| 100mL | 
|---------|----------|--|
|1M HEPES-KOH pH 7.9|20mM HEPES|2mL|
|5M NaCl| 150mM NaCl|3mL|
|0.5M EDTA pH 8|2mM EDTA|400uL|
|20% Triton-X 100|0.05% Triton-X|250uL|
|H2O| .|97.35mL|

- Wash buffer w/o EDTA (okay up to 6 months at 4C)

|Component| Final| 100mL | 
|---------|----------|--|
|1M HEPES-KOH pH 7.9|20mM HEPES|2mL|
|5M NaCl| 150mM NaCl|3mL|
|20% Triton-X 100|0.05% Triton-X|250uL|
|H2O| .|97.75mL|

  > (I think) Cut&Run needs HEPES based buffer, instead of PBS, as addition of Ca causes precipitation of phosphates? in PBS.

- Antibody binding buffer<br>
Add 300mg of BSA to 10mL of wash buffer (w/ EDTA). Aliquot and store at -20C. 

- 2X STOP buffer (okay up to 6 months at 4C)

|Component| Final| 10mL | 
|---------|----------|--|
|5M NaCl| 340mM NaCl|720uL|
|0.5M EDTA pH 8|20mM EDTA|400uL|
|0.2M EGTA pH 8|4mM EGTA|200uL|
|H2O| .|8680uL|

Add RNase (10mg/mL, 200X, final 50ug/mL) fresh


# Day1 - attach ConA beads to cells, incubate with antibodies 

1. Take Concanavalin A-coated beads - 10uL per each sample (e.g. take 120uL for 12 samples)
    > 10uL for 100~200K cells. But I think this is in excess. <br>
    Empirically optimize the amount of beads by checking supernatant after bead binding to cells.

2. Wash 2X with 1mL bead binding buffer

3. Resuspend in a volume of bead binding buffer equal to the volume of bead slurry.

<b> [Binding cells to beads] </b><br>
NOTE: Treat cells and cell+beads gently. Not too long magnet binding. Using wide-bore tips, etc. 
 
4. Obtain ~100,000 single cell suspensions. Fix with 1% formaldehyde for 1min.
 
5. Quench by directly adding the same vol. 1M Tris to a final concentration of ~500mM. Incubate ~5 min.

6. Cfg. in FACS tubes in 600G for 6min. Remove supernatant, leaving ~100uL.
    > Higher Cfg because it is fixed (a. cells now already dead, b. needs higher cfg to pellet)
  
7. Resuspend cells in the wash buffer (0.05% Triton-X, (!) NO EDTA)  
    > Typically, you would wash multiple times, but to avoid losing cells, I do not wash and go to the next steps.
  
8. Add bead slurry cells and rotate 5-10min at room temp.
    > I prefer occasional flipping than rotating.

Example image of spermatocytes bound ConA beads<br>
![ConA bound spermatocytes](https://github.com/jongminkmg/Storage/blob/main/ConA_Scytes_23-0905.jpg?raw=true "ConA bound spermatocytes")

<b> [Bind primary antibodies] </b><br>

9. Wash/incubate once with antibody buffer (wash buffer + EDTA + BSA)

10. Divide into aliquots in 2mL tubes, one for each antibody to be used.
 
11. Add 100uL of antibody buffer with each antibody. Incubate O/N at 4C.
    >  Many protocol says rocking or rotating. I leave them stationary. If possible, occasional flicking when I use 2mL tubes.
    > If I use PCR strips, cannot mix by flicking. I occasionally rotate (I prefer using 2mL tubes, even if I cannot use multi-channel). 

# Day2 - pA-MNase binding, digestion, release & collection of targets

<b> [Bind secondary antibodies] (skip if no mouse antibody was used)] </b> <br>

12. Wash beads with 1mL wash buffer with EDTA
 
13. Add 100uL of antibody buffer with appropriate secondaries. Incubate >2hr at 4C.

<b> [Bind Protein A-MNase fusion protein] </b> <br>

NOTE: If you leave beads+cells on magenet too long, beads+cells can aggregate. Very quick (5 sec) should be enough for most type of magnets.

14. Wash beads with wash buffer (w/ EDTA, 2X)
 
15. Add pA-MNase to a final conc. 500ng/mL in wash buffer with BSA, EDTA 100uL 
    > Used Sharon single (Ni-alone) purified pA-MN (0.5mg/mL) in 1000X (Final 500ng/mL).
    > Again, the amount of pA-MN needs empirical optimization.
 
16. Incubate 2 hr at 4C.

17. Wash 2X with 1mL wash buffer and then final wash buffer w/o EDTA (~200uL wash when using PCR strip)
 
<b> [Targeted digestion] </b> <br>

* Before starting, equilibrate sample tubes, and digestion solution to 4C.
 
18. Resuspend beads with 100uL wash buffer (w/o EDTA) + 4mM CaCl2
    > I use 4mM CaCl2 instead of suggested 2mM CaCl2, because my buffers had EDTA throught till right before the digestion.<br>
 
19. Incubate 2 hr at 4C.
 
* Warm up 2X STOP solution to 37C.
 
20. Add 100uL 2XSTOP and mix by gentle tapping (or up&down when using PCR strip)
 
 
<b> [Target chromatin release] </b> <br>

21. Incubate 10 min at 37C oven to release CUT&RUN fragments from the insoluble chromatin.
 
<b> [DNA extraction] </b> <br>

22. Cfg 5min at 4C >16000g and place on magnet stand.
 
23. Supernatant: add 10% SDS (final 0.1%), 2uL Proteinase K (20mg/mL)

24. Incubate 70C O/N for ProK / de-crosslinking

25. Purify DNA with Qiagen DNA purification kit
    > When I did phenol-chloroform precipitation, residual salts seemed to inhibit enzymatic reactions in library prep. <br>
    > At some point, I compared >2X SPRI vs. column (Qiagen) based purification, and realized column was better in retaining <100bp fragments. So column based purifications.
