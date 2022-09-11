# Micron/nano-scale fabrication Projects

The fabrication processes are usually performed using either the conventional techniques or Substrate Selective Epitaxy method (SSE).

## Conventional fabrication technique

The conventional fabrication techniques involve postdeposition patterning including either wet or dry etching processes.

### 1. Dry etching

In this technique, the epitaxial layer is spin coated with a photoresist mask of [AZ1512](https://www.microchemicals.com/products/photoresists/az_1512_hs.html "AZ1512") or [PMMA](https://www.allresist.com/resist-wiki-uv-structuring-of-pmma-resists/ "PMMA") (polymethyl methacrylate).
Photoresist is a light sensitive material which has two types, positive and negative, that react very differently when exposed to UV light. In negative lithography, the exposed area stabilizes the photo resist, whereas the unexposed portion remains soluble while in positive lithography, the exposed UV areas of the resist are soluble in the developer.

For direct-draw maskless photolithography, a pattern is defined using [Graphic](https://www.graphic.com "Graphic") or any other drawing program. A few of these masks are shown here for various projects. Then the desired mask is precisely aligned for the photolitography process, where a UV light is shone on the photoresist.

The photolitography is performed after a careful analysis of the best exposure time and focus with exposure tests. In the next step, samples are etched using Ion Beam Milling system or plasma etching at room temperature. In some cases, if the etching process is too long and there is a risk of overheating, a cooling stage of liquid nitrogen is used to cool the sample. The lift-off process is done after the milling.

<p align="center">
<img src="standard.png" width="500" height="200">
</p>

### 2. Wet etching

In wet etching method, the acid is used to etch the parts of the sample that are not cover by photoresist. The choice of acid depends on the epitaxial layer. For some materials, high-corrosive acids like [HF](https://en.wikipedia.org/wiki/Hydrofluoric_acid "HF") are used, while Nitric Acid [$HNO_{3}$](https://en.wikipedia.org/wiki/Nitric_acid "HNO3") could be sufficient for others. As wet etching exposes the epitaxial layer to harmful chemicals, it is not recommended in most cases. Along with other methods such as Fourier transforms from X-ray diffraction or AFM, wet etching after photolitography can be used for measuring layer thickness using [profilometer](https://en.wikipedia.org/wiki/Profilometer "profilometer").

---

## Substrate Selective Epitaxy technique (SSE)

Unlike the conventional fabrication methods, in the substrate selective epitaxy (SSE) technique the epitaxial layer is preserved by patterning the substrate prior to the deposition, protecting the layer from harmful chemicals and overheating caused by milling process.
The SSE technique can be done in two different ways.

### 1. SSE-Trench

This method does not involve ion milling. As is schematically illustrated in the Figure 2, the substrate is spin coated with a photoresist followed by the photolithography to obtain the desired pattern. Then, a thin amorphous layer is sputtered on the sample using [RF sputtering](https://www.tn.ifn.cnr.it/facilities/rf-sputtering-facility/rf-sputtering-principles "RF") or pulsed laser deposition [(PLD)](https://en.wikipedia.org/wiki/Pulsed_laser_deposition "PLD"). After the lift-off, the amorphous layer will only remain where we do not want to grow epitaxial layers. In the last step, the epitaxial layer is deposited using pulsed laser deposition (PLD).

<p align="center">
<img src="SSE.png" width="500" height="200">
<br>
    <strong>Figure 2:</strong> Substrate selective epitaxy with trench method.
</p>

### 2. SSE-Ridge

The SSE method can be performed in another way in which it includes a gentle ion milling. In this method, if the ion milling step is long, a cooling stage of liquid Nitrogen can be used to prevent the sample from heating. This method can be performed using two different ways, which are explained with the help of Figure 3, as follow:

a) In the first procedure, the substrate is milled after patterning it. Then, a thin amorphous layer is sputtered on the sample using RF sputtering at room temperature. In this technique, the substrate and the amorphous layer will be in the same level. After lift-off, some parts of the substrate are covered by the amorphous mask which prevent epitaxial growth. In the final step, the epitaxial layer is deposited on the sample.

b) In the second procedure, an amorphous layer is grown on a bare substrate, followed by spin coating of the photoresist on it. After patterning the substrate, the amorphous layer is etched using ion milling down to the substrate. Once the lift-off is done, the epitaxial superconducting layer is grown on the sample. In this project, we used $SiO_{2}$ and $Al_{2}O_{3}$ as amorphous layers.

<p align="center">
<img src="SSE-milling.png" width="500" height="340">
<br>
    <strong>Figure 3:</strong> Schematic of the SSE device preparation procedure using ridge technique.
</p>

---

## Fabrication of Hall bar pattern

Variety of patterns have been examined in different projects. The Hall pattern was one of the most commonly used patterns to explore the electrical transport properties. It consists of a six-probe Hall bar as shown in Figure 4.

This pattern enables us to measure the longitudinal and transverse voltage at the same time as well as IV curve.
As is shown, the current is injected at I+ and the transverse ($\rho_{yx}$) and longitudinal ($\rho_{xx}$) voltage can be measured using two facing and adjacent pads, respectively.

<p align="center">
<img src="SSE-graph.png" width="500" height="150">
<br>
    <strong>Figure 4:</strong> The Hall effect pattern fabrication process.
</p>

The pattern of Hall bar we have used is shown in Figure 5. The patterns can be designed using Graphic software or paint with the bmp format.

<p align="center">
<img src="Masque-Hall.bmp" width="400" height="200">
<br>
    <strong>Figure 5:</strong> The Hall effect pattern.
</p>

The final device which contains the Hall effect pattern is shown in Figure 6.

<p align="center">
<img src="hall-sample-lab.png" width="400" height="200">
<br>
    <strong>Figure 6:</strong> (a) The Hall effect pattern after the photolithography prior to the epitaxial deposition. (b) The final sample is wired to the PPMS puck.
</p>

---

## Fabrication of micron-scale wires and rings

The conventional photolitography and substrate selective epitaxy method are both employed to fabricate micron-scale wires and rings.
Figure 7 shows the pattern that we used in which the wires with different widths of 5, 10 and 15 $\mathrm{\mu m}$ are located at the top and three rings with diameters of 20, 25 and 30 $\mathrm{\mu m}$ and the width of 1 $\mathrm{\mu m}$ are placed at the bottom. The LSAT and STO substrates were used for this project.
The fabrication of rings and wires were done using the ridge method with a gentle ion milling after the amorphous layer deposition.
The superconducting wires are shown in Figure 7.

<p align="center">
<img src="pattern-wires.png" width="500" height="300">
<br>
    <strong>Figure 7:</strong> The pattern of micron-scale wires and rings.
</p>

<p align="center">
<img src="ring-pcco.png" width="500" height="180">
<br>
    <strong>Figure 8:</strong> The pictures of three different designed micron-size superconducting rings (after PLD deposition) with diameters of a) 20, b) 25 and c) 30 $\mu m$.
