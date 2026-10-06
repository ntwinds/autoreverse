================================================================================
                    AutoReverse - Binary Ninja Edition v1.0.0
================================================================================

AutoReverse is a high-performance native desktop binary analysis, reverse
engineering, and live instrumentation platform for Windows x64 executables.

--------------------------------------------------------------------------------
QUICK START
--------------------------------------------------------------------------------
1. Launch:
   Double-click "AutoReverse.exe" to start the application.

2. Load a Target:
   - Drag & drop any PE32 / PE32+ (x86 / x64) executable or DLL into the window.
   - Or press Ctrl+O (File -> Open).
   - Or press Ctrl+Alt+A (File -> Attach to Process) to inspect live memory.

3. Navigation:
   - Space: Toggle between Linear Disassembly and IDA-style Control Flow Graph.
   - F5: Decompile current function into pseudo-C.
   - Alt+3: Switch to raw Hex Viewer with ASCII side-by-side.
   - Ctrl+G: Jump directly to any Virtual Address or symbol offset.
   - Ctrl+E: Patch or assemble new machine instructions in-place.
   - Ctrl+Alt+S: Save modified / patched executable.

4. Kareem Model Context Protocol (MCP) AI Server:
   - Port: http://127.0.0.1:9099/mcp
   - Integrates with Claude Desktop, Cursor, Gemini, and Cline for autonomous
     reverse engineering, control flow analysis, and live bytecode patching.

--------------------------------------------------------------------------------
AUTO-UPDATER & BOOTSTRAPPER
--------------------------------------------------------------------------------
- Inside the app:
  Click Help -> Check for Updates... or Tools -> Check for Updates...
  AutoReverse queries GitHub Releases or your custom manifest URL, downloads the
  update package with live progress, and runs the bootstrapper.

- Standalone Bootstrapper:
  "AutoReverseBootstrapper.bat" is included to apply any update archive (.zip)
  in-place without requiring third-party tools or administrative installers.

--------------------------------------------------------------------------------
SYSTEM REQUIREMENTS
--------------------------------------------------------------------------------
- Windows 10 / Windows 11 (64-bit)
- No external runtime installations required (all Qt6 and Capstone DLLs included).
================================================================================


------
note

this was for faster and better analysis this features alot of stuff from your loving tools such as ida pro and binary ninja.
anyways have fun.
-------------------------------------------------------------------------------------------------------------------------------
