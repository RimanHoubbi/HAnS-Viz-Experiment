# HAnS-Viz-Experiment

# Prerequisites
- Download **Git** [Download Git for your system](https://git-scm.com/downloads)
- Download **IntelliJ**, maximum version should be 2023.3.8 [Download IntelliJ here](https://www.jetbrains.com/de-de/idea/download/other.html)
- Open **Sanke game** project to carry out the tasks and evaluate the functionalities of the plugin.
- Install **HAnS** and **HAnS-Viz** Plugins

# Installation
**HAnS**
- Using the IDE built-in plugin system:
  Settings/Preferences > Plugins > Marketplace > Search for "HAnS" > Install

- Manually:
  Go to IntelliJ Settings --> select "Plugins" --> Click on >⚙️>"Install plugin from Disk..."
-->Navigate to the folder of the downloaded repository then select and install "HAnS-0.0.7.zip".

  After doing that, please clone the [HanS Repository](https://github.com/RimanHoubbi/HAnS) and switch to FeatureHistoryView branch
  (This is a temporary solution to run HAnS-Viz with the new feature history view until the code gets reviewd)

**HAnS-Viz**
- Manually:
  Go to IntelliJ Settings --> select "Plugins" --> Click on >⚙️>"Install plugin from Disk..."
-->Navigate to the folder of the downloaded repository then select 'HAnS-Viz-2.zip' and install.

After doing that, please clone the [HanS-Viz Repository](https://github.com/RimanHoubbi/HAnS-viz) and switch to featureHistoryView branch
Please note: inside the **build.gradle.kts** file [edit this line](https://github.com/RimanHoubbi/HAnS-viz/blob/2eb8afc5c75b606a10c39750f402edc0392c72ee/build.gradle.kts#L49) to add the location of HAnS-0.0.7.jar on your computer.

After setting it up, navigate to gradle, press on Run Plugin and a new window will open, here you should choose the Sanke project. 
You can access the HAnS-Viz window from the right top of the screen. 

# Preparations
Please view the files „HAnS_Introdction.pdf“ and „HAnS-Viz_Introdction.pdf“ in slideshow within the downloaded GitHub Repo

