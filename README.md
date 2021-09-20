# NATASHA: magNetoelAsTic beAm with biStable beHAvior

To download the vibration dataset of the benchmark NATASHA, please fill the form:
https://forms.gle/cmH4P926XowkseGC7

__________________________________________________________________________________________________
# Description

NATASHA is a dataset of vibrations measured by a magneto-elastic beam composed of a clamped beam interacting with two permanent magnets in a bistable configuration. The experimental setup is formed by a cantilever steel beam with dimensions of 150$\times$15$\times$ 0.65 mm. The beam-free end is distant from 5 mm to two magnets placed 65 mm one to the other.

<img src="bancada.jpg " width="80%">
<img src="esquema.jpg " width="80%">

The setup includes the following:

 <li>  Tira shaker TV51120-M</li>
	 <li>  Polytec OFV-525/-5000-S modular laser vibrometer</li>
	 <li> Dytran load cell model 1022V (IEPE force sensor)</li>
 <li>  m+p VibPilot acquisition system</li>

The shaker was attached 25 mm distant from the clamp. Velocity was measured through the laser vibrometer in the free end of the beam. All signals were sampled with 1024 Hz.

To characterize the baseline condition of the structure ("healthy" state), two different input signals were used: chirp and mono-harmonic sine:

  <li>  Chirp input from 5 to 30 Hz, with 8192 samples and input levels of: 0.01, 0.05, and 0.10 V. Each test was repeated 10 times to check repeatability</li>
   <li>  Sine input with a frequency of 20 Hz, with 81920 samples and input levels of: 0.01, 0.05, and 0.10 V</li>
   
This data is presented in the file "identificationdata.mat" which has two MATLAB structures named "data\_chirp" and "data\_sine". The variables contained in both variables are presented in Table 1.

<img src="table1.jpg " width="80%">

The gap between the free end of the beam and the magnets was modified from 5 mm up to 17.5 mm to simulate a structural variation. This change in the distance is expected to change both the linear and nonlinear behavior of the system. Table 2 shows the structural states simulated in the system.

<img src="table2.jpg " width="80%">

__________________________________________________________________________________________________
# Authors

  <li>Cristian Hansen (IFMT) </li>
  <li>Sidney Bruce Shiki (UFSCar)</li>
  <li>Samuel da Silva (UNESP) </li>
  
  __________________________________________________________________________________________________
# How to cite

The data are still available for non-commercial research under the following terms: (i) the SHM Lab at UNESP/Ilha Solteira should be acknowledged as the source of the data; (ii) in publications, relevant publications by members of the SHM Lab at UNESP/Ilha Solteira should be cited; (iii) this benchmark should be cited as NATASHA.

This dataset was used in these publications:

<li>Hansen, C.  Caracterização experimental de sistemas mecânicos com comportamento não-linear. M.Sc. Dissertation in Mechanical Engineering; São Paulo State University, Ilha Solteira/SP, Brazil, 2015, http://hdl.handle.net/11449/134107 </li><br>

If you are using a LaTeX Editor, you can cite the papers above using these BibTeX citations:

```
@phdthesis{Hansen2015,
  title={Caracterização experimental de sistemas mecânicos com comportamento não-linear},
  author={Cristian Hansen},
  year={2019},
    school ={Universidade Estadual Paulista (UNESP)}
      note= {M.Sc. in Mechanical Engineering}
  url = "http://hdl.handle.net/11449/134107",
}

```

__________________________________________________________________________________________________
# License

<img src="licenca.png" width="10%">
Creative Commons Attribution-NonCommercial-ShareAlike (CC-BY-NC-SA):

A creative commons license that bans commercial use and requires you to release any modified works under this license.

__________________________________________________________________________________________________
# Funding

São Paulo Research Foundation (<a href="http://www.fapesp.br">FAPESP</a>), grant numbers 12/09135-3, 13/09008-4 and 13/25148-0, Brazilian National Council for Scientific and Technological Development (<a href="http://www.cnpq.br/">CNPq</a>) and Brazilian Coordination for the Improvement of Higher Education Personnel (<a href="https://www.gov.br">CAPES</a>)-Finance Code 001 funded this experimental setup.

<img src="sponsors.jpg " width="50%">
