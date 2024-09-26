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

# Bidehex 1.1.5

Release date: Near future

What was added:
* Updating internal APIs to their latest version. Also updating Java from 8 -> 21
* Internal refactoring.
* Other fields are no longer updated in real-time. Now they are updated after 1 sec delay, pressing Enter will make the update instant.
  * Invalid input is also no longer replaced instantly with the last valid input, it's removed after 1 sec after the user has finished timing which gives better user experience.
* Expression can now be evaluated (replaced by the result value) by Shift+Enter.
  * If the field contains an expression or value that is not in its respective base then tooltip is going to be displayed with the proper values.
* 0-padding now works for in every input field not only the binary one.
* Datatype information prompts were greatly improved, now it can recognize:
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
* Partial DNS lookup for URLs was implemented.
* Slight performance improvements.
#
