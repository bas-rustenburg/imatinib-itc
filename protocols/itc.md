# ITC of Abl and imatinib


Based on the Seeliger paper [1] and Klebe paper [2]

Hepes, Tris, and tricine buffer at pH 7.8 [2]

Seeliger uses [1]:

Buffer 20 mM Tris (pH 8.0),
100 mM NaCl,
10% glycerol, 1 mM TCEP,
5% DMSO

Abl concentration between : 10–50 mM.

Imatinib stocks DMSO were diluted 20-fold with buffer to a final concentration
of 1–500 mM.

The heat of binding was measured over the injection of 295 mL of drug in 12-mL steps
spaced 300 sec apart. (VPITC has 1 ml cell?)

## TODO

- Make recipes for 1 L of
    - 50 mM Hepes, Tris, or Tricine
    - 100 mM NaCl
    - 10% glycerol
    - 1 mM TCEP
    - 5% DMSO
    - pH 7.8




- Check whether in the future it will be possible to have the Revo make these

- Calculate scaled down volumes for Seeliger protocol (VPITC versus ITC-200)

    -
     Alternatively, use heuristic equations with the concentrations given in the Seeliger paper and see if we can find a more "optimal" setup

- Check our Imatinib stocks

- Investigate if we want to use more buffers than just the Klebe buffers

- Do we have Abl, or are we able to get Abl at a short notice?

    - Use Single mutant possibly. Did Seeliger use this - D382N


## Buffer Recipes
http://www.biomol.net/en/tools/buffercalculator.htm

### Chemicals needed:

- Tricine free acid (MW = 179.2)
    -  ~ 9 grams per liter of buffer
- Tris base  (We have Tris in stock, as base and as HCl solution)
    - ~ 6 grams per liter of buffer
- Hepes free acid (MW = 238.3)
    -  ~ 12 grams per liter of buffer
- Glycerol ( 100 mL per liter of buffer)
- DMSO ( 50 mL per liter of buffer, we have some in stock)
- TCEP (we have in stock) , ~ 0.3g per liter
- NaCl (we have in stock), 4 g per liter

#### To order:
- Tricine free acid (MW = 179.2) 
- Hepes free acid (MW = 238.3)
- Glycerol ( 100 mL per liter of buffer)


***Do we just replace water with***  
- 10% glycerol
- 1 mM TCEP (286.65 milligram per liter)
- 5% DMSO
?

### Tris:
To make 1000 ml of 0.05 M Tris (pKa=8.06) Buffer:
- pH= 7.8
- Ionic strength = 0.1 M (Ionic strength due to the buffer = 0.035M )
- Thermodynamic pKa = 8.06, Apparent pKa' = 8.17
- Temperature coefficient = -0.028 per °C
- Prepared at 25°C, used at 25 °C  

  #### Recipe:
    - Dissolve 6.057 g of Tris base (Mr = 121.14) in approx. 900 ml of pure water.
    - Add 3.798 g NaCl.
    - Titrate to pH 7.79 at the lab temperature of 25°C with monovalent strong base or acid as needed.
    - Make up volume to 1000 ml with pure water
    - Buffer will, of course, be pH 7.8 at 25°C  

  #### Alternative Recipe:
    - Dissolve 0.0351 mol of acid component
    - Dissolve 0.0148 mol of basic component
    - Add 3.798 g NaCl.
    - Make up to 1000 ml with pure water


### Hepes :
To make 1000 ml of 0.05 M HEPES (pKa=7.66) Buffer:
- pH= 7.8
- Ionic strength = 0.1 M (Ionic strength due to the buffer = 0.032M )
- Thermodynamic pKa = 7.66, Apparent pKa' = 7.54
- Temperature coefficient = -0.014 per °C
  #### Recipe:
    - Prepared at 25°C, used at 25 °C
    - Dissolve 11.915 g of HEPES free acid (Mr = 238.3) in approx. 900 ml of pure water.
    - Add 3.976 g NaCl.
    - Titrate to pH 7.8 at the lab temperature of 25°C with monovalent strong base or acid as needed.
    - Make up volume to 1000 ml with pure water
    - Buffer will, of course, be pH 7.8 at 25°C

  #### Alternative Recipe:
    - Dissolve 0.0179 mol of acid component
    - Dissolve 0.032 mol of basic component
    - Add 3.976 g NaCl.
    - Make up to 1000 ml with pure water

### Tricine :

To make 1000 ml of 0.05 M Tricine (pKa=8.26) Buffer:
- pH= 7.8
- Ionic strength = 0.1 M (Ionic strength due to the buffer = 0.015M )
- Thermodynamic pKa = 8.26, Apparent pKa' = 8.14
- Prepared at 25°C, used at 25 °C
- Temperature coefficient = -0.021 per °C

  #### Recipe:
    - Dissolve 8.959 g of Tricine free acid (Mr = 179.2) in approx. 900 ml of pure water.
    - Add 4.946 g NaCl.
    - Titrate to pH 7.79 at the lab temperature of 25°C with monovalent strong base or acid as needed.
    - Make up volume to 1000 ml with pure water
    - Buffer will, of course, be pH 7.80 at 25°C

  #### Alternative Recipe:
    - Dissolve 0.0344 mol of acid component
    - Dissolve 0.0155 mol of basic component
    - Add 4.946 g NaCl.
    - Make up to 1000 ml with pure water



## Citations

1.  > **cHigh yield bacterial expression of active c-Abl and c-Src tyrosine kinases**

    >Seeliger MA, Young M, Henderson MN, Pellicena P, King DS, Falick AM, Kuriyan J.
    > [fulltext](http://www.ncbi.nlm.nih.gov/pmc/articles/PMC2253236/pdf/0143135.pdf)

2. > **Chasing Protons: How Isothermal Titration Calorimetry, Mutagenesis, and pKa Calculations Trace the Locus of Charge in  Ligand Binding to a tRNA-Binding Enzyme**

    > Manuel Neeb, Paul Czodrowski, Andreas Heine, Luzi Jakob Barandun, Christoph Hohn,
Francois Diederich, and Gerhard Klebe
    > [fulltext](http://pubs.acs.org/doi/pdf/10.1021/jm500401x)
