# My Awesome Hackintosh

* [HWSensors-pkg](https://github.com/githubutilities/HWSensors-pkg)

> I have worked so hard to pack this but I discover that I just reinvent
> the wheel. :sob:
> The original author already provides the package installer for us.

* [VoodooHDA-repacked-pkg](https://github.com/githubutilities/VoodooHDA-repacked-pkg)

> Generic Sound Card Driver.

* [GenericUSBXHCI-pkg](https://github.com/githubutilities/GenericUSBXHCI-pkg)

> Generic USB 3.0 Driver.

* [Kext Wizard](http://www.insanelymac.com/forum/topic/253395-kext-wizard-easy-to-use-kext-installer-and-more/)

> A kext installer.


## Note

All the pkg is available through [caskroom](https://github.com/caskroom/homebrew-cask). Here is the bootstrap script:

```sh
brew tap githubutilities/tap
brew cask install hwsensors
brew cask install voodoo-hda-kext
brew cask install generic-usb-xhci-kext

# install kext-wizard
brew tap caskroom/unofficial
brew cask install kext-wizard
```

## Fallback Option

* [hackintosh-kexts](https://github.com/githubutilities/hackintosh-kexts)

