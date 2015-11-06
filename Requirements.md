# Introduction #

Every developer wants crash logs, but nobody wants to replicate Apple's crash catcher by themselves. Crash Kit is intended to be a drop-in framework that can be used to detect the presence of new crash logs for an application, present UI to the user and upload the crash log.

# Details #

  * Ease of adoption - this is why Sparkle is so widely used.
  * Works for applications and plug-ins to applications.
  * Supports Tiger and Leopard
  * Allows multiple methods of submission (email, HTTP POST, etc.)

## Not in Scope ##

This project will not produce:

  * A general server-side script or database for accepting crash reports. Although it is likely that such a project would be very welcome across the Mac development community, that is not the purpose of this project.