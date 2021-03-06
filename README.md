# Dell Settings

This repository demonstrates the usage of dell cctk command line.

## Content

- [Installation](#Installation)
- [Settings for Battery Charging](#Settings-for-Battery-Charging)
- [Reference](#Reference)


## Installation

Visit this link for installation guide. [link](https://topics-cdn.dell.com/pdf/command-configure-v42_install-guide_en-us.pdf)

## Settings for Battery Charging

```bash
cd /opt/dell/dcc
sudo ./cctk --PrimaryBattChargeCfg=Custom:50-85
```

## Reference

- Command line documents [link](https://dl.dell.com/topicspdf/command-configure-v41_reference-guide_en-us.pdf)
- Introduction of Dell command line [link](https://www.dell.com/support/kbdoc/en-sg/000134806/how-to-install-use-dell-client-configuration-toolkit)
