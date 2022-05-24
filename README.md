# Flat prices dashboard in R

## Description

Project represents flat prices in 17 biggest cities in Poland in years 2006-2021.\
Dashboard was made for diploma project. I have choosen R because I wanted to sharepen my programming skills in R lang.

## Requirements

- R (used 4.2.0)
- RStudio (used 2022.02.1)

## First run

To properly build solution you need to change file path
```
po<- read_excel("~/Desktop/Kamilka/dane.xls", sheet= "Rynek pierwotny ceny oferowane",col_names = TRUE, na = "")

pt <- read_excel("~/Desktop/Kamilka/dane.xls", sheet= "Rynek pierwotny ceny transakcyj",col_names = TRUE, na = "")

wo <- read_excel("~/Desktop/Kamilka/dane.xls", sheet= "Rynek wtorny ceny oferowane",col_names = TRUE, na = "")

wt <- read_excel("~/Desktop/Kamilka/dane.xls", sheet= "Rynek wtorny ceny transakcyjne",col_names = TRUE, na = "")

przecietne_wynagrodzenie <- read_excel("~/Desktop/Kamilka/dane.xls", sheet= "Srednie wynagrodzenie brutto",col_names = TRUE, na = "")
```
You need to change this path `~/Desktop/Kamilka/dane.xls` to your data file path.

To build on Windwos PC uncomment all packages in `#Dla systemu Windows` and comment `#Dla systemu MacOS`


## Future

Project was written in Polish as it needed to be done for diploma project. In future project will be rewritten to English.
