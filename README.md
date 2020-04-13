# scot_covid
Time series of covid19 cases/deaths in Scotland

Author: William Ball

Last Update: 29/03/2020

Description: Covid19 case/death data taken from the official ScotGov daily reports found here:
https://www.gov.scot/coronavirus-covid-19/

Variables:

Date - Date on which cases/deaths data are reported (not when tests/deaths occured)

Positive - Total positive

Negative - Total negative

TotalTests - Total of all tests

NewTests - New Tests completed per day

NewCases - New cases per day

DayRateIncrease - New cases each day as a proportion of new cases the previous day

TestsPerMillion - Number of tests completed per million (Scottish Population est. 5,438,000)

CasesPerTest - Daily new cases divided by daily new tests

PositivePercent - Percentage of total tests which are positive

NewDeaths - New deaths per day

TotalDeaths - Total deaths

CaseFatalityRate - Total deaths divided by total positive

DeathsPerMillion - Total deaths per million of Scottish population

DailyDPMillion - Daily deaths per million of Scottish Population

** As of 08/04/2020 The Scottish Government began reporting numbers relating to hospitalisations **

ICU - The number of patients in Intensive Care with confirmed or suspected COVID-19 test

HospSusConf - Total reported to be in hospital with confirmed or suspected COVID-19

** As of 11/04/2020 The Scottish Government produced back-dated figures for ICU & Hospitalisations **

NewICU - The daily change in the number of patients in Intensive care

NewHosp - The daily change in the number of patients in Hospital with confirmed or suspected COVID-19

IntensRate - Proportion of suspected/confirmed hospitalisations who are in Intensive care (with confirmed case)

HospRate - Proportion of total confirmed cases who are currently in hospital
*Note: Most testing to date has been on hospitalised patients which is why this number seems so high