</p>

<p align="center">
<img src="rings-afm.png" width="500" height="240">
<br>
    <strong>Figure 9:</strong> AFM images of the rings after depositing the superconducting layer.

---

## nano-scale size superconducting ring

In order to reduce the ring size to nano scale, the electron-beam litography (EBL) is performed in collaboration with the engineering department. In this project, two nano-scale rings with the diameter of 1 micron and the widths of 100 nm and 250 nm were designed. The pattern contains of four rings, two for each ring size (Figure 10). A different type of resist ([CSAR](https://www.allresist.com/portfolio-item/e-beam-resist-ar-p-6200-series-csar-62/ "CSAR")) has been used to fabricate nano-scale rings, with the use of [Anisole](https://pubchem.ncbi.nlm.nih.gov/compound/Anisole "Anisole") for lift-off process.

<p align="center">
<img src="Masque-4-Wires-rings.png" width="300" height="300">
<br>
    <strong>Figure 10:</strong> Nano-scale rings pattern
</p>

The final device is displayed in Figure 11. From left to right:

- The sample just after the epitaxial deposition.
- After putting indium contacts on the pads for measurement of the transport properties.
- After wiring the sample to the [PPMS](https://www.qdusa.com/products/ppms.html "PPMS") puck with gold wires.

<p align="center">
<img src="nano-rings.png" width="500" height="280">
<br>
    <strong>Figure 11:</strong> Images of the nano-scale rings after growing the epitaxial spuerconducting film
</p>

AFM images of the nano superconducting ring are shown in Figure 12.
The pattern in left is after developing the pattern on the substrate and the one in right is after the deposition of the amorphous layer. Figure 13 is a AFM image after deposition of superconducting layer.

<p align="center">
<img src="resin-ring.png" width="500" height="200">
<br>
    <strong>Figure 12:</strong> AFM images of the nano-scale rings after patterning the substrate and sputtering the amorphous layer.
</p>
<p align="center">
<img src="nanoafm.png" width="500" height="200">
<br>
    <strong>Figure 13:</strong> AFM images of the nano-scale rings after depositing the superconducting layer.
</p>

A different pattern has been also used to fabricate the nano-scale ring. Figure 14 is SEM images of the nanorings on a Si substrate.

<p align="center">
<img src="third-ring-SEM.png" width="500" height="250">
<br>
    <strong>Figure 14:</strong> SEM images of the nanorings on a Si substrate
</p>
