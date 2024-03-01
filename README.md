# TAC Data Updater

TAC Data Updater is GitHub Action to update data sources in a TAC repo for projects at the Linux Foundation.

These scripts presume a few things...

1) The TAC is part of a Linux Foundation umbrella project. If you don't know if you are this, then likely these scripts aren't for you ;-)
2) You have a landscape
3) You have an artwork repo
4) You have a TAC repo setup

If all of these apply - these scripts are for you!

## Architecture

The concept behind the architecture is to enable users to edit data in the most appropriate tool, and then sync those changes to the relevant data locations. Data will not have the ability to be maintained in two different locations, avoiding any data silos that could be inadvertantly created.

