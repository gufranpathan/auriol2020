# auriol2020
Reproduction Package for Auriol et al (2020)

The reproduction package uses the `starpolishr` library which is not available on CRAN. The library can be installed from the [starpolishr github repo](https://github.com/ChandlerLutz/starpolishr). The library requires certain prerequisite software which were not automatically installed. The following sequence of installation commands successfully installed the library.

```
install.packages("cli")
install.packages("rlang")
install.packages("devtools")
devtools::install_github("ChandlerLutz/starpolishr")
```