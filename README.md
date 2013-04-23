Copyright (C) 2012 Bitpay.com

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

About
	Bitcoin payment via bitpay.com for VirtueMart.

Version 0.1
	
System Requirements:
	Bitpay.com account
	VirtueMart
	PHP 5+
	Curl PHP Extension
  
Build Instructions:
  The VirtueMart Extension Manager expets a zip file for installation.  The
  contents of the zip file can be found in the upload subdirectory.  Create 
  a zip file of everything in the upload directory and then follow the 
  configuration instructions below.

Configuration Instructions:
-------
1. Go to Extensions > Extension Manager > Install
2. Browse and select zip file, click Upload & Install.
3. Go to Extensions > Extension Manager > Manage, and find the plugin, click on publish.
4. Go to Components > VirtueMart and click on Payment Methods.
5. Click New and type in the information, selecting VMPAYMENT_BITPAY as Payment Method.
6. Create an API Key in your bitpay account at bitpay.com.
7. Click Configuration tab and enter your API Key.
8. Click Save.

Tested against Joomla 2.5.9 and Virtuemart 2.0.20b
