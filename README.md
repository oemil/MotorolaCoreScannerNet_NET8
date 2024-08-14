# Update Motorola / Zebra CoreScanner Driver Wrapper for .NET 8

Fork of original driver adapted to work with .NET version 8.

Minor adjustments within code to make the wrapper work again:
- Handling of images within System.Drawing.Common library to prevent the need for additional 3rd party libraries
- Extended Commands\Default.cs to enable persistance of custom device parameters, as well as factory reset.


# Original Readme: Motorola / Zebra CoreScanner Driver Wrapper

C# Wrapper for the Motorola CoreScanner Driver. 

Makes using the Motorola / Zebra Scanners much easier (handles much of the duplicate code and XML for you).

Visit website for documentation.
http://fortelinea.github.io/MotorolaCoreScannerNet/

#The MIT License (MIT)

Copyright (c) 2013 Fortelinea Software Systems, Inc.

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.
