# Hello Mojolicious Lite

## Summary
The purpose of this exercise is to get you familiar with setting up a Mojolicious Lite app and the basics of writing route handlers.

## Goals
- Define the following routes in your project file that will perform various geometric calculations:
    - `/rectangle/area`
    - `/rectangle/perimeter`
    - `/circle/area`
    - `/circle/perimeter`
- Each of the above routes will need to access variables in the querystring (height, width, radius) in order to calculate the result. Return the answer to the client in any HTML tag. 
- Next, define the following routes:
    - `/rectangle/area/:height/:width`
    - `/rectangle/perimeter/:height/:width`
    - `/circle/area/:radius`
    - `/circle/perimeter/:radius`
- These route should behave the same as the above routes, but they should get their input from these ordered URL parameters instead of the querystring. 