<p align="center">
  <img src="https://github.com/data-team-uhn/cards/blob/clindig_demo/clindig-resources/clinical-data/src/main/media/SLING-INF/content/libs/cards/resources/logo.png" width="600px" alt="ClinDIG logo"/>
</p>

# ClinDIG

## Factsheet
ClinDIG integrates two software platforms: CanDIG and CARDS to create a rich clinical and genomic data management solution that enables federated analysis while protecting patient privacy. CanDIG offers a suite of federation services to enable privacy-protected clinical and phenotypic data sharing and research across multiple sites. CARDS offers a data management platform that can be configured for your own needs, integrating a UI for questionnaire development, connection to numerous ontologies for data structure, and a patient-facing questionnaire UI for direct data capture. 

## Documentation
### Prerequisites
- `vagrant`
- `virtualbox`

Run the following commands:
```
vagrant plugin install vagrant-disksize
vagrant plugin install vagrant-reload
git clone git@github.com:sdumitriu/CanDIGv2.git
cd CanDIGv2
git checkout vagrant-docker-compose-install
vagrant up
```
Open `http://localhost:2543/`

## Code/Download
If you'd like to access the code to the platforms this project brought together as separate entities, please visit:
- [CanDIG v2](https://github.com/CanDIG/CanDIGv2)
- [CARDS](https://github.com/data-team-uhn/cards/)

## Provenance
New features and bug fixes are tested and released into the development branch upon completion. Releases are created by combining a number of features into a single release tag, upon which release notes will be updated. During development, pull requests are reviewed and validated by the development team before being merged into the development branch. All ClinDIG releases will be approved by DATA Team leadership.

## Release Notes

## Support
This is free software! Create an issue in GitHub to ask others for help, or try fixing the issue yourself and then make a pull request to contribute it back to the core. If you have any questions, please contact data.team@uhn.ca
