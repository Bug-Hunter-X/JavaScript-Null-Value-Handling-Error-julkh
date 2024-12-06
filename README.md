# JavaScript Null Value Handling Bug

This repository demonstrates a common error in JavaScript: improper handling of null values. The `foo` function doesn't properly handle cases where `a` or `b` might be null, which could lead to unexpected behavior or runtime errors.

## Bug

The original `foo` function lacks robust null checks.  This can cause issues if the function receives null arguments.  The solution demonstrates how to properly handle these cases.

## Solution

The solution includes explicit null checks and uses a more defensive approach, returning `null` when either `a` or `b` is `null`. This prevents potential errors.