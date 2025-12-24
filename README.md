# BiteBoond

Week 1: The "Foundation & Persistence" Sprint
Day 1: Scaffolding & The Map (Navigation)
Today is about setting the "Rules of the House."

What to do: Create a new Android Studio project (Empty Views Activity). Set up ViewBinding in your build.gradle. It’s cleaner than the old way and prevents null-pointer crashes.

The Navigation Graph: Create a nav_graph.xml. You need three main "Destinations":

HomeFragment: A list of your food items.

AddEditFragment: Where you type in the food name and expiry date.

RecipeFragment: Where the API data will eventually live.

SafeArgs: This is a requirement. Set it up so when you click an item in Home, it passes a foodId to AddEdit.
