# Cash Shampoo 
## _Frontend and Backend for the UFill Dispenser_

[![N|Solid](https://ufill.net/wp-content/uploads/2022/03/cropped-U-fill-logo.png)](https://ufill.net)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

The UFILL Dispenser is a pioneering innovation in the realm of sustainable packaging solutions. Established in 2019, UFILL is the first Sri Lankan company to manufacture liquid vending machines engineered with local ingenuity. As a subsidiary of Vega Innovations Pvt Ltd, home to South Asia’s first electric supercar, UFILL represents a commitment to environmental responsibility and technological advancement. The dispenser is designed to reduce plastic waste by allowing consumers to refill their containers with various products, thereby promoting a circular economy and supporting efforts to achieve net-zero carbon emissions. With its user-friendly interface and versatile applications, the UFILL Dispenser is set to revolutionize the way we think about product consumption and waste management. Whether for personal care items, household cleaners, or food products, UFILL offers a convenient and eco-friendly alternative to single-use packaging.

_The Components for V1 and V2 are similar_

The Main Components of this repo.

- Setup
- Installation
- ✨Notes ✨

## Setup

<img width="376" alt="image" src="https://github.com/LMJayasundara/cashnote_lk/assets/73810867/37dee978-6184-4d72-ab45-f4bd2aaa317a">
<img width="374" alt="image" src="https://github.com/LMJayasundara/cashnote_lk/assets/73810867/f60f07e2-b8ba-4044-85d5-b8b74e5e481b">
<img width="377" alt="image" src="https://github.com/LMJayasundara/cashnote_lk/assets/73810867/0af0cc4f-7e7f-46f4-925e-2242e44b0910">

## Installation

Step 1: Install NVM 

_For Linux and UNIX Based OSes(Mac):_ https://github.com/nvm-sh/nvm
_For Windows:_ https://github.com/coreybutler/nvm-windows

Step 2: Install Node JS 14.21.3 and Set it using NVM
_Check NVM Docs_
<img width="247" alt="image" src="https://github.com/LMJayasundara/cashnote_lk/assets/73810867/5edd3e78-0434-4aa4-b91e-72db6eaa7afa">
 
Step 3: Clone the repo and open the project folder on VS Code
```
git clone https://github.com/LMJayasundara/cashnote_lk
cd cashnote_lk
npm install
node serial_data.js
```
Run the above codes to run the server on the port 3001

Step 4: Open the loading.html on firefox

```
firefox --kiosk loading.html
```

##✨Notes: ✨

If you meet errors related to fiber at npm install setup
Makesure 
Visual Studio Community 2017 is installed : https://visualstudio.microsoft.com/vs/older-downloads/
<img width="799" alt="image" src="https://github.com/LMJayasundara/cashnote_lk/assets/73810867/ba25c5f3-eed9-4bef-8ffe-5736cb90c97d">

Make sure to install Desktop Development WITH C++ [ONLY]

<img width="865" alt="image" src="https://github.com/LMJayasundara/cashnote_lk/assets/73810867/1fd699fd-2e2d-48d3-a7bf-a09b0c086d4b">

If errors presists Install C++ Build tools
<img width="605" alt="image" src="https://github.com/LMJayasundara/cashnote_lk/assets/73810867/2e6e21bd-a860-4f05-a89c-e1be1a56014d">


- Install VS before installing NVM and Node
- Delete Node Modules and Package.lock file before 
- Run the code in Linux for best performance
- Small alignment issues can be removed by using Chromium in Kiosk
- Don't forget to check the Environment varibles 
