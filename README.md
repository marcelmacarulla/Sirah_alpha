# Sirah alpha
<p align="center">
  <img src="images/enciams_recir_2.jpg" alt="Sirah" style="width: 400px; height: 300px;">
</p>

## Description
<p style="text-align: justify;">
The goal of the SIRAH project is to develop products and technologies from laboratory settings to market scale.
The project is based on 2 products: SIRAH alpha and SIRH beta.
SIRAH is an irrigation module at a prototype level development. The irrigation system has a nutrient and water
recirculation infrastructure installed which can be monitored with an irrigation panel and a sectorization of
water valves.
The potential of the smart irrigation product in the marked will be made in this task. Also, a social impact
assessment is crucial to determine the potential effect on the society of the product installation. The
elaboration of a social study and questionnaire for potential customers and stakeholders will help preventing
possible risks and impacts on the installation of the product. While the increase of vegetation and the creation
of access to fresh produce might signify an improvement, the acceptability to install these production systems
in a person's defined as “NIMBY”.
</p>

This repository contains the Sirah Alpha project, which offers the following functionalities:
- Scheduled irrigation
- Manual operation of irrigation valves
- Historical data of valves operation

<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Repository Structure
The repository is organized as follows:
- `code/Sirah`: Contains the scripts to be installed in the raspberry and arduino
- `Node_Red_Flows`: Contains the flows to be imported in the raspberry's node red 
- `docs/`: Contains the project documentation.
- `images/`: Contains the project images.
<p align="right">(<a href="#readme-top">back to top</a>)</p>


## Installation
To install and run this project, follow these steps:
1. Copy the folder `code/Sirah` in your raspberry
2. Compile and send to the arduino the file 280223_Sirah_arduino.ino located in `Code/Sirah/Arduino/ProgramaArduino/280223_Sirah_arduino`
3. Import the nodered flows in your raspberry located in `Node_Red_Flows`

## Usage
To use this project, follow these steps:
1. Turn on the raspberry
2. Configure the irrigation schedule

## Documentation
- [Sirah Alpha scheme](docs/sirah-Model.pdf)
- [User manual](docs/user_manual.md)

## Contribution
Contributions are welcome! If you wish to contribute to this project, follow these steps:
1. Fork the repository.
2. Create a branch for your contribution (`git checkout -b feature/new-feature`).
3. Make your changes and commit (`git commit -am 'Add new feature'`).
4. Push the branch (`git push origin feature/new-feature`).
5. Create a pull request on GitHub.

## Credits
This project was developed by GRIC (Group of Reasearch and Innovation in Construction) from UPC (Universitat Politècnica de Catalunya and SOSTENIPRA from UAB.

<p> <img src="images/GRIC.png" alt="GRIC" style="width: auto; height: 50px;"> &nbsp &nbsp <img src="images/UPC.png" alt="UPC" style="width: auto; height: 50px;"> &nbsp &nbsp <img src="images/SOSTENIPRA.png" alt="SOSTENIPRA" style="width: auto; height: 50px;"> &nbsp &nbsp <img src="images/UAB.png" alt="UAB" style="width: auto; height: 50px;"> </p>

This project was funded by MCIN/AEI/10.13039/501100011033 and by the European Union“NextGenerationEU”/PRTR with the reference number PDC2021-121054-C21.

<img src="images/funding_sirah.jpg" alt="Funding" style="width: auto; height: 50px;">

## License
This project is licensed under the MIT License. See the [LICENSE.md](LICENSE.md) file for more details.
