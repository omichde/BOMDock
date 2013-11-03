# BOMDock

This is a small (AppleScript) application which will hide or show the dock icon of an OS-X application.

# Installation

Download BOMDock and drag any application onto its icon. BOMDock will display a first dialog with the current application icon state and wether to either hide or show its dock icon. If you proceed, the application will quit, the settings applied and the final result will be displayed. Finally you can  launch the application again.

In case the settings could not be applied witht the users permission, it'll ask you for administrative permissions.

# Background

I could not find a reliable Dock Icon settings application anymore, Dock Dodger is aging and not working for me under Mavericks. But I still wanted SpamSieve, xScope and DragThing to be removed from my dock. It basically runs `defaults read/write [APPPATH] LSUIElement [PARA]` in order to tweak the app Info.plist file.

# Version

**1.0**

- first release, tested on 10.9 (should work down to 10.6)

# Contact

Oliver Michalak - [oliver@werk01.de](mailto:oliver@werk01.de) - [@omichde](http://twitter.com/omichde)

## Keywords

OS-X, hide, show, dock, icon

## License

BOMDock is available under the MIT license:

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
