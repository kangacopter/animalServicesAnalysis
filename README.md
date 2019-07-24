# Louisville Metro Animal Services: Cats and Dogs

A project to analyze animal services intake and outcome data using Python.

## Overview

Household pets, such as cats and dogs, are dear to many a human heart, but sometimes beloved pets end up in a different situation. How do they often fare? In this project, I set out to examine a dataset put together over several years by the Louisville Metro Animal Services. Both wildlife and household pets go through animal services, but in this report the reasons for intake and outcomes are examined for two common pets: cats and dogs. By analyzing the data, it becomes evident that cats and dogs are indeed not the same, and unsurprisingly have very different outcomes when they find themselves in the animal shelter.

To examine the outcomes of cats and dogs brought to animal services, I gathered a dataset from Louisville, KY's Open Data database website (https://data.louisvilleky.gov). Python, Jupyter Notebook, and Matplotlib were used to create the resulting graphs to aid in the analyzation of data. Initially I used SQL to make queries of interest to me, such as looking at how many black cats were taken in, and what other kinds of animals are brought in. There is a very large amount of data in this set, so cats and dogs were settled upon.

## Question/Problem

The question to answer with this analysis: **how do the intake reasons and outcomes differ for cats and dogs at Louisville Metro Animal Services?** The animal's health status at intake, resulting outcome, and reasons for intake were chosen to visualize in this report. These were chosen to illustrate just how many beloved pets are brought in for a variety of reasons, and to highlight the importance of spaying/neutering pets and also the importance of taking pet ownership seriously.

## Glossary

**Intake Asilomar Status**: The following is stated of The Asilomar Accords, an widely known agreement between animal welfare agents:

_In August of 2004, a group of animal welfare industry leaders from across the nation convened at Asilomar in Pacific Grove, California, for the purpose of building bridges across varying philosophies, developing relationships and creating goals focused on significantly reducing the euthanasia of healthy and treatable companion animals in the United States._

This document outlines agreed-upon terms to define an animal's condition upon intake:

**_Healthy_** - Animal is healthy and pose no safety or health risk.

**_Treatable + Rehabilitable_** - Animal is not healthy but can become so with proper treatment.

**_Treatable + Manageable_** - Animal is not healthy and have a permanant condition that, with consistent treatment, does not impact the animal's quality of life.

**_Unhealthy + Untreatable_** - Animal has behavioral issues that are unmanageable for pet owners, or has a disease or injury that negatively impacts the animal's quality of life.

**Intake Reason**: The main reason for which the animal is brought in to Metro Animal Services.

**TNR**: Stands for Trap, Neuter(Spay), Return. This refers to the practice of trapping stray animals, to neuter/spay them and then return them to their previous environment. This helps cut down the stray population and gives the animal a chance out in the wild.

**RTO**: Stands for Return to Owner. This refers to an outcome type in which the animal is returned to the owner of the animal. For example, an owner can bring the animal in for veterinary services or the animal was turned in at at Animal Services because it was found away from home.

## Requirements/How to run

Jupyter Notebook, Python, Matplotlib, Sqlite, Numpy, and Pandas.

1. Clone this repo
2. Launch Jupyter Notebook and view AnimalServicesAnalysis.ipynb

#### References

Animal Service Intake and Outcome dataset: https://data.louisvilleky.gov/dataset/animal-service-intake-and-outcome

The Asilomar Accords: https://www.shelteranimalscount.org/docs/default-source/DataResources/2004aaccords5.pdf?sfvrsn=31c1ff76_0

ASPCA Pet Statistics: https://www.aspca.org/animal-homelessness/shelter-intake-and-surrender/pet-statistics
