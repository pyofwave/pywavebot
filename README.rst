PyWaveBot
=========

Notices
-------

This repository was created to plan the eventual creation of this project and so hackers can can get started before I'm ready. 

PyOfWave wants to encourage decentralization, so while we may create this project as a reference, we won't create any other robot APIs ourselves but encourage others to do it.

Overview
--------

The modules created by these files will create a pythonic API for creating automated Wave users/participants. A base API has yet to be decided between xmpppy, pyxmpp, or something custom using thisismedium/python-sasl, but no other dependancies will be required. 

I will use this to create robots powering POW projects management.

I plan to have the following submodules:

- xmpp - Simple base XMPP module
- wave - Object representation of waves which implicitly updates the server (much as I do for users).
- events - Decorators to register to Wave events.
