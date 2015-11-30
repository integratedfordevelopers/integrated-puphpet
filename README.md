# Integrated PuPHPet #
Integrated PuPHPet provides a Vagrant box for Integrated applications, based on PuPHPet.

## Requirements ##
* Vagrant >= 1.7
* Virtualbox >= 4.3
* On Windows: Vagrant WinNFSd (https://github.com/winnfsd/vagrant-winnfsd)
* Availability of 2048MB of system memory and 2 cpu cores for you Vagrant box. If you don't have them you have to overrule these settings in the config-custom.yaml.

## Features ##
* Provides a default Vagrant box based on PuPHPet
* Customizable

## Documentation ##
* [Integrated for Developers](http://integratedfordevelopers.com/ "Integrated for Developers")

## Installation ##
This bundle can be installed following these steps:

* Add integrated/puphpet to your project composer.json and run a composer update
* Copy the Vagrantfile.dist to your project directory and rename to Vagrantfile
* Copy config-custom.yaml.dist to your project directory and rename to puphpet/config-custom.yaml
* Customize the hostname in puphpet/config-custom.yaml, otherwise it will conflict with other projects
* Do a vagrant up and your box is ready

## License ##
This bundle is under the MIT license. See the complete license in the bundle:

    LICENSE

## Contributing ##
Pull requests are welcome. Please see our [CONTRIBUTING guide](http://integratedfordevelopers.com/contributing "CONTRIBUTING guide").

## About ##
This bundle is part of the Integrated project. You can read more about this project on the
[Integrated for Developers](http://integratedfordevelopers.com/ "Integrated for Developers") website.