check_damocles
==============

Checks the hwgroup damocles device.

### Usage

    check_damocles.pl -h

    check_damocles.pl -H <host> ( -S <sensor id> | -I <input id> | -O
    <output id> )

Options:

    -h      Display this helpmessage.
    -H      The hostname or ipaddress of the hwgroup device.
    -C      The snmp community of the hwgroup device.
    -S      The sensor to check
    -I      The dry contact to check
    -O      The relay output to check
    --man   Displays the complete perldoc manpage.

### Threshold formats

    start <= end
    
    Thresholds have to be specified from the lower level end on e.g. -w 20 is meaning that a warning error is occuring when the collected value is over 20.
