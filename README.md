CropperView
=============

...


### Installation
Add the files to your project manually by dragging the CropperView directory into your Xcode project.


### Usage

```
// Import the class
#import "CropperView.h"

...

// ---------------------------------------------------
// ex) get CropperView in UIViewController or UIView or ...
// ---------------------------------------------------
    // add UIViewController
    CropperView * cropperView = [[CropperView alloc] initWithFrame:self.view.bounds];
    [cropperView addCropper:CGRectMake(10, 10, 100, 100)];    // <- draw rect {{10, 10}, {100, 100}}
    [cropperView addCropper:CGRectMake(130, 130, 100, 100)];  // <- do you want it multi rect, add rect
    [self.view addSubview:cropperView];

```


License
-------------------------------------------------------
The MIT License (MIT)

Copyright (c) 2014 JoongKwan Choi

JKLib

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

