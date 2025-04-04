﻿

   --------------------------------------------------------------------------------
                    README file for JS Engine Switcher: V8 v3.29.1

   --------------------------------------------------------------------------------

      Copyright (c) 2013-2025 Andrey Taritsyn - http://www.taritsyn.ru


   ===========
   DESCRIPTION
   ===========
   JavaScriptEngineSwitcher.V8 contains a `V8JsEngine` adapter (wrapper for the
   Microsoft ClearScript.V8 (http://github.com/Microsoft/ClearScript) version
   7.5).

   This package does not contain the native ClearScript.V8 assemblies.
   Therefore, you need to choose and install the most appropriate package(s) for
   your platform. The following packages are available:

    * Microsoft.ClearScript.V8.Native.win-x86
    * Microsoft.ClearScript.V8.Native.win-x64
    * Microsoft.ClearScript.V8.Native.win-arm64
    * Microsoft.ClearScript.V8.Native.linux-x64
    * Microsoft.ClearScript.V8.Native.linux-arm
    * Microsoft.ClearScript.V8.Native.linux-arm64
    * Microsoft.ClearScript.V8.Native.osx-x64
    * Microsoft.ClearScript.V8.Native.osx-arm64

   =============
   RELEASE NOTES
   =============
   Performed a migration to a modern API for pre-compilation of scripts.

   =============
   DOCUMENTATION
   =============
   See documentation on GitHub -
   http://github.com/Taritsyn/JavaScriptEngineSwitcher