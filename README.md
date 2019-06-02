# GLELogger 
To use:
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

###Returns current logging level
Logger:ShowLogLevel

## Dependancies
Requires LibStub