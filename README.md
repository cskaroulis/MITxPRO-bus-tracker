# Real Time Bus Tracker

## Description:

This project shows the bus route for the 77 bus running outbound from Harvard to Arlington Heights. The map marker moves outbound every second and stops at each bus stop.

List of improvements:

- Called the MBTA API to dynamically retrieve the list of bus stops outbound for bus route 77.
- Came up with a manual way to hide secrets when the source code is public and reintroduced secrets when running the code locally.
- Minimized the use of global variables by declaring useful variables in the main function and then passing them into the helper functions as parameters.

This project makes use of two APIs:

- [mapbox](https://docs.mapbox.com/) to draw the map
- [MBTA](https://api-v3.mbta.com/docs/swagger/index.html#/Stop/ApiWeb_StopController_index) to grab the bus data

## How to run

Open index.html in the browser.

## Future improvements

- Find a way to automatically handle secrets locally.
- Allow the user to define a range of time and show the actual time the bus arrives at each stop.
- Write tests for helper functions.

## License information

Copyright (c) 2012-2022 Colleen Skaroulis

Permission is hereby granted, free of charge, to any person obtaining
a copy of this software and associated documentation files (the
"Software"), to deal in the Software without restriction, including
without limitation the rights to use, copy, modify, merge, publish,
distribute, sublicense, and/or sell copies of the Software, and to
permit persons to whom the Software is furnished to do so, subject to
the following conditions:

The above copyright notice and this permission notice shall be
included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND,
EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF
MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND
NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE
LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION
OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION
WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
