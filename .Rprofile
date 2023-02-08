# Sys.getenv("R_LIBS_USER")

# .libPaths(c( Sys.getenv("R_LIBS_USER") , .libPaths()))
.libPaths(Sys.getenv("R_LIBS_USER"))
options(repos = c(CRAN = "https://packagemanager.rstudio.com/all/__linux__/jammy/latest"))

# TO avoid error: Error: Input files not all in same directory, please supply
# explicit wd
options(bookdown.render.file_scope = FALSE)
