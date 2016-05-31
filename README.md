# RSyncSnapshot
RSync Snapshot Script

RSyncSnapshot is a Bash Shell script that implements most of the features of RSnapshot, but is 1/30th the size.  It also doesn't require a 30MB+ Perl Interpreter installation, making it perfect for use on embedded Linux based platforms, like the FreeNAS server.

Usage: RSyncSnapshot Source_Directory Target_Directory Number_of_Snapshots_to_Keep Optional_Log_File
         Custom_Lock_File