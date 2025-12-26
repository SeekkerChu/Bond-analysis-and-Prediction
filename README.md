Trying to find the correlation between features such as: inflation, unemploy rate, ect. To predict market bond, aaa and bbb companies.

1. Import libraies:
library(dplyr)
library(ggplot2)
library(tidyverse)
library(tidyr)
library(corrplot)
library(vars)
library(lmtest)
library(tsibble)
library(lubridate)
library(urca)
library(tseries)
library(patchwork)
library(forecast)
library(tsDyn)
library(lubridate)

2. ADF test: Use ur.df()

3. Johansen test

4. Based on ADF and Johansen test, select which model we should use. (VAR/VECM)

5. Granger test
