# Material 
- Freshly dissociated single cells in PBS
- Zombie Green Fixable Viability Kit (BIOLEGEND INC, 423111)
- 10% BSA in PBS frozen aliquots
- Cold PBS, Cold PBS + 2mM EDTA<br>

[Antibodies]
- Undifferentiated spermatogonia: (THY1+ & ITGa6+) or (THY1+ & ITGb1+) or (THY1+)
   - THY1 (CD90.2 Antibody, anti-mouse, APC (130-123-783)) | Use 1:50
   - ITGa6 (CD49f Antibody, anti-human/mouse, PE, REAfinity™ (130-119-807)) | Use 1:50
   - ITGb1 (CD29 Antibody, anti-mouse, PE (130-102-602)) | Use 1:10
- Differentiating spermatogonia: (THY1- & cKIT+) or (cKIT+)
   - CD117 Antibody, anti-mouse, PE (130-122-937) | Use 1:500
(All from Miltenyi Biotec)
   > FACS antibodies vary in their stock conc. a lot. Check carefully and optimize for the right conc. 

# Protocol 

Last updated: 5. 18. 2023

1. Cfg. 400G, 6min

2. Resuspend Zombie Green in PBS (1uL ZG / 1mL PBS). Incubate at RT for 20~30 min.
    > About ~10 million cells / 1mL ZG+PBS range <br>
    > ZG is an amine-reactive dye, so I do room temp as I worry reactivity will be lower at 4C (and protocol says room temp).<br>
    > I use Zombie 'Green' because the Melody sorter I use does not have 405 laser, so could not use HOECHST for viability.<br>
    > In my experience, most sorting okay w/o excluding 'dead/ZG+' cells, but I tend to sort signficant amount of random crap w/o ZG step.

3. Wash by directly adding ~45mL PBS + 0.5% BSA
    > Relatively high percentage of BSA to 'quench' Zombie Green <br>
    > (!) Note: I try to minimize 'centrifuge/remove supernatant' cycles, becuase I lose cells every Cfg cycles. <br>
    >   So I directly add excess amount of wash buffer into existing cell suspension to wash.

4. Cfg. 400G, 6min
 
5. Resuspend in (x) mL with each antibody dissolved in PBS EDTA + 0.1% BSA. Incubate at 4C for 30-60min.
    > About ~10 million cells / 1mL antibody solution <br>
    > I was told cell surface dyes need to be stained at 4C, otherwise they will be endocytosed. Not sure how much this matters. <br>
    > I get higher proportion of stained cells when incubated at least for 60min, so I usually do 60 min incubation. 

6. Wash by directly adding cold PBS EDTA up to 50mL

7. Cfg. 400G, 6min

8. Resuspend with cold PBS EDTA 0.1% BSA. To have ~10million/mL cells.

9. Analyze or sort.

### Note for sorting. 

- Pre-coat all plastic surface with ~0.1% BSA PBS to prevent cell loss.

### Example profile & result 

- From one adult mouse (two testes), I usually get 30~50M cells. Not all of these will be sorted as I lose them during staining/washing. 
- From there, I get 300-400K cKIT(+) cells or 30-40K THY1(+) cells.

![THY1 profile, 1,000,000 events](https://github.com/jongminkmg/Storage/blob/main/THY1.png?raw=true "THY1 profile, 1,000,000 events")
<br> THY1&ITGa6 profile, 1,000,000 events, ~0.2% of total 'events' (not cells) <br><br>

![THY1 result](https://github.com/jongminkmg/Storage/blob/main/THY1_cells.png?raw=true "THY1 result")
<br> THY1&ITGa6 result<br><br>

![cKIT profile, 100,000 events](https://github.com/jongminkmg/Storage/blob/main/cKIT.png?raw=true "cKIT profile, 100,000 events")
<br> cKIT profile, 100,000 events, 2~4% of total 'events' (not cells)<br><br>

![cKIT result](https://github.com/jongminkmg/Storage/blob/main/cKIT-1_cells.png?raw=true "cKIT result")
<br> cKIT result<br><br>

