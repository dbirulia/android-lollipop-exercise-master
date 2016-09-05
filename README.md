# Week 7 lab : Android Lollipop Exercise

Android app to use as the base app for implementing the following material widgets and animations that were introduced in Android 5.0 (API level 21).

* RecyclerView (the new ListView)
* CardView (custom outline and shadow)
* Ripple animation (touch feedback)
* Palette (Incorporate dynamic color)
* Shared Element Activity Transition
* Floating Action Button

The app is composed of two screens. The first screen displays a list of contacts, in which, each item is described by the contact's avatar and name. Once a contact is selected from the list, a second screen appears with additional details about the contact, including his contact no. and a floating action button to place a phone call to this contact.

Time spent: **2** hours spent in total

## Video Walkthrough

Here's a walkthrough of implemented user stories:

<img src='https://github.com/dbirulia/android-lollipop-exercise-master/blob/master/Lollipop.gif' title='Video Walkthrough' width='' alt='Video Walkthrough' />

GIF created with [LiceCap](http://www.cockos.com/licecap/).

## Overview

The app does the following:

1. It uses a `RecyclerView` to display a list of contacts.
2. `CardView` is used to display each contact in the list.
3. Add ripple effect to `CardView` to provide touch feedback.
4. Use `Palette` to add dynamic color to contact item's background. Use the same color as the accent color for the views in details screen.
5. Add shared element activity transition to provide a seamless experience by emphasizing continuity between activity transitions.
6. Add a floating action button, clicking on which should enable you to directly place a call to your contact.

## Libraries

This app leverages the following third-party library:
* [Picasso](http://square.github.io/picasso/) - For image loading
