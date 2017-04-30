# LumiSoft.Net
LumiSoft.Net bugfix branch - upgraded to mvs2015 .net 4.5.2

Hi everyone,

I was interested in a fairly straightforward FTP server component in C# to use on a personal project. The original branch of this was the best that I could find. It hasn't been updated since 2012 so probably safe to consider it dead unfortunately. There are a few other branches that people have made some spot fixes on but none I would call a successor at this stage. 

This library has a lot of interesting network components that I'm curious to tinker with. I made this branch mostly to fix a bug I found in the FTP_Session handling of RNFR that caused renames to timeout and fail 100% of the time.

