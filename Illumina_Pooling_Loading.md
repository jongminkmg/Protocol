Last updated 9. 18. 2023 

# Pooling

1. Make a pooling table ([example link](https://docs.google.com/spreadsheets/d/1clMWukv5wbXT6UzbKcdi_ZC2u8-hLJZefsZNFqknh0g/edit?usp=sharing)).
    > Try to use at least 2uL from each for pipetting accuracy.

2. Pool samples

# Measure 'sequenceable' library conc. using KAPA qPCR kit

1. Dilute pooled library to have concentration below 20pM
    > Usually 1/1000

2. Use [KAPA Library Quantification Kit for Illumina Platforms](https://sequencing.roche.com/us/en/products/group/kapa-library-quantification-kits.html) (KK4824, Roche 07960140001) 
    > I use 1/2 reaction volume (no ROX)
    
|Component| vol| e.g. 12x (x1.1) | 
|---------|----------|--|
|KAPA SYBR FAST qPCR master mix (2X) + Primer Premix (10X)|6uL|79.2uL|
|PCR grade water|2uL|26.4uL|
|Total volume|8uL|-|

3. Calculate pooled libarary concentration (see 'KAPA quantify' section of the [pooling table](https://docs.google.com/spreadsheets/d/1clMWukv5wbXT6UzbKcdi_ZC2u8-hLJZefsZNFqknh0g/edit?usp=sharing)).

# Prepare sequencing run at Illumina Basespace

1. Login at [Basespace](https://basespace.illumina.com) with your credentials.

2. Go to 'RUNS' and click 'NEW RUN' -> 'RUN PLANNING'.

3. Prepare the run as screenshots below

![1](https://github.com/jongminkmg/Storage/blob/main/Basespace1.png?raw=true "Basespace 1")
Next<br><br>
![2](https://github.com/jongminkmg/Storage/blob/main/Basespace2.png?raw=true "Basespace 2")  
Next<br><br>
![3](https://github.com/jongminkmg/Storage/blob/main/Basespace3.png?raw=true "Basespace 3")
Above is for 100bp run (+ 38bp extra given)<br>
Next<br><br>
![4](https://github.com/jongminkmg/Storage/blob/main/Basespace4.png?raw=true "Basespace 4") 
...<br>
![5](https://github.com/jongminkmg/Storage/blob/main/Basespace5.png?raw=true "Basespace 5")
Save as planned. 
<br><br>

# NextSeq 2000 run

Note, a very good protocol is on [Penn Vet center](https://protocols.hostmicrobe.org/nextseq-2000). Below is my simplified protocol. 

1. Thaw the cartridge on the bench (in the foil) at least 9 but no more than 16 hours. Then move to 4C till 30 minutes prior to sequencing.

2. Final dilution: dilute your library 600pM with RSB
    > RSB has 0.1% Tween 20, which prevents DNA loss by adhering to plastic surface.<br>
    > It's been okay for me *not* using LoBind tubes.

3. Equilibrate the cartridge and the flow cell to room temp. 30 minutes prior to sequencing.

4. Go to NextSeq machine. Log in with your Basespace credentials. Follow instructions.

5. Open the cartridge and invert the cartridge 10 times to mix reagents.

6. Open to flow cell and assemble it into the cartridge.

7. Load 20uL of diluted library to the cartridge.
