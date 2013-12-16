GNOME session using the i3 window manager
=========================================

This allows you to easily switch between i3 and the default window manager
within a GNOME display manager.

To install, get the package, build it and install:

    git clone git@github.com:tommie/i3-wm-gnome-session.git i3-wm-gnome-session-1.0
    (cd i3-wm-gnome-session-1.0 && debuild -uc -us -b)
    dpkg -i i3-wm-gnome-session-1.0_all.deb

If this causes you any problems, or you think this is a bad way of doing
things, feel free not to use it. If you have improvements, please send
them as GitHub pull requests.

Published under the MIT license
-------------------------------
Copyright (c) 2013 Tommie Gannert

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
