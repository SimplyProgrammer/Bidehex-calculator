# Bidehex 1.0.0 (beta)

Release date: 10.27.2021 (Night)

What was added:
* Ability to convert between 3 most popular numeric systems.
* Ability to convert multiple numbers at once.
* Understanding of IPv4 format.
* Understanding of IPv6 format.
* Information about current numbers parameters.
#

# Bidehex 1.1.0

Release date: 11.1.2021 (Night)

What was added:
* Ability to perform basic arithmetic operations (add, subtract, multiply, divide, modulo, power)!
* Expression groups to define order precedence of expression!
* Simpler text field right click context menu!
* Application now can be downloaded as executable file or setup wizard that can install application as java independent!
* Small visual design changes!
* Small bugs fixed!
#

# Bidehex 1.2.0

Release date: Near future

What was added:
* Updating internal APIs to their latest version. Also updating Java from 8 -> 21
* Internal refactoring.
* Other fields are no longer updated in real-time as you type. Now they are updated after 1 sec delay. Pressing Enter will make the update instant.
  * Invalid input is no longer replaced instantly with the last valid input, it's replaced after 1 sec as well. This gives you time to make necessary changes. This improves user experience.
* Expression can now be evaluated (replaced by the result value) by Shift+Enter.
  * If the field contains an expression or value that is not in its respective base then the tooltip is going to be displayed with the proper/result values.
* 0-padding now works for in every input field not only in the binary one.
* Datatype recognition was greatly improved, now it can recognize:
  * IPv4:
    * A, B and C masks.
    * Broadcast address.
    * Some multicast addresses.
    * Loopback address.
    * Public/Private ip.
  * IPv6:
    * Broadcast address.
    * Some multicast addresses.
    * Loopback address.
    * Public/Private ip.
  * Physical 'MAC' address:
    * Broadcast address.
    * Can show you the vendor if you are connected to the internet.
* Partial DNS (IP from URL) lookup was implemented.
* Context menu (field right click) was improved, now it supports:
  * Copy and paste with specifiable delimiter that will be replaced from/to space (which is standard delimiter).
  * Ability to add a specified number of padding zeros to the specific field.
* Slight performance improvements.
#
