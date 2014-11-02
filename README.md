matlab-ssh2
===========

SSH/SFTP/SCP For Matlab (v2)
This is a git copy for github of the Mathworks File Exchange version of SSH2 for Matlab.

A new Matlab interface for using the Ganymed-SS2 Java library. Renamed commands are improved for limitations of existing Matlab/SSH2 codebase (see inspired submissions) using a straightforward command list. 
If you need to access a remote machine from your Matlab session (for near-real time data transfer etc...) this set of functions allows you to send commands and obtain the return values. SFTP and SCP file transfer functions are included. Supports public key authentication and improved multiple command support.

This requires the open-source Ganymed SSH-2 for Java that is freely available and automatically included in the zip file. For SFTP-GET, one must modify the ssh2_setup.m to use the included custom Ganymed SSH-2 Java library that is compatible with Matlab. Otherwise, the official Ganymed library will be downloaded automatically on first use.

See ssh2-examples.m for documentation.

FOR SUPPORT, PLEASE CONTACT AUTHOR DIRECTLY instead of posting to "Comments and Ratings" first. Helpful information or comments can be posted after communication to ensure useful information for others instead of a ballooning of failed SSH/SFTP/SCP connection info in the comments.

Additionally, I would love to hear about how and where you're using this submission in the comments section.

