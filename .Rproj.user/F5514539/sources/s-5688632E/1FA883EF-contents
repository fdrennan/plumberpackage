# Hello, world!
#
# This is an example function named 'hello'
# which prints 'Hello, world!'.
#
# You can learn more about package authoring with RStudio at:
#
#   http://r-pkgs.had.co.nz/
#
# Some useful keyboard shortcuts for package authoring:
#
#   Install Package:           'Cmd + Shift + B'
#   Check Package:             'Cmd + Shift + E'
#   Test Package:              'Cmd + Shift + T'

#' wait
#' @description For testing the API
#' @param n How many seconds to wait
#' @importFrom jsonlite toJSON
#' @export wait
wait <- function(n = n) {
  if(n > 5) {
    n = 5
  }
  Sys.sleep(n)

  toJSON("Ran successfully")
}
