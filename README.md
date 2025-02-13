# Tailwind CSS Class Application Issue

This repository demonstrates a bug where certain Tailwind CSS classes are not being applied correctly.  The hover effect, specifically, is not working as expected.

## Problem

The `bg-red-500` class is applied initially but the `hover:bg-blue-700` class doesn't change the background color on hover.

## Solution

The solution involves checking for CSS specificity conflicts, ensuring correct Tailwind configuration, and verifying that JavaScript isn't overriding the styles.