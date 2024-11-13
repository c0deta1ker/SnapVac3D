# SnapVac3D: Rapid 3D plotting for vacuum chamber design

[SnapVac3D](https://github.com/c0deta1ker/SnapVac3D) is a cutting-edge app that enables users to effortlessly design custom vacuum chambers in 3D with exceptional precision and speed. Seamlessly browse through your designs to ensure feasibility, then save them as text files and PNGs for easy retrieval or sharing with your preferred vacuum supplier. Crafting your perfect vacuum chamber has never been more accessible!

This app is tailored for researchers, engineers, technicians, and students interested in designing bespoke vacuum chambers. Whether you are collaborating on a vacuum chamber design, working on a research project, or simply curious about creating your own design, this app facilitates easy iteration. The final text file contains all the technical information your vacuum supplier needs. Download [SnapVac3D](https://github.com/c0deta1ker/SnapVac3D) today and bring your designs to life!  


## Installation  
1. Download the *SnapVac3D* repository.
2. Open MATLAB and use *Set Path* in the *Home* tab to add the *SnapVac3D* repository and all its sub-folders into its saved search paths.
3. Type 'App_SnapVac3D' in the MATLAB Command Prompt to boot up the  App.

Or, simply download & install the executable file [here](/SnapVac3D-v1.0/InstallWizard/install_SnapVac3D_web.exe)!    


## App Details
![App_MatBase](SnapVac3D-v1.0/ReadMeImages/App_SnapVac3D.png)   

The vacuum design is split into three independent tables of properties:  

**(1) Main-Chamber Properties**: Define the design of your main chamber, whether it's cylindrical, spherical, or tetragonal, along with its dimensions.  

**(2) Focal-Point Properties**: Specify the focal points, which serve as the origin points for each port placement.  

**(3) Port Properties**: Configure all necessary ports using conventional European (DN) sizes, based on tube inner diameters in millimeters. Define the length and rotational orientation (via spherical coordinates) of each port. Additionally, specify whether the port is rotatable or tapped and label its usage. Crucially, the focal point to serve as the origin for each port can also be defined with a drop-down box.   


You can continuously monitor the progress of your model as you build it port-by-port, with the option to save the results at any time. Additionally, you can save the final tables as a single .txt file, which can be easily reloaded, making it super simple to collaborate or share your designs with others.    


## MATLAB Version control  
MATLAB version:   2024a  
MATLAB add-ons (recommended): None required


## Authors
**Dr. Procopios Constantinou**,  
Swiss Light Source (SLS),  
Paul Scherrer Institute (PSI),  
email: procopios.constantinou@psi.ch


## Acknowledgments
I would like to thank Dr. Vladimir Strocov (PSI) for his invaluable guidance and support in the design and execution of this software application. His expertise and insights were instrumental in the successful completion of this project.   


## License  
This project is licensed under the GNU General Public License v3.0 - see the [LICENSE.md](LICENSE.md) file for details. 

--PCC, November 2024


