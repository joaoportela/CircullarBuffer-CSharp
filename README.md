# Circular Buffer

[![Build Status](https://github.com/joaoportela/CircullarBuffer-CSharp/workflows/Build%20%26%20Test/badge.svg?branch=master)](https://github.com/joaoportela/CircularBuffer-CSharp/actions?query=workflow%3A%22Build+%26+Test%22)
[![nuget](https://img.shields.io/nuget/v/CircularBuffer)](https://www.nuget.org/packages/CircularBuffer/)

Simple implementation of a circular buffer in C#.
This is a single file implementation, which means that you only need to copy 
the CircularBuffer.cs file to your project and use it.

## What is a circular buffer? 

> A circular buffer, cyclic buffer or ring buffer is a data structure 
that uses a single, fixed-size buffer as if it were connected end-to-end.

This means that you have predefined memory usage. Push and Pop operations 
are always O(1). Index access is also O(1).

More info @ wikipedia: http://en.wikipedia.org/wiki/Circular_buffer
