# GLELogger 
A World of Warcraft addon library to provide logging services for addons

## Usage
- Copy the folder to your addon's lib folder
- Add to toc file: libs\GLELogger-1.0\GLELogger-1.0.xml

Example toc entries:
libs\LibStub\LibStub.lua
libs\GLELogger-1.0\GLELogger-1.0.xml

Use in addon :
local Logger = LibStub("GLELogger-1.0")

## Available methods:
### These methods will print out a message to the default chat frame:
- Logger:Error(src,msg)
- Logger:Warn(src,msg)
- Logger:Info(src,msg)
- Logger:Debug(src,msg)
- Logger:Trace(src,msg)

### Change the logging level
Logger:SetLogLevel(logLevel)

Default logging level is WARN

###### Valid logging levels:
1. ERROR
2. WARN
3. INFO
4. DEBUG
5. TRACE

### Returns current logging level
Logger:ShowLogLevel

## Dependancies
Requires LibStub