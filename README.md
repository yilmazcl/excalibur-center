# Excalibur Center (EX900G fork)

A Linux alternative to Casper's Excalibur Control Center, with a couple of fixes for the EX900G.

## What's different in this fork

The bottom strip LEDs can now be controlled (color, brightness, on/off), and the left and right keyboard zones are no longer swapped.

## Usage

    excalibur-center --set-led corner FF8800   # set the bottom strip color
    excalibur-center --set-led corner off      # turn the bottom strip off
    excalibur-center --restore                 # restore the last saved state

## Tested on

Casper Excalibur EX900G running Kubuntu 24.04. Other models may behave differently.

## Install

    ./install.sh

The kernel driver comes from the casper-wmi project by Mustafa-eksi. Licensed under GPL-2.0-or-later. This project is not affiliated with Casper.
