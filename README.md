# Unexpected Behavior of Swift's `map` Function

This example demonstrates a common misunderstanding of how Swift's `map` function operates.  Unlike some languages, `map` in Swift *doesn't* modify the original array; instead, it returns a *new* array containing the transformed elements.

This repository contains a Swift file demonstrating the behavior and a solution explaining how to achieve in-place modification if desired.