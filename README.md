# Home Automation

![LICENCE](https://img.shields.io/github/license/hbrekke/home-automation)
![SIZE](https://img.shields.io/github/repo-size/hbrekke/home-automation)
![LAST UPDATE](https://img.shields.io/github/last-commit/hbrekke/home-automation)

Home Automation is my home automation system, the system should be able to do all the different smart things in your house, the system is based off raspberry pi's, where one raspberry pi will act as the main server / hub other translate commands from the hub to the smart devices and respond with the response if any.

The idea is that one rasperry pi will act as a HUB or main server how ever you see it, this should communicate with the different other raspberries that will act as a translator for the language that the server wants to talk and the way that the component wants to talk. The main server will not be directly connected to any device, it will use API's to make this possible.

The whole system will have a user-friendly and layout and self explanatory - If you see any flaws here please make an issue.

## Installation

The whole system is based off docker applications run on a raspberry pi (is what is use but docker makes it possible to use any computer that can install docker).

inside the folder /images/ there will be all the docker images from the different "translators" for the server, and the server image will also be located here in the MAIN-HUB folder.

All folders will include a separate readme with the need to know things to deploy the "addon" and how how to install specifically this "addon".

## Planed "Addons"
* Garage door
* IKEA light controller
* Scheduler

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
