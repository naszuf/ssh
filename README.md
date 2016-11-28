# ssh


-t

port forward

remote forward

"Vidd a portom messzi!"

local

"Portot ide hozzám!"

tunnel

## ssh escape seq

     ~.      Disconnect.

     ~^Z     Background ssh.

     ~#      List forwarded connections.

     ~&      Background ssh at logout when waiting for forwarded connection /
             X11 sessions to terminate.

     ~?      Display a list of escape characters.

     ~B      Send a BREAK to the remote system (only useful if the peer sup-
             ports it).

     ~C      Open command line.  Currently this allows the addition of port
             forwardings using the -L, -R and -D options (see above).  It also
             allows the cancellation of existing port-forwardings with
             -KL[bind_address:]port for local, -KR[bind_address:]port for
             remote and -KD[bind_address:]port for dynamic port-forwardings.
             !command allows the user to execute a local command if the
             PermitLocalCommand option is enabled in ssh_config(5).  Basic
             help is available, using the -h option.

     ~R      Request rekeying of the connection (only useful if the peer sup-
             ports it).

     ~V      Decrease the verbosity (LogLevel) when errors are being written
             to stderr.

     ~v      Increase the verbosity (LogLevel) when errors are being written
             to stderr.
ssh config
l
proxycommand
localcommand
tcpkeepalive
connectimeout
X11

authkey

allowuser


sshfs

putty
