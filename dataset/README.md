# FOCUS Dataset

This folder contains all parsed JAR files (`jars`), and the metadata of the four datasets described in the paper:

- `SH_L`: 610 randomly selected Java projects retrieved from GitHub via the [Software Heritage archive](https://www.softwareheritage.org/archive/).
- `SH_S`: 200 smallest (in size) Java projects taken from SH<sub>L</sub>.
- `MV_L`: 3,600 randomly selected JAR files retrieved from the Maven Central repository.
- `MV_S`: 1,600 JAR files taken from MV<sub>L</sub>. Just one version per project is kept. 

In addition, we included the results obtained with PAM considering the SH<sub>S</sub> dataset  (`PAM`).