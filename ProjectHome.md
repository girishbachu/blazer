### From 0 to AMF messages generation and fuzzing in just few clicks ###

**Blazer** is a custom [AMF messages](http://en.wikipedia.org/wiki/Action_Message_Format) generator with fuzzing capabilities, developed as [Burp Suite](http://portswigger.net/burp/) plugin. It is designed and implemented to make AMF testing easy, and yet allows researchers to control fully the entire security testing process.

Using Blazer, testing AMF-based applications is easier and more robust. As it is highly integrated in a well-known testing suite, web security practitioners can start using the tool with minimal setup in few seconds.

**Please note that Blazer code is now hosted on Github:** https://github.com/ikkisoft/blazer

![http://i.imgur.com/VEfrW.png](http://i.imgur.com/VEfrW.png)

Blazer implements a new testing approach, introduced at [Black Hat USA 2012](http://www.blackhat.com/usa/bh-us-12-briefings.html#Carettoni). This automated gray-box testing technique allows security researchers to improve the coverage and the effectiveness of fuzzing efforts targeting complex applications.

For further details, please refer to the original [whitepaper](http://blazer.googlecode.com/files/BH2012_LucaCarettoni_WP_FINAL.pdf) and [presentation](http://blazer.googlecode.com/files/BH2012_LucaCarettoni_PRESO_FINAL.pdf).
Another recent presentation is available on [SlideShare](http://www.slideshare.net/ikkisoft/amf-testing-made-easy-deepsec-2012).

#### Features ####
  * Automatic Java objects generation from method signatures via Java reflection and "best-fit" heuristics
  * Fuzzing capabilities, with customizable data pools and attack vectors
  * Ability to start, pause, restore and stop testing
  * Easy-to-use internal methods to construct custom AMF messages
  * Embedded [BeanShell](http://www.beanshell.org/) for manual testing
  * Highly integrated in Burp Suite
  * JARs, classes and Java src import feature
  * AMF request/response export functionality (AMF2XML)
  * Sandbox feature using a custom security manager
  * Support for Java server-side remoting technologies ([Adobe BlazeDS](http://sourceforge.net/adobe/blazeds/wiki/Home/), [Adobe LiveCycle Data Services](http://www.adobe.com/products/livecycle/dataservices/), [GraniteDS](http://www.graniteds.org/confluence/pages/viewpage.action?pageId=229378), ...)

Blazer has been developed in Java as a [Burp Suite plugin](http://portswigger.net/burp/extender/) and released under the [GNU General Public License](http://www.gnu.org/licenses/). Burp plugins are supported by both versions (free and professional) of the Burp Suite. All major operating systems (Windows, Mac, Linux) with standard Oracle JRE installed are supported by Blazer.

#### News ####

  * **02/03/13** - [DeepSec](https://deepsec.net/) release v0.3 is out!
  * **08/01/12** - "AMF testing with Blazer" videos uploaded
  * **07/31/12** - Initial release v0.2
  * **07/31/12** - Initial project content entered