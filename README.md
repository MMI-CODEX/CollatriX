<h1 align="center">CollatriX 2.0.1</h1>


  <p align="center">
    User-Friendly Photogrammetry Software
    <br/>
    <br/>
    <a href="https://github.com/MMI-CODEX/CollatriX/blob/master/CollatriX_v2-0-1_manual.pdf"><strong>Read the Manual »</strong></a>
    <br/>
    <br/>
    <a href="https://github.com/MMI-CODEX/CollatriX/issues">Report Bug</a>
    .
    <a href="https://github.com/MMI-CODEX/CollatriX/issues">Request Feature</a>
  </p>
</p>
<div align="center">

[![DOI](https://joss.theoj.org/papers/10.21105/joss.02328/status.svg)](https://doi.org/10.21105/joss.02328)
 [![DOI](https://zenodo.org/badge/243385218.svg)](https://zenodo.org/badge/latestdoi/243385218)
![Downloads](https://img.shields.io/github/downloads/MMI-CODEX/CollatriX/total) 
![Contributors](https://img.shields.io/github/contributors/MMI-CODEX/CollatriX?color=dark-green) 
![Stargazers](https://img.shields.io/github/stars/MMI-CODEX/CollatriX?style=social) 
![Issues](https://img.shields.io/github/issues/MMI-CODEX/CollatriX) 
![License](https://img.shields.io/github/license/MMI-CODEX/CollatriX) 

</div>

## Table Of Contents

* [About the Project](#about-the-project)
* [Getting Started](#getting-started)
* [Usage](#usage)
* [Attribution](#attribution)
* [Contributing](#contributing)
* [License](#license)
* [Authors](#authors)

## About The Project
The path from measuring an image to having a clean dataset of measurements can often be complicated. CollatriX was designed to help.

This all started with the simple need for a tool to collate the csv outputs from [MorphoMetriX](https://github.com/MMI-CODEX/MorphoMetriX-V2)  into one large single data frame containing the image, animal ID, measurements, and notes.

But calculating accurate measurements requires more. CollatriX V2 now has several additional tools to bring in altitude measurements from a laser altimter by helping accurately correct timestamps and merge datasets.

CollatriX can also calcuate several body condition metrics for cetaceans.
 
![alt text](https://github.com/MMI-CODEX/CollatriX/blob/701dc27b8ee2c76bafa407235a2a3e94bc82cd38/CollatriX_Workflow.png)

## Getting Started
To install CollatriX as an application go to our [releases page](https://github.com/MMI-CODEX/CollatriX/releases) and download the dmg (for macs) or exe (for windows).
Check out the [manual](https://github.com/MMI-CODEX/CollatriX/blob/master/CollatriX_v2-0-1_manual.pdf) for more detail.

**Note** IF you are using a mac - you’ll also need exiftool installed. If you already have it installed, great! If not, download the zipfile [here](https://github.com/cbirdferrer/collatrix-OLD/blob/293d8e37f5a9c82b60726dcb8b4decbad4bb48dc/collatrix/install_exiftool_mac.zip) for an easy download 


## Usage
Please read our [manual](https://github.com/MMI-CODEX/CollatriX/blob/master/CollatriX_v2-0-1_manual.pdf) and check out our [tutorial videos](https://media.oregonstate.edu/playlist/dedicated/1_hm9cgwh4/1_v8r3wntu) for detailed instructions.

## Attribution
If you use this software please cite our paper:  
*Bird C.N. & Bierlich K.C., (2020). CollatriX: A GUI to collate MorphoMetriX outputs. Journal of Open Source Software, 5(51), 2328, https://doi.org/10.21105/joss.02328*

Additionally:
* if you calculate Body Volume cite:
  * Circular frustums: *Christiansen, F., Vivier, F., Charlton, C., Ward, R., Amerson, A., Burnell, S., & Bejder, L. Maternal body size and condition determine calf growth rates in southern right whales (2018). Maternal body size and condition determine calf growth rates in southern right whales. Marine Ecology Progress Series, 592, 267–281. http://doi.org/10.3354/meps12522*

  * Elliptical: *Christiansen F,  Sironi M,  Moore MJ, et al.  Estimating body mass of free-living whales using aerial photogrammetry and 3D volumetrics. Methods Ecol Evol.  2019; 10: 2034–2044. https://doi.org/10.1111/2041-210X.13298* 

* if you calucalte BAI cite: 
*Burnett, Jonathan D., Leila Lemos, Dawn Barlow, Michael G. Wing, Todd Chandler, and Leigh G. Torres. 2018. “Estimating Morphometric Attributes of Baleen Whales with Photogrammetry from Small UASs: A Case Study with Blue and Gray Whales.” Marine Mammal Science 35 (1): 108–39. https://doi.org/10.1111/mms.12527.*

## Contributing
We designed CollatriX with future collaborations in mind and we'd love for you to contribute! If you'd like to contribute please see our [contributing guidelines](https://github.com/MMI-CODEX/CollatriX/blob/701dc27b8ee2c76bafa407235a2a3e94bc82cd38/CONTRIBUTING.md)

### Creating A Pull Request

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Copyright (c) 2020 Clara Bird, KC Bierlich

`Collatrix` is free software made available under the MIT License. For details see the the [LICENSE](https://github.com/cbirdferrer/collatrix/blob/master/LICENSE) file.

## Authors

* **Clara N. Bird** - *Researcher, PhD Wildlife Science* - [Clara Bird](https://mmi.oregonstate.edu/people/clara-bird)
* **KC Bierlich** - *Assistant Professor Senior Research, PhD Marine Science and Conservation* - [KC Bierlich](https://mmi.oregonstate.edu/people/kevin-bierlich)
