# React Native FlatList Performance Issue

This repository demonstrates a common performance issue encountered when using FlatList in React Native with large datasets. The component exhibits slow rendering and update times, leading to a poor user experience. The solution implemented uses `keyExtractor` and optimization techniques to address these performance issues. 

## Problem

The original `FlatList` implementation suffers from performance bottlenecks when dealing with a significant number of items. Scrolling becomes sluggish, updates are delayed, and the app may even freeze.

## Solution

The improved implementation uses a `keyExtractor` function to efficiently update and render only the necessary components. It also incorporates other optimization strategies to mitigate performance degradation. 

## Usage

1. Clone the repository.
2. Navigate to the project directory.
3. Run `npm install` to install dependencies.
4. Run `npx react-native run-android` or `npx react-native run-ios` to run the app.

Compare the performance of the original `FlatList` with the optimized one to observe the significant improvement.