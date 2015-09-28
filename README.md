# cisco-lb-control
Control context written in Bash -  used for manipulating a Cisco ACE 4710 load balancer. One-off script and menu system created for pulling, activating or getting state of nodes.

<b>This project makes the following assumptions:</b>
<ol>
<li>you have cli access to your Cisco device
<li>you have access/sudo privs to a linux system with expect installed, and this linux system has route/access to your target device
<li>you have a copy of the core expect script provided by Cisco: http://docwiki.cisco.com/wiki/Remote_VTY_Command_Script
<li>you have knowledge of cisco lb interaction - cli or gui and understand lb concepts
</ol>

This project is broken up into two sets of directories containining scripts:
<ol>
<li>targetserver - used for one-off node manipulation: drop/bleed
<li>env - example of menu system used to drive farm manipulation: bleed only
</ol>
