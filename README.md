___
# DELETE THIS INSTRUCTIONS AND ADD AN INTRODUCTION ABOUT YOUR PROJECT
___

HydraSense – Smart Water Bottle

Introduction

HydraSense is an embedded systems project that aims to make everyday hydration smarter by integrating water consumption monitoring, water-quality parameter sensing, and filter usage tracking into a smart water bottle.

Conventional water bottles primarily serve as water storage containers and do not provide users with information about their drinking habits, selected water-quality parameters, or filter usage. HydraSense aims to address these limitations through an intelligent and user-friendly design that combines embedded sensors, electronic components, and a built-in replaceable filter.

The system is designed to help users monitor their water consumption, view relevant sensor readings, and keep track of filter usage. By integrating these features into a portable bottle, HydraSense explores how embedded systems and sensor technologies can support healthier hydration habits and more informed water-use decisions.

The project focuses on designing and developing a working prototype, integrating hardware and software components, and testing the functionality and reliability of the system.

Project Objectives

- Develop a smart water bottle that monitors water consumption.
- Integrate sensors to measure selected water-quality parameters.
- Implement a mechanism to track filter usage.
- Design a compact and practical embedded system suitable for a portable bottle.
- Test and evaluate the prototype's functionality and performance.

Key Features

- Hydration Monitoring: Designed to track the user's water consumption.
- Water-Quality Monitoring: Incorporates sensors for selected water-quality parameters.
- Filter Usage Tracking: Aims to monitor filter usage and indicate when maintenance or replacement may be required.
- Integrated Embedded System: Combines sensing, processing, and electronic components in a portable design.
- User-Friendly Operation: Aims to present useful information in an accessible format.

System Overview

HydraSense combines a water bottle, sensing components, a microcontroller, and a replaceable filter in a single prototype. Sensor readings and consumption measurements are processed by the embedded controller to support hydration monitoring and system feedback.

The prototype will be evaluated through functional testing and measurements appropriate to the implemented features. Water-quality readings and filter performance will require suitable testing and validation before any safety-related claims can be made.

Project Team

Student Name| Registration Number| Email
H. M. H. N. Aberathna| E/22/001| e22001@eng.pdn.ac.lk
M. A. N. P. Anawarathne| E/22/027| e22027@eng.pdn.ac.lk
A. S. V. Gunasiri| E/22/120| e22120@eng.pdn.ac.lk
P. H. D. Rathnasiri| E/22/324| e22324@eng.pdn.ac.lk

Technologies and Components

The project involves embedded systems development, sensor integration, microcontroller programming, electronic circuit design, and hardware testing.

The final list of microcontrollers, sensors, programming languages, and other hardware components will be updated as the prototype design is finalized.

Project Status

HydraSense is being developed as a third-year embedded systems project. The design, implementation, integration, and testing activities will be documented as the prototype progresses.

Repository Structure

- "docs/" – Project documentation and GitHub Pages content.
- Source code and hardware-related files – Embedded software, circuit designs, and other implementation resources as added to the repository.

Future Improvements

- Improve hydration tracking accuracy.
- Refine sensor calibration and water-quality measurements.
- Develop clear user feedback for hydration and filter maintenance.
- Optimize power consumption and physical integration.
- Expand prototype testing and performance evaluation.

Acknowledgements

This project is developed as part of the Embedded Systems project programme at the Department of Computer Engineering, Faculty of Engineering, University of Peradeniya, Sri Lanka.

### Enable GitHub Pages

You can put the things to be shown in GitHub pages into the _docs/_ folder. Both html and md file formats are supported. You need to go to settings and enable GitHub pages and select _main_ branch and _docs_ folder from the dropdowns, as shown in the below image.

![image](https://user-images.githubusercontent.com/11540782/98789936-028d3600-2429-11eb-84be-aaba665fdc75.png)

### Special Configurations

These projects will be automatically added into [https://projects.ce.pdn.ac.lk](). If you like to show more details about your project on this site, you can fill the parameters in the file, _/docs/index.json_

```
{
  "title": "This is the title of the project",
  "team": [
    {
      "name": "Team Member Name 1",
      "email": "email@eng.pdn.ac.lk",
      "eNumber": "E/yy/xxx"
    },
    {
      "name": "Team Member Name 2",
      "email": "email@eng.pdn.ac.lk",
      "eNumber": "E/yy/xxx"
    },
    {
      "name": "Team Member Name 3",
      "email": "email@eng.pdn.ac.lk",
      "eNumber": "E/yy/xxx"
    }
  ],
  "supervisors": [
    {
      "name": "Dr. Supervisor 1",
      "email": "email@eng.pdn.ac.lk"
    },
    {
      "name": "Supervisor 2",
      "email": "email@eng.pdn.ac.lk"
    }
  ],
  "tags": ["Web", "Embedded Systems"]
}
```

Once you filled this _index.json_ file, please verify the syntax is correct. (You can use [this](https://jsonlint.com/) tool).

### Page Theme

A custom theme integrated with this GitHub Page, which is based on [github.com/cepdnaclk/eYY-project-theme](https://github.com/cepdnaclk/eYY-project-theme). If you like to remove this default theme, you can remove the file, _docs/\_config.yml_ and use HTML based website.
