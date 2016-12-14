FuseeProtobuf
=============

Customized protobuf-net library used for Fusee.

Build `Proto_FUSEE.sln`. This will generate several ouptuts. Two of them are used in FUSEE:

- `precompile/bin/Debug/precompile.exe` - This is the precompiler generating a Serializer class for any `[ProtoContract]` attributed 
   class found in a given dll. Copy this tool and all accompanying DLLs to `$(FuseeRoot)\ext\protobuf\PrecompileTool`.
- `protobuf-net_Portable\bin\Debug` - This is the stripped-down protobuf dll only containing the attributes (such as `[ProtoContract]`).
   Copy this DLL to `$(FuseeRoot)\ext\protobuf`. NOTE: This DLL is different to the DLL with the same name in the `PrecompileTool`
   subdirectory.


Fusee is licensed under the MIT license (see below). Repository: https://github.com/FUSEEProjectTeam/Fusee


-------------------------------------------------------------------------------


Fusee contains freely available open source software and assets. They are 
governed by their respective license terms and conditions. As the time of writing,
protobuf-net (https://code.google.com/p/protobuf-net/) by Marc Gravell is released
under the Apache License 2.0:


-------------------------------------------------------------------------------


The core Protocol Buffers technology is provided courtesy of Google.
At the time of writing, this is released under the BSD license.
Full details can be found here:

http://code.google.com/p/protobuf/


This .NET implementation is Copyright 2008 Marc Gravell

   Licensed under the Apache License, Version 2.0 (the "License");
   you may not use this file except in compliance with the License.
   You may obtain a copy of the License at

       http://www.apache.org/licenses/LICENSE-2.0

   Unless required by applicable law or agreed to in writing, software
   distributed under the License is distributed on an "AS IS" BASIS,
   WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
   See the License for the specific language governing permissions and
   limitations under the License.

   
-------------------------------------------------------------------------------


The MIT License (MIT)

Copyright (c) 2014 FuseeProjectTeam

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