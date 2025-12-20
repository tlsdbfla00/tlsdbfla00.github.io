---
layout: project
type: project
image: img/pantrypals-logo.png
title: "Pantry Pals"
date: 2025
published: true
labels:
  - PostgreSQL
  - GitHub
  - Next.js
  - Prisma
summary: "Pantry Pal is a web app that helps users keep track of what they have in their pantry, fridge, and freezer by managing inventory, tracking expiration dates, and automatically creating shopping lists so grocery shopping is easier and food waste is reduced."
---

<img class="img-fluid" src="../img/CorponectorLanding.png">

## Project Overview
Pantry Pals is a web application designed to help people keep track of the food they have at home. Many people forget what’s in their pantry or fridge, which leads to buying duplicates or letting food expire. Pantry Pals solves this problem by giving users a simple digital inventory for their pantry, fridge, freezer, and spices.

Users can easily add, update, and remove items, track quantities, and see expiration dates. The app can also automatically generate shopping lists when items are running low, making grocery shopping more organized and efficient. The interface is clean and minimal so it’s easy to use every day without feeling overwhelming.

## Use Cases

* Check what items are low or expired before going to the store

* Look up ingredients while cooking to see what’s available

* Share a pantry list with family members or roommates

* Use expiration reminders to finish food before it goes bad

* Barcode scanning for quick item entry

* Recipe suggestions based on available ingredients

## Features & Future Ideas

* Reports to track spending habits and reduce food waste

* Possible integration with smart assistants like Alexa or Google Assistant

## Deployment

Pantry Pals is deployed using Vercel with Next.js and GitHub integration. The main branch of the repository is connected directly to Vercel, so every merge automatically triggers a new production build. During deployment, Vercel installs dependencies, generates the Prisma client, applies database migrations, and builds the app with zero downtime.
This setup allows the team to focus on development while keeping deployment reliable and consistent.

## My Contributions

* Implemented custom restock preferences, allowing users to choose when items are added to the shopping list (e.g., eggs when half gone, berries when fully gone)

* Added a quick “Add to Shopping List” button on the pantry view for faster workflow

* Fixed issues with quantity and unit handling when adding items to shopping lists

* Improved expiration-related features and user flow

* Enhanced UI with fallback visuals when no item image is uploaded

These contributions focused on making Pantry Pals more practical, customizable, and easier to use in real-life situations.

[Pantry Pals Home page](https://pantry-pal-gamma.vercel.app/)

[Pantry Pals Website](https://pantry-pals.github.io/)

[Pantry Pals Source code](https://github.com/pantry-pals)

