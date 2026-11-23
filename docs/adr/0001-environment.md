# Development environment

Status: Accepted · Date: 2026-11-23

## Context

### Model

MacBook Pro 2019 16"

### RAM

16 GB 2667 MHz DDR4

### Graphics

AMD Radeon Pro 5500M 4 GB
Intel UHD Graphics 630 1536 MB

### CPU

2,3 GHz Intel Core i9 de 8 núcleos

## Decision taken

### Docker

Why I choose docker? Because it let me use the programs in my mac without the need to make partitions and install other OS's. It is the more straightforward and easiest way to start, and when you want to start anything new the less friction is the better.

The tradeoff is that docker don't let me use my AMD Radeon graphic, I will need to test the performance and see if I can go ahead with this setup.

## Other options

### New partition with linux

Discarded because I don't want to install another OS in my mac and start doing partitions and so on. It's complicated and at this point, overengineering. Also my mac model has some components that are not very compatible with linux, they are already known problems with the Radeon and other components.
