The X_settings.sui file contains most of the info the old def file used to hold. 

The _a and _b file are the cab specific files that link to the appropriate tobj file for the main skin. SCS uses _a to refer to Highline and _b to refer to normal cab.

IF the skin is the same for both cab sizes then you can drop the _a and _b suffixes and just use the one sii for both and remove the Suitible_for line. 