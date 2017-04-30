# LumiSoft.Net
LumiSoft.Net bugfix branch - upgraded to mvs2015 .net 4.5.2

## CaptainPants branch
Hi everyone,

I was interested in a fairly straightforward FTP server component in C# to use on a personal project. The original branch of this was the best that I could find. It hasn't been updated since 2012 so probably safe to consider it dead unfortunately. There are a few other branches that people have made some spot fixes on but none I would call a successor at this stage. 

This library has a lot of interesting network components that I'm curious to tinker with. I made this branch mostly to fix a bug I found in the FTP_Session handling of RNFR that caused renames to timeout and fail 100% of the time.

## License
The original author included this license

> General usage terms:
> 
>   *) If you use/redistribute compiled binary, there are no restrictions.
>      You can use it in any project, commercial and no-commercial.
>      Redistributing compiled binary not limited any way.
> 
>   *) It's allowed to complile source code parts to your application,
>      but then you may not rename class names and namespaces.
> 
>   *) Anything is possible, if special agreement between LumiSoft.
> 
> THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, 
> INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR 
> PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE 
> FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, 
> ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
