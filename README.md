
collaborative Protection Profile for Dedicated Security Component
===============
[![build pp document](https://github.com/commoncriteria/dsc/workflows/build%20pp%20document/badge.svg)](https://github.com/commoncriteria/dsc/actions)
[![GitHub issues Open](https://img.shields.io/github/issues/commoncriteria/dsc.svg?maxAge=2592000)](https://github.com/commoncriteria/dsc/issues) 
![license](https://img.shields.io/badge/license-Unlicensed-blue.svg)

This repository hosts the draft version of the collaborative Protection Profile for Dedicated Security Component based on the 
[Essential Security Requirements (ESR)](https://commoncriteria.github.io/pp/dsc/dsc-esr.html) for this technology class of 
products. This repository is used to facilitate collaboration and development on the draft document. 
See the [release](#Release-Version) section if you are looking for the officially released version for evaluations. 
A list of products that have passed evaluation against this Protection Profile can be found [here](QQQQ).

## Draft Version

* [collaborative Protection Profile for Dedicated Security Component](https://commoncriteria.github.io/pp/dsc/dsc-release.html) (html)
* [Supporting Documents for Dedicated Security Component cPP](https://commoncriteria.github.io/pp/dsc/dsc-sd.html) (html)
* [collaborative Protection Profile for Dedicated Security Component](https://commoncriteria.github.io/pp/dsc/dsc-release.pdf) (pdf)
* [Supporting Documents for Dedicated Security Component cPP](https://commoncriteria.github.io/pp/dsc/dsc-sd.pdf) (pdf)

## Release Version
* [collaborative Protection Profile for Dedicated Security Component](https://www.niap-ccevs.org/MMO/PP/cpp_dsc_v1.0.pdf)

## Contributing

If you are interested in contributing directly to future versions the this Protection Profile, please consider joining the NIAP technical community.
* [How to join the NIAP Technical Community (Mailing list and updates)](https://www.niap-ccevs.org/NIAP_Evolution/tech_communities.cfm)

## Feedback

Questions, comments, and fixes can be submitted to the [repository issue tracker](https://github.com/commoncriteria/QQQQ/issues)

## Quickstart
To clone this project along with its _transforms_ submodule run:

````
  git clone --recursive git@github.com:commoncriteria/qqqq.git
````
To pull updates from the upstream _transforms_ submodule and commit them run:
````
 git submodule update --remote transforms
 git add transforms
 git commit
````

### Development Info
[Help working with Transforms Submodule](https://github.com/commoncriteria/transforms/wiki/Working-with-Transforms-as-a-Submodule)

## Repository Content
* input - Contains the 'meat' of the project. It's the input content (in XML form) that gets transformed to readable html.
* output - The output directory where the html is placed after transformation.
* output/images - The directory where images are stored
* transforms - Points to the transform subproject which is really a repository for resources shared amongst many Common Criteria projects. You shouldn't need to modify it.

## Links 
* [National Information Assurance Partnership (NIAP)](https://www.niap-ccevs.org/)
* [Common Criteria Portal](https://www.commoncriteriaportal.org/)

## License
See [License](./LICENSE)
