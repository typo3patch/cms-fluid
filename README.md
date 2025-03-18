# patch'd [TYPO3](https://typo3.org) extension [`fluid`](https://github.com/TYPO3/typo3/tree/main/typo3/sysext/fluid)

This extension integrates the Fluid templating engine into TYPO3.

## Installation

```bash
composer config repo.t3p-fluid git https://github.com/typo3patch/cms-fluid
composer req typo3patch/cms-fluid
```

## Provides

* `^10.4` incl. [ADD] attr. `decoding` @ `<f:image />` [[patch](https://github.com/TYPO3/typo3/commit/c0e99719e17b275a2a85a676ea9ed60c22999476)]
* https://github.com/typo3patch/cms-fluid/blob/da5a168bb822d77f7c368532f8ce04346134ccfb/composer.json#L18

## Patches

https://github.com/typo3patch/cms-fluid/commit/6436ef6268f0044bfb04c5054e4d8e98ac5fa818 [ADD] attr. `fetchpriority` @ `<f:(media|image) />` [[issue](https://forge.typo3.org/issues/97765)]
