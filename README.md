# Unified-Approach-For-Automatic-Reports
e-Rum2020::A Unified Approach For Writing Automatic Reports

This repo contains rstudio.cloud Course materials for the June 2020 ***A UNIFIED APPROACH FOR WRITING AUTOMATIC REPORTS - Parameterization and Generalization of R-Markdown*** Workshop being held at e-Rumm2020. 

URL for this workshop Rstudio Cloud material (available for new connections until 20/06/2020) is:

https://rstudio.cloud/spaces/68613/join?access_code=iK9r7HvoIBiMYtabvcvER%2F0KObdhtxUUoZctMo22

More Details in the *Workshop_synopsis* document.



## Note

I forked this repo from [muschitiello's github](https://github.com/muschitiello/e-Rum2020-Unified-Approach-For-Automatic-Reports) during eRum june 2020. Any changes after that are just for my own educational purposes. 



## Renv for package management

This project uses `renv` for package mangement. Use the following code to restore packages from the lock.file:



```R
if (!require(renv)) install.packages("renv")

renv::restore()
```



See the [renv documentation](https://rstudio.github.io/renv/articles/renv.html) for more infomation about `renv`. 

