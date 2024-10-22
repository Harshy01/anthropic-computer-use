┌──(four7㉿kali)-[~/Anthropic/anthropic-computer-use]
└─$ sudo docker run \
    -e ANTHROPIC_API_KEY=$ANTHROPIC_API_KEY \
    -v $HOME/.anthropic:/home/computeruse/.anthropic \
    -p 5900:5900 \
    -p 8501:8501 \
    -p 6080:6080 \
    -p 8080:8080 \
    -it ghcr.io/anthropics/anthropic-quickstarts:computer-use-demo-latest

Unable to find image 'ghcr.io/anthropics/anthropic-quickstarts:computer-use-demo-latest' locally
computer-use-demo-latest: Pulling from anthropics/anthropic-quickstarts
6414378b6477: Pull complete
2d7f28854791: Pull complete
46b34d436c7c: Pull complete
287dc4a54b39: Pull complete
d432e42f3468: Pull complete
4f4fb700ef54: Pull complete
52eed1865290: Pull complete
0475c8d1e6b9: Pull complete
e5e90442ea93: Pull complete
7fd469838d18: Pull complete
f9496f7c947e: Pull complete
8f2506d2bc14: Pull complete
d516a2b6c133: Pull complete
Digest: sha256:fb3111afa5a8157f08c2807f2d4093760de87704df3a29b813f6f393131b75a0
Status: Downloaded newer image for ghcr.io/anthropics/anthropic-quickstarts:computer-use-demo-latest
^B"^B"^B"Xvfb started successfully on display :1
Xvfb PID: 9
starting tint2 on display :1 ...
starting mutter
starting vnc
PORT=5900
starting noVNC
noVNC started successfully
✨ Computer Use Demo is ready!
➡️  Open http://localhost:8080 in your browser to begin
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:32:27 No client after 60 secs.
22/10/2024 22:32:27 deleted 32 tile_row polling images.
starting vnc
PORT=5900
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:34:42 passing arg to libvncserver: -rfbport
22/10/2024 22:34:42 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:34:43 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 542
22/10/2024 22:34:43 Using X display :1
22/10/2024 22:34:43 rootwin: 0x50d reswin: 0x800001 dpy: 0xa97d55b0
22/10/2024 22:34:43
22/10/2024 22:34:43 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:34:43
22/10/2024 22:34:43 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:34:43   If this yields undesired behavior (poor response, painting
22/10/2024 22:34:43   errors, etc) it may be disabled:
22/10/2024 22:34:43    - use '-nowf' to disable wireframing completely.
22/10/2024 22:34:43    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:34:43      moved window is released in the new position.
22/10/2024 22:34:43   Also see the -help entry for tuning parameters.
22/10/2024 22:34:43   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:34:43   repaint the screen, also see the -fixscreen option for
22/10/2024 22:34:43   periodic repaints.
22/10/2024 22:34:43 GrabServer control via XTEST.
22/10/2024 22:34:43
22/10/2024 22:34:43 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:34:43   use RECORD extension to try to detect scrolling windows
22/10/2024 22:34:43   (induced by either user keystroke or mouse input).
22/10/2024 22:34:43   If this yields undesired behavior (poor response, painting
22/10/2024 22:34:43   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:34:43   Also see the -help entry for tuning parameters.
22/10/2024 22:34:43   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:34:43   repaint the screen, also see the -fixscreen option for
22/10/2024 22:34:43   periodic repaints.
22/10/2024 22:34:43
22/10/2024 22:34:43 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:34:43   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:34:43   Automatically switching to -xkb mode.
22/10/2024 22:34:43   If this makes the key mapping worse you can
22/10/2024 22:34:43   disable it with the "-noxkb" option.
22/10/2024 22:34:43   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:34:43
22/10/2024 22:34:43 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:34:43 X display is not capable of DPMS.
22/10/2024 22:34:43 --------------------------------------------------------
22/10/2024 22:34:43
22/10/2024 22:34:43 Default visual ID: 0x21
22/10/2024 22:34:43 Read initial data from X display into framebuffer.
22/10/2024 22:34:43 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:34:43
22/10/2024 22:34:43 X display :1 is 32bpp depth=24 true color
22/10/2024 22:34:43
22/10/2024 22:34:43 ListenOnTCPPort: Address already in use
22/10/2024 22:34:43 listen6: bind: Address already in use
22/10/2024 22:34:43 Not listening on IPv6 interface.
22/10/2024 22:34:43
22/10/2024 22:34:43 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:34:43 Xinerama: number of sub-screens: 1
22/10/2024 22:34:43 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:34:43
22/10/2024 22:34:43 fb read rate: 1795 MB/sec
22/10/2024 22:34:43 fast read: reset -defer ms to: 10
22/10/2024 22:34:43 The X server says there are 10 mouse buttons.
22/10/2024 22:34:43 Error: could not obtain listening port.
22/10/2024 22:34:43 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:34:47 passing arg to libvncserver: -rfbport
22/10/2024 22:34:47 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:34:48 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 598
22/10/2024 22:34:48 Using X display :1
22/10/2024 22:34:48 rootwin: 0x50d reswin: 0x800001 dpy: 0x893a45b0
22/10/2024 22:34:48
22/10/2024 22:34:48 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:34:48
22/10/2024 22:34:48 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:34:48   If this yields undesired behavior (poor response, painting
22/10/2024 22:34:48   errors, etc) it may be disabled:
22/10/2024 22:34:48    - use '-nowf' to disable wireframing completely.
22/10/2024 22:34:48    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:34:48      moved window is released in the new position.
22/10/2024 22:34:48   Also see the -help entry for tuning parameters.
22/10/2024 22:34:48   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:34:48   repaint the screen, also see the -fixscreen option for
22/10/2024 22:34:48   periodic repaints.
22/10/2024 22:34:48 GrabServer control via XTEST.
22/10/2024 22:34:48
22/10/2024 22:34:48 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:34:48   use RECORD extension to try to detect scrolling windows
22/10/2024 22:34:48   (induced by either user keystroke or mouse input).
22/10/2024 22:34:48   If this yields undesired behavior (poor response, painting
22/10/2024 22:34:48   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:34:48   Also see the -help entry for tuning parameters.
22/10/2024 22:34:48   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:34:48   repaint the screen, also see the -fixscreen option for
22/10/2024 22:34:48   periodic repaints.
22/10/2024 22:34:48
22/10/2024 22:34:48 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:34:48   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:34:48   Automatically switching to -xkb mode.
22/10/2024 22:34:48   If this makes the key mapping worse you can
22/10/2024 22:34:48   disable it with the "-noxkb" option.
22/10/2024 22:34:48   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:34:48
22/10/2024 22:34:48 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:34:48 X display is not capable of DPMS.
22/10/2024 22:34:48 --------------------------------------------------------
22/10/2024 22:34:48
22/10/2024 22:34:48 Default visual ID: 0x21
22/10/2024 22:34:48 Read initial data from X display into framebuffer.
22/10/2024 22:34:48 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:34:48
22/10/2024 22:34:48 X display :1 is 32bpp depth=24 true color
22/10/2024 22:34:48
22/10/2024 22:34:48 ListenOnTCPPort: Address already in use
22/10/2024 22:34:48 listen6: bind: Address already in use
22/10/2024 22:34:48 Not listening on IPv6 interface.
22/10/2024 22:34:48
22/10/2024 22:34:48 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:34:48 Xinerama: number of sub-screens: 1
22/10/2024 22:34:48 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:34:48
22/10/2024 22:34:48 fb read rate: 1964 MB/sec
22/10/2024 22:34:48 fast read: reset -defer ms to: 10
22/10/2024 22:34:48 The X server says there are 10 mouse buttons.
22/10/2024 22:34:48 Error: could not obtain listening port.
22/10/2024 22:34:48 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:34:52 passing arg to libvncserver: -rfbport
22/10/2024 22:34:52 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:34:53 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 606
22/10/2024 22:34:53 Using X display :1
22/10/2024 22:34:53 rootwin: 0x50d reswin: 0x800001 dpy: 0x32be65b0
22/10/2024 22:34:53
22/10/2024 22:34:53 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:34:53
22/10/2024 22:34:53 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:34:53   If this yields undesired behavior (poor response, painting
22/10/2024 22:34:53   errors, etc) it may be disabled:
22/10/2024 22:34:53    - use '-nowf' to disable wireframing completely.
22/10/2024 22:34:53    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:34:53      moved window is released in the new position.
22/10/2024 22:34:53   Also see the -help entry for tuning parameters.
22/10/2024 22:34:53   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:34:53   repaint the screen, also see the -fixscreen option for
22/10/2024 22:34:53   periodic repaints.
22/10/2024 22:34:53 GrabServer control via XTEST.
22/10/2024 22:34:53
22/10/2024 22:34:53 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:34:53   use RECORD extension to try to detect scrolling windows
22/10/2024 22:34:53   (induced by either user keystroke or mouse input).
22/10/2024 22:34:53   If this yields undesired behavior (poor response, painting
22/10/2024 22:34:53   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:34:53   Also see the -help entry for tuning parameters.
22/10/2024 22:34:53   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:34:53   repaint the screen, also see the -fixscreen option for
22/10/2024 22:34:53   periodic repaints.
22/10/2024 22:34:53
22/10/2024 22:34:53 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:34:53   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:34:53   Automatically switching to -xkb mode.
22/10/2024 22:34:53   If this makes the key mapping worse you can
22/10/2024 22:34:53   disable it with the "-noxkb" option.
22/10/2024 22:34:53   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:34:53
22/10/2024 22:34:53 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:34:53 X display is not capable of DPMS.
22/10/2024 22:34:53 --------------------------------------------------------
22/10/2024 22:34:53
22/10/2024 22:34:53 Default visual ID: 0x21
22/10/2024 22:34:53 Read initial data from X display into framebuffer.
22/10/2024 22:34:53 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:34:53
22/10/2024 22:34:53 X display :1 is 32bpp depth=24 true color
22/10/2024 22:34:53
22/10/2024 22:34:53 ListenOnTCPPort: Address already in use
22/10/2024 22:34:53 listen6: bind: Address already in use
22/10/2024 22:34:53 Not listening on IPv6 interface.
22/10/2024 22:34:53
22/10/2024 22:34:53 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:34:53 Xinerama: number of sub-screens: 1
22/10/2024 22:34:53 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:34:53
22/10/2024 22:34:53 fb read rate: 2134 MB/sec
22/10/2024 22:34:53 fast read: reset -defer ms to: 10
22/10/2024 22:34:53 The X server says there are 10 mouse buttons.
22/10/2024 22:34:53 Error: could not obtain listening port.
22/10/2024 22:34:53 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:34:57 passing arg to libvncserver: -rfbport
22/10/2024 22:34:57 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:34:58 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 615
22/10/2024 22:34:58 Using X display :1
22/10/2024 22:34:58 rootwin: 0x50d reswin: 0x800001 dpy: 0x8f5a05b0
22/10/2024 22:34:58
22/10/2024 22:34:58 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:34:58
22/10/2024 22:34:58 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:34:58   If this yields undesired behavior (poor response, painting
22/10/2024 22:34:58   errors, etc) it may be disabled:
22/10/2024 22:34:58    - use '-nowf' to disable wireframing completely.
22/10/2024 22:34:58    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:34:58      moved window is released in the new position.
22/10/2024 22:34:58   Also see the -help entry for tuning parameters.
22/10/2024 22:34:58   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:34:58   repaint the screen, also see the -fixscreen option for
22/10/2024 22:34:58   periodic repaints.
22/10/2024 22:34:58 GrabServer control via XTEST.
22/10/2024 22:34:58
22/10/2024 22:34:58 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:34:58   use RECORD extension to try to detect scrolling windows
22/10/2024 22:34:58   (induced by either user keystroke or mouse input).
22/10/2024 22:34:58   If this yields undesired behavior (poor response, painting
22/10/2024 22:34:58   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:34:58   Also see the -help entry for tuning parameters.
22/10/2024 22:34:58   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:34:58   repaint the screen, also see the -fixscreen option for
22/10/2024 22:34:58   periodic repaints.
22/10/2024 22:34:58
22/10/2024 22:34:58 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:34:58   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:34:58   Automatically switching to -xkb mode.
22/10/2024 22:34:58   If this makes the key mapping worse you can
22/10/2024 22:34:58   disable it with the "-noxkb" option.
22/10/2024 22:34:58   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:34:58
22/10/2024 22:34:58 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:34:58 X display is not capable of DPMS.
22/10/2024 22:34:58 --------------------------------------------------------
22/10/2024 22:34:58
22/10/2024 22:34:58 Default visual ID: 0x21
22/10/2024 22:34:58 Read initial data from X display into framebuffer.
22/10/2024 22:34:58 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:34:58
22/10/2024 22:34:58 X display :1 is 32bpp depth=24 true color
22/10/2024 22:34:58
22/10/2024 22:34:58 ListenOnTCPPort: Address already in use
22/10/2024 22:34:58 listen6: bind: Address already in use
22/10/2024 22:34:58 Not listening on IPv6 interface.
22/10/2024 22:34:58
22/10/2024 22:34:58 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:34:58 Xinerama: number of sub-screens: 1
22/10/2024 22:34:58 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:34:58
22/10/2024 22:34:58 fb read rate: 2482 MB/sec
22/10/2024 22:34:58 fast read: reset -defer ms to: 10
22/10/2024 22:34:58 The X server says there are 10 mouse buttons.
22/10/2024 22:34:58 Error: could not obtain listening port.
22/10/2024 22:34:58 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:02 passing arg to libvncserver: -rfbport
22/10/2024 22:35:02 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:03 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 624
22/10/2024 22:35:03 Using X display :1
22/10/2024 22:35:03 rootwin: 0x50d reswin: 0x800001 dpy: 0xb55a25b0
22/10/2024 22:35:03
22/10/2024 22:35:03 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:03
22/10/2024 22:35:03 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:03   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:03   errors, etc) it may be disabled:
22/10/2024 22:35:03    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:03    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:03      moved window is released in the new position.
22/10/2024 22:35:03   Also see the -help entry for tuning parameters.
22/10/2024 22:35:03   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:03   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:03   periodic repaints.
22/10/2024 22:35:03 GrabServer control via XTEST.
22/10/2024 22:35:03
22/10/2024 22:35:03 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:03   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:03   (induced by either user keystroke or mouse input).
22/10/2024 22:35:03   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:03   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:03   Also see the -help entry for tuning parameters.
22/10/2024 22:35:03   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:03   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:03   periodic repaints.
22/10/2024 22:35:03
22/10/2024 22:35:03 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:03   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:03   Automatically switching to -xkb mode.
22/10/2024 22:35:03   If this makes the key mapping worse you can
22/10/2024 22:35:03   disable it with the "-noxkb" option.
22/10/2024 22:35:03   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:03
22/10/2024 22:35:03 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:03 X display is not capable of DPMS.
22/10/2024 22:35:03 --------------------------------------------------------
22/10/2024 22:35:03
22/10/2024 22:35:03 Default visual ID: 0x21
22/10/2024 22:35:03 Read initial data from X display into framebuffer.
22/10/2024 22:35:03 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:03
22/10/2024 22:35:03 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:03
22/10/2024 22:35:03 ListenOnTCPPort: Address already in use
22/10/2024 22:35:03 listen6: bind: Address already in use
22/10/2024 22:35:03 Not listening on IPv6 interface.
22/10/2024 22:35:03
22/10/2024 22:35:03 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:03 Xinerama: number of sub-screens: 1
22/10/2024 22:35:03 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:03
22/10/2024 22:35:03 fb read rate: 2599 MB/sec
22/10/2024 22:35:03 fast read: reset -defer ms to: 10
22/10/2024 22:35:03 The X server says there are 10 mouse buttons.
22/10/2024 22:35:03 Error: could not obtain listening port.
22/10/2024 22:35:03 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:07 passing arg to libvncserver: -rfbport
22/10/2024 22:35:07 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:08 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 632
22/10/2024 22:35:08 Using X display :1
22/10/2024 22:35:08 rootwin: 0x50d reswin: 0x800001 dpy: 0x6f63b5b0
22/10/2024 22:35:08
22/10/2024 22:35:08 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:08
22/10/2024 22:35:08 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:08   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:08   errors, etc) it may be disabled:
22/10/2024 22:35:08    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:08    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:08      moved window is released in the new position.
22/10/2024 22:35:08   Also see the -help entry for tuning parameters.
22/10/2024 22:35:08   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:08   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:08   periodic repaints.
22/10/2024 22:35:08 GrabServer control via XTEST.
22/10/2024 22:35:08
22/10/2024 22:35:08 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:08   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:08   (induced by either user keystroke or mouse input).
22/10/2024 22:35:08   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:08   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:08   Also see the -help entry for tuning parameters.
22/10/2024 22:35:08   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:08   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:08   periodic repaints.
22/10/2024 22:35:08
22/10/2024 22:35:08 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:08   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:08   Automatically switching to -xkb mode.
22/10/2024 22:35:08   If this makes the key mapping worse you can
22/10/2024 22:35:08   disable it with the "-noxkb" option.
22/10/2024 22:35:08   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:08
22/10/2024 22:35:08 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:08 X display is not capable of DPMS.
22/10/2024 22:35:08 --------------------------------------------------------
22/10/2024 22:35:08
22/10/2024 22:35:08 Default visual ID: 0x21
22/10/2024 22:35:08 Read initial data from X display into framebuffer.
22/10/2024 22:35:08 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:08
22/10/2024 22:35:08 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:08
22/10/2024 22:35:08 ListenOnTCPPort: Address already in use
22/10/2024 22:35:08 listen6: bind: Address already in use
22/10/2024 22:35:08 Not listening on IPv6 interface.
22/10/2024 22:35:08
22/10/2024 22:35:08 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:08 Xinerama: number of sub-screens: 1
22/10/2024 22:35:08 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:08
22/10/2024 22:35:08 fb read rate: 2545 MB/sec
22/10/2024 22:35:08 fast read: reset -defer ms to: 10
22/10/2024 22:35:08 The X server says there are 10 mouse buttons.
22/10/2024 22:35:08 Error: could not obtain listening port.
22/10/2024 22:35:08 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:12 passing arg to libvncserver: -rfbport
22/10/2024 22:35:12 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:13 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 640
22/10/2024 22:35:13 Using X display :1
22/10/2024 22:35:13 rootwin: 0x50d reswin: 0x800001 dpy: 0x112855b0
22/10/2024 22:35:13
22/10/2024 22:35:13 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:13
22/10/2024 22:35:13 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:13   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:13   errors, etc) it may be disabled:
22/10/2024 22:35:13    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:13    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:13      moved window is released in the new position.
22/10/2024 22:35:13   Also see the -help entry for tuning parameters.
22/10/2024 22:35:13   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:13   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:13   periodic repaints.
22/10/2024 22:35:13 GrabServer control via XTEST.
22/10/2024 22:35:13
22/10/2024 22:35:13 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:13   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:13   (induced by either user keystroke or mouse input).
22/10/2024 22:35:13   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:13   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:13   Also see the -help entry for tuning parameters.
22/10/2024 22:35:13   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:13   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:13   periodic repaints.
22/10/2024 22:35:13
22/10/2024 22:35:13 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:13   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:13   Automatically switching to -xkb mode.
22/10/2024 22:35:13   If this makes the key mapping worse you can
22/10/2024 22:35:13   disable it with the "-noxkb" option.
22/10/2024 22:35:13   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:13
22/10/2024 22:35:13 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:13 X display is not capable of DPMS.
22/10/2024 22:35:13 --------------------------------------------------------
22/10/2024 22:35:13
22/10/2024 22:35:13 Default visual ID: 0x21
22/10/2024 22:35:13 Read initial data from X display into framebuffer.
22/10/2024 22:35:13 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:13
22/10/2024 22:35:13 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:13
22/10/2024 22:35:13 ListenOnTCPPort: Address already in use
22/10/2024 22:35:13 listen6: bind: Address already in use
22/10/2024 22:35:13 Not listening on IPv6 interface.
22/10/2024 22:35:13
22/10/2024 22:35:13 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:13 Xinerama: number of sub-screens: 1
22/10/2024 22:35:13 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:13
22/10/2024 22:35:13 fb read rate: 1911 MB/sec
22/10/2024 22:35:13 fast read: reset -defer ms to: 10
22/10/2024 22:35:13 The X server says there are 10 mouse buttons.
22/10/2024 22:35:13 Error: could not obtain listening port.
22/10/2024 22:35:13 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:17 passing arg to libvncserver: -rfbport
22/10/2024 22:35:17 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:18 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 648
22/10/2024 22:35:18 Using X display :1
22/10/2024 22:35:18 rootwin: 0x50d reswin: 0x800001 dpy: 0xd34225b0
22/10/2024 22:35:18
22/10/2024 22:35:18 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:18
22/10/2024 22:35:18 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:18   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:18   errors, etc) it may be disabled:
22/10/2024 22:35:18    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:18    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:18      moved window is released in the new position.
22/10/2024 22:35:18   Also see the -help entry for tuning parameters.
22/10/2024 22:35:18   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:18   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:18   periodic repaints.
22/10/2024 22:35:18 GrabServer control via XTEST.
22/10/2024 22:35:18
22/10/2024 22:35:18 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:18   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:18   (induced by either user keystroke or mouse input).
22/10/2024 22:35:18   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:18   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:18   Also see the -help entry for tuning parameters.
22/10/2024 22:35:18   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:18   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:18   periodic repaints.
22/10/2024 22:35:18
22/10/2024 22:35:18 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:18   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:18   Automatically switching to -xkb mode.
22/10/2024 22:35:18   If this makes the key mapping worse you can
22/10/2024 22:35:18   disable it with the "-noxkb" option.
22/10/2024 22:35:18   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:18
22/10/2024 22:35:18 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:18 X display is not capable of DPMS.
22/10/2024 22:35:18 --------------------------------------------------------
22/10/2024 22:35:18
22/10/2024 22:35:18 Default visual ID: 0x21
22/10/2024 22:35:18 Read initial data from X display into framebuffer.
22/10/2024 22:35:18 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:18
22/10/2024 22:35:18 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:18
22/10/2024 22:35:18 ListenOnTCPPort: Address already in use
22/10/2024 22:35:18 listen6: bind: Address already in use
22/10/2024 22:35:18 Not listening on IPv6 interface.
22/10/2024 22:35:18
22/10/2024 22:35:18 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:18 Xinerama: number of sub-screens: 1
22/10/2024 22:35:18 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:18
22/10/2024 22:35:18 fb read rate: 2314 MB/sec
22/10/2024 22:35:18 fast read: reset -defer ms to: 10
22/10/2024 22:35:18 The X server says there are 10 mouse buttons.
22/10/2024 22:35:18 Error: could not obtain listening port.
22/10/2024 22:35:18 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:22 passing arg to libvncserver: -rfbport
22/10/2024 22:35:22 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:23 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 656
22/10/2024 22:35:23 Using X display :1
22/10/2024 22:35:23 rootwin: 0x50d reswin: 0x800001 dpy: 0x139a55b0
22/10/2024 22:35:23
22/10/2024 22:35:23 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:23
22/10/2024 22:35:23 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:23   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:23   errors, etc) it may be disabled:
22/10/2024 22:35:23    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:23    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:23      moved window is released in the new position.
22/10/2024 22:35:23   Also see the -help entry for tuning parameters.
22/10/2024 22:35:23   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:23   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:23   periodic repaints.
22/10/2024 22:35:23 GrabServer control via XTEST.
22/10/2024 22:35:23
22/10/2024 22:35:23 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:23   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:23   (induced by either user keystroke or mouse input).
22/10/2024 22:35:23   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:23   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:23   Also see the -help entry for tuning parameters.
22/10/2024 22:35:23   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:23   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:23   periodic repaints.
22/10/2024 22:35:23
22/10/2024 22:35:23 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:23   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:23   Automatically switching to -xkb mode.
22/10/2024 22:35:23   If this makes the key mapping worse you can
22/10/2024 22:35:23   disable it with the "-noxkb" option.
22/10/2024 22:35:23   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:23
22/10/2024 22:35:23 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:23 X display is not capable of DPMS.
22/10/2024 22:35:23 --------------------------------------------------------
22/10/2024 22:35:23
22/10/2024 22:35:23 Default visual ID: 0x21
22/10/2024 22:35:23 Read initial data from X display into framebuffer.
22/10/2024 22:35:23 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:23
22/10/2024 22:35:23 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:23
22/10/2024 22:35:23 ListenOnTCPPort: Address already in use
22/10/2024 22:35:23 listen6: bind: Address already in use
22/10/2024 22:35:23 Not listening on IPv6 interface.
22/10/2024 22:35:23
22/10/2024 22:35:23 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:23 Xinerama: number of sub-screens: 1
22/10/2024 22:35:23 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:23
22/10/2024 22:35:23 fb read rate: 2421 MB/sec
22/10/2024 22:35:23 fast read: reset -defer ms to: 10
22/10/2024 22:35:23 The X server says there are 10 mouse buttons.
22/10/2024 22:35:23 Error: could not obtain listening port.
22/10/2024 22:35:23 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:27 passing arg to libvncserver: -rfbport
22/10/2024 22:35:27 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:28 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 664
22/10/2024 22:35:28 Using X display :1
22/10/2024 22:35:28 rootwin: 0x50d reswin: 0x800001 dpy: 0x458bb5b0
22/10/2024 22:35:28
22/10/2024 22:35:28 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:28
22/10/2024 22:35:28 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:28   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:28   errors, etc) it may be disabled:
22/10/2024 22:35:28    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:28    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:28      moved window is released in the new position.
22/10/2024 22:35:28   Also see the -help entry for tuning parameters.
22/10/2024 22:35:28   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:28   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:28   periodic repaints.
22/10/2024 22:35:28 GrabServer control via XTEST.
22/10/2024 22:35:28
22/10/2024 22:35:28 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:28   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:28   (induced by either user keystroke or mouse input).
22/10/2024 22:35:28   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:28   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:28   Also see the -help entry for tuning parameters.
22/10/2024 22:35:28   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:28   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:28   periodic repaints.
22/10/2024 22:35:28
22/10/2024 22:35:28 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:28   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:28   Automatically switching to -xkb mode.
22/10/2024 22:35:28   If this makes the key mapping worse you can
22/10/2024 22:35:28   disable it with the "-noxkb" option.
22/10/2024 22:35:28   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:28
22/10/2024 22:35:28 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:28 X display is not capable of DPMS.
22/10/2024 22:35:28 --------------------------------------------------------
22/10/2024 22:35:28
22/10/2024 22:35:28 Default visual ID: 0x21
22/10/2024 22:35:28 Read initial data from X display into framebuffer.
22/10/2024 22:35:28 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:28
22/10/2024 22:35:28 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:28
22/10/2024 22:35:28 ListenOnTCPPort: Address already in use
22/10/2024 22:35:28 listen6: bind: Address already in use
22/10/2024 22:35:28 Not listening on IPv6 interface.
22/10/2024 22:35:28
22/10/2024 22:35:28 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:28 Xinerama: number of sub-screens: 1
22/10/2024 22:35:28 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:28
22/10/2024 22:35:28 fb read rate: 2301 MB/sec
22/10/2024 22:35:28 fast read: reset -defer ms to: 10
22/10/2024 22:35:28 The X server says there are 10 mouse buttons.
22/10/2024 22:35:28 Error: could not obtain listening port.
22/10/2024 22:35:28 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:32 passing arg to libvncserver: -rfbport
22/10/2024 22:35:32 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:33 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 673
22/10/2024 22:35:33 Using X display :1
22/10/2024 22:35:33 rootwin: 0x50d reswin: 0x800001 dpy: 0xe3eb55b0
22/10/2024 22:35:33
22/10/2024 22:35:33 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:33
22/10/2024 22:35:33 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:33   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:33   errors, etc) it may be disabled:
22/10/2024 22:35:33    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:33    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:33      moved window is released in the new position.
22/10/2024 22:35:33   Also see the -help entry for tuning parameters.
22/10/2024 22:35:33   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:33   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:33   periodic repaints.
22/10/2024 22:35:33 GrabServer control via XTEST.
22/10/2024 22:35:33
22/10/2024 22:35:33 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:33   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:33   (induced by either user keystroke or mouse input).
22/10/2024 22:35:33   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:33   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:33   Also see the -help entry for tuning parameters.
22/10/2024 22:35:33   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:33   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:33   periodic repaints.
22/10/2024 22:35:33
22/10/2024 22:35:33 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:33   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:33   Automatically switching to -xkb mode.
22/10/2024 22:35:33   If this makes the key mapping worse you can
22/10/2024 22:35:33   disable it with the "-noxkb" option.
22/10/2024 22:35:33   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:33
22/10/2024 22:35:33 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:33 X display is not capable of DPMS.
22/10/2024 22:35:33 --------------------------------------------------------
22/10/2024 22:35:33
22/10/2024 22:35:33 Default visual ID: 0x21
22/10/2024 22:35:33 Read initial data from X display into framebuffer.
22/10/2024 22:35:33 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:33
22/10/2024 22:35:33 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:33
22/10/2024 22:35:33 ListenOnTCPPort: Address already in use
22/10/2024 22:35:33 listen6: bind: Address already in use
22/10/2024 22:35:33 Not listening on IPv6 interface.
22/10/2024 22:35:33
22/10/2024 22:35:33 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:33 Xinerama: number of sub-screens: 1
22/10/2024 22:35:33 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:33
22/10/2024 22:35:33 fb read rate: 2250 MB/sec
22/10/2024 22:35:33 fast read: reset -defer ms to: 10
22/10/2024 22:35:33 The X server says there are 10 mouse buttons.
22/10/2024 22:35:33 Error: could not obtain listening port.
22/10/2024 22:35:33 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:37 passing arg to libvncserver: -rfbport
22/10/2024 22:35:37 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:38 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 681
22/10/2024 22:35:38 Using X display :1
22/10/2024 22:35:38 rootwin: 0x50d reswin: 0x800001 dpy: 0x3268f5b0
22/10/2024 22:35:38
22/10/2024 22:35:38 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:38
22/10/2024 22:35:38 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:38   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:38   errors, etc) it may be disabled:
22/10/2024 22:35:38    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:38    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:38      moved window is released in the new position.
22/10/2024 22:35:38   Also see the -help entry for tuning parameters.
22/10/2024 22:35:38   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:38   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:38   periodic repaints.
22/10/2024 22:35:38 GrabServer control via XTEST.
22/10/2024 22:35:38
22/10/2024 22:35:38 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:38   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:38   (induced by either user keystroke or mouse input).
22/10/2024 22:35:38   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:38   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:38   Also see the -help entry for tuning parameters.
22/10/2024 22:35:38   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:38   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:38   periodic repaints.
22/10/2024 22:35:38
22/10/2024 22:35:38 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:38   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:38   Automatically switching to -xkb mode.
22/10/2024 22:35:38   If this makes the key mapping worse you can
22/10/2024 22:35:38   disable it with the "-noxkb" option.
22/10/2024 22:35:38   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:38
22/10/2024 22:35:38 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:38 X display is not capable of DPMS.
22/10/2024 22:35:38 --------------------------------------------------------
22/10/2024 22:35:38
22/10/2024 22:35:38 Default visual ID: 0x21
22/10/2024 22:35:38 Read initial data from X display into framebuffer.
22/10/2024 22:35:38 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:38
22/10/2024 22:35:38 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:38
22/10/2024 22:35:38 ListenOnTCPPort: Address already in use
22/10/2024 22:35:38 listen6: bind: Address already in use
22/10/2024 22:35:38 Not listening on IPv6 interface.
22/10/2024 22:35:38
22/10/2024 22:35:38 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:38 Xinerama: number of sub-screens: 1
22/10/2024 22:35:38 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:38
22/10/2024 22:35:38 fb read rate: 2307 MB/sec
22/10/2024 22:35:38 fast read: reset -defer ms to: 10
22/10/2024 22:35:38 The X server says there are 10 mouse buttons.
22/10/2024 22:35:38 Error: could not obtain listening port.
22/10/2024 22:35:38 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:42 passing arg to libvncserver: -rfbport
22/10/2024 22:35:42 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:43 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 689
22/10/2024 22:35:43 Using X display :1
22/10/2024 22:35:43 rootwin: 0x50d reswin: 0x800001 dpy: 0xbf2cb5b0
22/10/2024 22:35:43
22/10/2024 22:35:43 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:43
22/10/2024 22:35:43 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:43   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:43   errors, etc) it may be disabled:
22/10/2024 22:35:43    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:43    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:43      moved window is released in the new position.
22/10/2024 22:35:43   Also see the -help entry for tuning parameters.
22/10/2024 22:35:43   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:43   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:43   periodic repaints.
22/10/2024 22:35:43 GrabServer control via XTEST.
22/10/2024 22:35:43
22/10/2024 22:35:43 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:43   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:43   (induced by either user keystroke or mouse input).
22/10/2024 22:35:43   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:43   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:43   Also see the -help entry for tuning parameters.
22/10/2024 22:35:43   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:43   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:43   periodic repaints.
22/10/2024 22:35:43
22/10/2024 22:35:43 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:43   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:43   Automatically switching to -xkb mode.
22/10/2024 22:35:43   If this makes the key mapping worse you can
22/10/2024 22:35:43   disable it with the "-noxkb" option.
22/10/2024 22:35:43   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:43
22/10/2024 22:35:43 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:43 X display is not capable of DPMS.
22/10/2024 22:35:43 --------------------------------------------------------
22/10/2024 22:35:43
22/10/2024 22:35:43 Default visual ID: 0x21
22/10/2024 22:35:43 Read initial data from X display into framebuffer.
22/10/2024 22:35:43 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:43
22/10/2024 22:35:43 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:43
22/10/2024 22:35:43 ListenOnTCPPort: Address already in use
22/10/2024 22:35:43 listen6: bind: Address already in use
22/10/2024 22:35:43 Not listening on IPv6 interface.
22/10/2024 22:35:43
22/10/2024 22:35:43 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:43 Xinerama: number of sub-screens: 1
22/10/2024 22:35:43 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:43
22/10/2024 22:35:43 fb read rate: 1873 MB/sec
22/10/2024 22:35:43 fast read: reset -defer ms to: 10
22/10/2024 22:35:43 The X server says there are 10 mouse buttons.
22/10/2024 22:35:43 Error: could not obtain listening port.
22/10/2024 22:35:43 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:47 passing arg to libvncserver: -rfbport
22/10/2024 22:35:47 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:48 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 697
22/10/2024 22:35:48 Using X display :1
22/10/2024 22:35:48 rootwin: 0x50d reswin: 0x800001 dpy: 0xb4ee45b0
22/10/2024 22:35:48
22/10/2024 22:35:48 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:48
22/10/2024 22:35:48 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:48   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:48   errors, etc) it may be disabled:
22/10/2024 22:35:48    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:48    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:48      moved window is released in the new position.
22/10/2024 22:35:48   Also see the -help entry for tuning parameters.
22/10/2024 22:35:48   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:48   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:48   periodic repaints.
22/10/2024 22:35:48 GrabServer control via XTEST.
22/10/2024 22:35:48
22/10/2024 22:35:48 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:48   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:48   (induced by either user keystroke or mouse input).
22/10/2024 22:35:48   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:48   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:48   Also see the -help entry for tuning parameters.
22/10/2024 22:35:48   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:48   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:48   periodic repaints.
22/10/2024 22:35:48
22/10/2024 22:35:48 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:48   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:48   Automatically switching to -xkb mode.
22/10/2024 22:35:48   If this makes the key mapping worse you can
22/10/2024 22:35:48   disable it with the "-noxkb" option.
22/10/2024 22:35:48   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:48
22/10/2024 22:35:48 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:48 X display is not capable of DPMS.
22/10/2024 22:35:48 --------------------------------------------------------
22/10/2024 22:35:48
22/10/2024 22:35:48 Default visual ID: 0x21
22/10/2024 22:35:48 Read initial data from X display into framebuffer.
22/10/2024 22:35:48 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:48
22/10/2024 22:35:48 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:48
22/10/2024 22:35:48 ListenOnTCPPort: Address already in use
22/10/2024 22:35:48 listen6: bind: Address already in use
22/10/2024 22:35:48 Not listening on IPv6 interface.
22/10/2024 22:35:48
22/10/2024 22:35:48 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:48 Xinerama: number of sub-screens: 1
22/10/2024 22:35:48 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:48
22/10/2024 22:35:48 fb read rate: 2462 MB/sec
22/10/2024 22:35:48 fast read: reset -defer ms to: 10
22/10/2024 22:35:48 The X server says there are 10 mouse buttons.
22/10/2024 22:35:48 Error: could not obtain listening port.
22/10/2024 22:35:48 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:52 passing arg to libvncserver: -rfbport
22/10/2024 22:35:52 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:53 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 705
22/10/2024 22:35:53 Using X display :1
22/10/2024 22:35:53 rootwin: 0x50d reswin: 0x800001 dpy: 0xe4b175b0
22/10/2024 22:35:53
22/10/2024 22:35:53 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:53
22/10/2024 22:35:53 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:53   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:53   errors, etc) it may be disabled:
22/10/2024 22:35:53    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:53    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:53      moved window is released in the new position.
22/10/2024 22:35:53   Also see the -help entry for tuning parameters.
22/10/2024 22:35:53   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:53   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:53   periodic repaints.
22/10/2024 22:35:53 GrabServer control via XTEST.
22/10/2024 22:35:53
22/10/2024 22:35:53 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:53   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:53   (induced by either user keystroke or mouse input).
22/10/2024 22:35:53   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:53   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:53   Also see the -help entry for tuning parameters.
22/10/2024 22:35:53   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:53   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:53   periodic repaints.
22/10/2024 22:35:53
22/10/2024 22:35:53 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:53   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:53   Automatically switching to -xkb mode.
22/10/2024 22:35:53   If this makes the key mapping worse you can
22/10/2024 22:35:53   disable it with the "-noxkb" option.
22/10/2024 22:35:53   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:53
22/10/2024 22:35:53 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:53 X display is not capable of DPMS.
22/10/2024 22:35:53 --------------------------------------------------------
22/10/2024 22:35:53
22/10/2024 22:35:53 Default visual ID: 0x21
22/10/2024 22:35:53 Read initial data from X display into framebuffer.
22/10/2024 22:35:53 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:53
22/10/2024 22:35:53 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:53
22/10/2024 22:35:53 ListenOnTCPPort: Address already in use
22/10/2024 22:35:53 listen6: bind: Address already in use
22/10/2024 22:35:53 Not listening on IPv6 interface.
22/10/2024 22:35:53
22/10/2024 22:35:53 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:53 Xinerama: number of sub-screens: 1
22/10/2024 22:35:53 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:53
22/10/2024 22:35:53 fb read rate: 2340 MB/sec
22/10/2024 22:35:53 fast read: reset -defer ms to: 10
22/10/2024 22:35:53 The X server says there are 10 mouse buttons.
22/10/2024 22:35:53 Error: could not obtain listening port.
22/10/2024 22:35:53 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:35:57 passing arg to libvncserver: -rfbport
22/10/2024 22:35:57 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:35:58 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 713
22/10/2024 22:35:58 Using X display :1
22/10/2024 22:35:58 rootwin: 0x50d reswin: 0x800001 dpy: 0x36f215b0
22/10/2024 22:35:58
22/10/2024 22:35:58 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:35:58
22/10/2024 22:35:58 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:35:58   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:58   errors, etc) it may be disabled:
22/10/2024 22:35:58    - use '-nowf' to disable wireframing completely.
22/10/2024 22:35:58    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:35:58      moved window is released in the new position.
22/10/2024 22:35:58   Also see the -help entry for tuning parameters.
22/10/2024 22:35:58   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:58   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:58   periodic repaints.
22/10/2024 22:35:58 GrabServer control via XTEST.
22/10/2024 22:35:58
22/10/2024 22:35:58 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:35:58   use RECORD extension to try to detect scrolling windows
22/10/2024 22:35:58   (induced by either user keystroke or mouse input).
22/10/2024 22:35:58   If this yields undesired behavior (poor response, painting
22/10/2024 22:35:58   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:35:58   Also see the -help entry for tuning parameters.
22/10/2024 22:35:58   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:35:58   repaint the screen, also see the -fixscreen option for
22/10/2024 22:35:58   periodic repaints.
22/10/2024 22:35:58
22/10/2024 22:35:58 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:35:58   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:35:58   Automatically switching to -xkb mode.
22/10/2024 22:35:58   If this makes the key mapping worse you can
22/10/2024 22:35:58   disable it with the "-noxkb" option.
22/10/2024 22:35:58   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:35:58
22/10/2024 22:35:58 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:35:58 X display is not capable of DPMS.
22/10/2024 22:35:58 --------------------------------------------------------
22/10/2024 22:35:58
22/10/2024 22:35:58 Default visual ID: 0x21
22/10/2024 22:35:58 Read initial data from X display into framebuffer.
22/10/2024 22:35:58 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:35:58
22/10/2024 22:35:58 X display :1 is 32bpp depth=24 true color
22/10/2024 22:35:58
22/10/2024 22:35:58 ListenOnTCPPort: Address already in use
22/10/2024 22:35:58 listen6: bind: Address already in use
22/10/2024 22:35:58 Not listening on IPv6 interface.
22/10/2024 22:35:58
22/10/2024 22:35:58 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:35:58 Xinerama: number of sub-screens: 1
22/10/2024 22:35:58 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:35:58
22/10/2024 22:35:58 fb read rate: 2216 MB/sec
22/10/2024 22:35:58 fast read: reset -defer ms to: 10
22/10/2024 22:35:58 The X server says there are 10 mouse buttons.
22/10/2024 22:35:58 Error: could not obtain listening port.
22/10/2024 22:35:58 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:02 passing arg to libvncserver: -rfbport
22/10/2024 22:36:02 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:03 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 721
22/10/2024 22:36:03 Using X display :1
22/10/2024 22:36:03 rootwin: 0x50d reswin: 0x800001 dpy: 0x87ba15b0
22/10/2024 22:36:03
22/10/2024 22:36:03 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:03
22/10/2024 22:36:03 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:03   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:03   errors, etc) it may be disabled:
22/10/2024 22:36:03    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:03    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:03      moved window is released in the new position.
22/10/2024 22:36:03   Also see the -help entry for tuning parameters.
22/10/2024 22:36:03   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:03   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:03   periodic repaints.
22/10/2024 22:36:03 GrabServer control via XTEST.
22/10/2024 22:36:03
22/10/2024 22:36:03 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:03   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:03   (induced by either user keystroke or mouse input).
22/10/2024 22:36:03   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:03   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:03   Also see the -help entry for tuning parameters.
22/10/2024 22:36:03   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:03   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:03   periodic repaints.
22/10/2024 22:36:03
22/10/2024 22:36:03 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:03   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:03   Automatically switching to -xkb mode.
22/10/2024 22:36:03   If this makes the key mapping worse you can
22/10/2024 22:36:03   disable it with the "-noxkb" option.
22/10/2024 22:36:03   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:03
22/10/2024 22:36:03 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:03 X display is not capable of DPMS.
22/10/2024 22:36:03 --------------------------------------------------------
22/10/2024 22:36:03
22/10/2024 22:36:03 Default visual ID: 0x21
22/10/2024 22:36:03 Read initial data from X display into framebuffer.
22/10/2024 22:36:03 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:03
22/10/2024 22:36:03 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:03
22/10/2024 22:36:03 ListenOnTCPPort: Address already in use
22/10/2024 22:36:03 listen6: bind: Address already in use
22/10/2024 22:36:03 Not listening on IPv6 interface.
22/10/2024 22:36:03
22/10/2024 22:36:03 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:03 Xinerama: number of sub-screens: 1
22/10/2024 22:36:03 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:03
22/10/2024 22:36:03 fb read rate: 2028 MB/sec
22/10/2024 22:36:03 fast read: reset -defer ms to: 10
22/10/2024 22:36:03 The X server says there are 10 mouse buttons.
22/10/2024 22:36:03 Error: could not obtain listening port.
22/10/2024 22:36:03 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:07 passing arg to libvncserver: -rfbport
22/10/2024 22:36:07 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:08 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 729
22/10/2024 22:36:08 Using X display :1
22/10/2024 22:36:08 rootwin: 0x50d reswin: 0x800001 dpy: 0xc02f75b0
22/10/2024 22:36:08
22/10/2024 22:36:08 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:08
22/10/2024 22:36:08 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:08   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:08   errors, etc) it may be disabled:
22/10/2024 22:36:08    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:08    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:08      moved window is released in the new position.
22/10/2024 22:36:08   Also see the -help entry for tuning parameters.
22/10/2024 22:36:08   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:08   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:08   periodic repaints.
22/10/2024 22:36:08 GrabServer control via XTEST.
22/10/2024 22:36:08
22/10/2024 22:36:08 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:08   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:08   (induced by either user keystroke or mouse input).
22/10/2024 22:36:08   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:08   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:08   Also see the -help entry for tuning parameters.
22/10/2024 22:36:08   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:08   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:08   periodic repaints.
22/10/2024 22:36:08
22/10/2024 22:36:08 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:08   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:08   Automatically switching to -xkb mode.
22/10/2024 22:36:08   If this makes the key mapping worse you can
22/10/2024 22:36:08   disable it with the "-noxkb" option.
22/10/2024 22:36:08   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:08
22/10/2024 22:36:08 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:08 X display is not capable of DPMS.
22/10/2024 22:36:08 --------------------------------------------------------
22/10/2024 22:36:08
22/10/2024 22:36:08 Default visual ID: 0x21
22/10/2024 22:36:08 Read initial data from X display into framebuffer.
22/10/2024 22:36:08 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:08
22/10/2024 22:36:08 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:08
22/10/2024 22:36:08 ListenOnTCPPort: Address already in use
22/10/2024 22:36:08 listen6: bind: Address already in use
22/10/2024 22:36:08 Not listening on IPv6 interface.
22/10/2024 22:36:08
22/10/2024 22:36:08 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:08 Xinerama: number of sub-screens: 1
22/10/2024 22:36:08 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:08
22/10/2024 22:36:08 fb read rate: 1545 MB/sec
22/10/2024 22:36:08 fast read: reset -defer ms to: 10
22/10/2024 22:36:08 The X server says there are 10 mouse buttons.
22/10/2024 22:36:08 Error: could not obtain listening port.
22/10/2024 22:36:08 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:12 passing arg to libvncserver: -rfbport
22/10/2024 22:36:12 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:13 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 737
22/10/2024 22:36:13 Using X display :1
22/10/2024 22:36:13 rootwin: 0x50d reswin: 0x800001 dpy: 0x7deb25b0
22/10/2024 22:36:13
22/10/2024 22:36:13 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:13
22/10/2024 22:36:13 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:13   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:13   errors, etc) it may be disabled:
22/10/2024 22:36:13    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:13    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:13      moved window is released in the new position.
22/10/2024 22:36:13   Also see the -help entry for tuning parameters.
22/10/2024 22:36:13   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:13   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:13   periodic repaints.
22/10/2024 22:36:13 GrabServer control via XTEST.
22/10/2024 22:36:13
22/10/2024 22:36:13 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:13   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:13   (induced by either user keystroke or mouse input).
22/10/2024 22:36:13   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:13   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:13   Also see the -help entry for tuning parameters.
22/10/2024 22:36:13   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:13   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:13   periodic repaints.
22/10/2024 22:36:13
22/10/2024 22:36:13 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:13   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:13   Automatically switching to -xkb mode.
22/10/2024 22:36:13   If this makes the key mapping worse you can
22/10/2024 22:36:13   disable it with the "-noxkb" option.
22/10/2024 22:36:13   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:13
22/10/2024 22:36:13 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:13 X display is not capable of DPMS.
22/10/2024 22:36:13 --------------------------------------------------------
22/10/2024 22:36:13
22/10/2024 22:36:13 Default visual ID: 0x21
22/10/2024 22:36:13 Read initial data from X display into framebuffer.
22/10/2024 22:36:13 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:13
22/10/2024 22:36:13 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:13
22/10/2024 22:36:13 ListenOnTCPPort: Address already in use
22/10/2024 22:36:13 listen6: bind: Address already in use
22/10/2024 22:36:13 Not listening on IPv6 interface.
22/10/2024 22:36:13
22/10/2024 22:36:13 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:13 Xinerama: number of sub-screens: 1
22/10/2024 22:36:13 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:13
22/10/2024 22:36:13 fb read rate: 1269 MB/sec
22/10/2024 22:36:13 fast read: reset -defer ms to: 10
22/10/2024 22:36:13 The X server says there are 10 mouse buttons.
22/10/2024 22:36:13 Error: could not obtain listening port.
22/10/2024 22:36:13 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:17 passing arg to libvncserver: -rfbport
22/10/2024 22:36:17 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:18 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 745
22/10/2024 22:36:18 Using X display :1
22/10/2024 22:36:18 rootwin: 0x50d reswin: 0x800001 dpy: 0x30cd65b0
22/10/2024 22:36:18
22/10/2024 22:36:18 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:18
22/10/2024 22:36:18 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:18   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:18   errors, etc) it may be disabled:
22/10/2024 22:36:18    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:18    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:18      moved window is released in the new position.
22/10/2024 22:36:18   Also see the -help entry for tuning parameters.
22/10/2024 22:36:18   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:18   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:18   periodic repaints.
22/10/2024 22:36:18 GrabServer control via XTEST.
22/10/2024 22:36:18
22/10/2024 22:36:18 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:18   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:18   (induced by either user keystroke or mouse input).
22/10/2024 22:36:18   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:18   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:18   Also see the -help entry for tuning parameters.
22/10/2024 22:36:18   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:18   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:18   periodic repaints.
22/10/2024 22:36:18
22/10/2024 22:36:18 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:18   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:18   Automatically switching to -xkb mode.
22/10/2024 22:36:18   If this makes the key mapping worse you can
22/10/2024 22:36:18   disable it with the "-noxkb" option.
22/10/2024 22:36:18   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:18
22/10/2024 22:36:18 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:18 X display is not capable of DPMS.
22/10/2024 22:36:18 --------------------------------------------------------
22/10/2024 22:36:18
22/10/2024 22:36:18 Default visual ID: 0x21
22/10/2024 22:36:18 Read initial data from X display into framebuffer.
22/10/2024 22:36:18 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:18
22/10/2024 22:36:18 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:18
22/10/2024 22:36:18 ListenOnTCPPort: Address already in use
22/10/2024 22:36:18 listen6: bind: Address already in use
22/10/2024 22:36:18 Not listening on IPv6 interface.
22/10/2024 22:36:18
22/10/2024 22:36:18 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:18 Xinerama: number of sub-screens: 1
22/10/2024 22:36:18 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:18
22/10/2024 22:36:18 fb read rate: 1235 MB/sec
22/10/2024 22:36:18 fast read: reset -defer ms to: 10
22/10/2024 22:36:18 The X server says there are 10 mouse buttons.
22/10/2024 22:36:18 Error: could not obtain listening port.
22/10/2024 22:36:18 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:22 passing arg to libvncserver: -rfbport
22/10/2024 22:36:22 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:23 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 753
22/10/2024 22:36:23 Using X display :1
22/10/2024 22:36:23 rootwin: 0x50d reswin: 0x800001 dpy: 0x807ca5b0
22/10/2024 22:36:23
22/10/2024 22:36:23 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:23
22/10/2024 22:36:23 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:23   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:23   errors, etc) it may be disabled:
22/10/2024 22:36:23    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:23    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:23      moved window is released in the new position.
22/10/2024 22:36:23   Also see the -help entry for tuning parameters.
22/10/2024 22:36:23   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:23   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:23   periodic repaints.
22/10/2024 22:36:23 GrabServer control via XTEST.
22/10/2024 22:36:23
22/10/2024 22:36:23 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:23   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:23   (induced by either user keystroke or mouse input).
22/10/2024 22:36:23   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:23   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:23   Also see the -help entry for tuning parameters.
22/10/2024 22:36:23   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:23   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:23   periodic repaints.
22/10/2024 22:36:23
22/10/2024 22:36:23 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:23   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:23   Automatically switching to -xkb mode.
22/10/2024 22:36:23   If this makes the key mapping worse you can
22/10/2024 22:36:23   disable it with the "-noxkb" option.
22/10/2024 22:36:23   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:23
22/10/2024 22:36:23 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:23 X display is not capable of DPMS.
22/10/2024 22:36:23 --------------------------------------------------------
22/10/2024 22:36:23
22/10/2024 22:36:23 Default visual ID: 0x21
22/10/2024 22:36:23 Read initial data from X display into framebuffer.
22/10/2024 22:36:23 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:23
22/10/2024 22:36:23 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:23
22/10/2024 22:36:23 ListenOnTCPPort: Address already in use
22/10/2024 22:36:23 listen6: bind: Address already in use
22/10/2024 22:36:23 Not listening on IPv6 interface.
22/10/2024 22:36:23
22/10/2024 22:36:23 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:23 Xinerama: number of sub-screens: 1
22/10/2024 22:36:23 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:23
22/10/2024 22:36:23 fb read rate: 1087 MB/sec
22/10/2024 22:36:23 fast read: reset -defer ms to: 10
22/10/2024 22:36:23 The X server says there are 10 mouse buttons.
22/10/2024 22:36:23 Error: could not obtain listening port.
22/10/2024 22:36:23 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:27 passing arg to libvncserver: -rfbport
22/10/2024 22:36:27 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:28 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 761
22/10/2024 22:36:28 Using X display :1
22/10/2024 22:36:28 rootwin: 0x50d reswin: 0x800001 dpy: 0x6ad0d5b0
22/10/2024 22:36:28
22/10/2024 22:36:28 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:28
22/10/2024 22:36:28 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:28   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:28   errors, etc) it may be disabled:
22/10/2024 22:36:28    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:28    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:28      moved window is released in the new position.
22/10/2024 22:36:28   Also see the -help entry for tuning parameters.
22/10/2024 22:36:28   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:28   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:28   periodic repaints.
22/10/2024 22:36:28 GrabServer control via XTEST.
22/10/2024 22:36:28
22/10/2024 22:36:28 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:28   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:28   (induced by either user keystroke or mouse input).
22/10/2024 22:36:28   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:28   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:28   Also see the -help entry for tuning parameters.
22/10/2024 22:36:28   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:28   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:28   periodic repaints.
22/10/2024 22:36:28
22/10/2024 22:36:28 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:28   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:28   Automatically switching to -xkb mode.
22/10/2024 22:36:28   If this makes the key mapping worse you can
22/10/2024 22:36:28   disable it with the "-noxkb" option.
22/10/2024 22:36:28   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:28
22/10/2024 22:36:28 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:28 X display is not capable of DPMS.
22/10/2024 22:36:28 --------------------------------------------------------
22/10/2024 22:36:28
22/10/2024 22:36:28 Default visual ID: 0x21
22/10/2024 22:36:28 Read initial data from X display into framebuffer.
22/10/2024 22:36:28 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:28
22/10/2024 22:36:28 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:28
22/10/2024 22:36:28 ListenOnTCPPort: Address already in use
22/10/2024 22:36:28 listen6: bind: Address already in use
22/10/2024 22:36:28 Not listening on IPv6 interface.
22/10/2024 22:36:28
22/10/2024 22:36:28 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:28 Xinerama: number of sub-screens: 1
22/10/2024 22:36:28 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:28
22/10/2024 22:36:28 fb read rate: 1506 MB/sec
22/10/2024 22:36:28 fast read: reset -defer ms to: 10
22/10/2024 22:36:28 The X server says there are 10 mouse buttons.
22/10/2024 22:36:28 Error: could not obtain listening port.
22/10/2024 22:36:28 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:32 passing arg to libvncserver: -rfbport
22/10/2024 22:36:32 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:33 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 769
22/10/2024 22:36:33 Using X display :1
22/10/2024 22:36:33 rootwin: 0x50d reswin: 0x800001 dpy: 0x4ae815b0
22/10/2024 22:36:33
22/10/2024 22:36:33 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:33
22/10/2024 22:36:33 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:33   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:33   errors, etc) it may be disabled:
22/10/2024 22:36:33    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:33    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:33      moved window is released in the new position.
22/10/2024 22:36:33   Also see the -help entry for tuning parameters.
22/10/2024 22:36:33   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:33   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:33   periodic repaints.
22/10/2024 22:36:33 GrabServer control via XTEST.
22/10/2024 22:36:33
22/10/2024 22:36:33 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:33   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:33   (induced by either user keystroke or mouse input).
22/10/2024 22:36:33   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:33   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:33   Also see the -help entry for tuning parameters.
22/10/2024 22:36:33   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:33   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:33   periodic repaints.
22/10/2024 22:36:33
22/10/2024 22:36:33 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:33   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:33   Automatically switching to -xkb mode.
22/10/2024 22:36:33   If this makes the key mapping worse you can
22/10/2024 22:36:33   disable it with the "-noxkb" option.
22/10/2024 22:36:33   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:33
22/10/2024 22:36:33 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:33 X display is not capable of DPMS.
22/10/2024 22:36:33 --------------------------------------------------------
22/10/2024 22:36:33
22/10/2024 22:36:33 Default visual ID: 0x21
22/10/2024 22:36:33 Read initial data from X display into framebuffer.
22/10/2024 22:36:33 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:33
22/10/2024 22:36:33 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:33
22/10/2024 22:36:33 ListenOnTCPPort: Address already in use
22/10/2024 22:36:33 listen6: bind: Address already in use
22/10/2024 22:36:33 Not listening on IPv6 interface.
22/10/2024 22:36:33
22/10/2024 22:36:33 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:33 Xinerama: number of sub-screens: 1
22/10/2024 22:36:33 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:33
22/10/2024 22:36:33 fb read rate: 1291 MB/sec
22/10/2024 22:36:33 fast read: reset -defer ms to: 10
22/10/2024 22:36:33 The X server says there are 10 mouse buttons.
22/10/2024 22:36:33 Error: could not obtain listening port.
22/10/2024 22:36:33 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:37 passing arg to libvncserver: -rfbport
22/10/2024 22:36:37 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:38 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 777
22/10/2024 22:36:38 Using X display :1
22/10/2024 22:36:38 rootwin: 0x50d reswin: 0x800001 dpy: 0xda89b5b0
22/10/2024 22:36:38
22/10/2024 22:36:38 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:38
22/10/2024 22:36:38 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:38   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:38   errors, etc) it may be disabled:
22/10/2024 22:36:38    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:38    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:38      moved window is released in the new position.
22/10/2024 22:36:38   Also see the -help entry for tuning parameters.
22/10/2024 22:36:38   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:38   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:38   periodic repaints.
22/10/2024 22:36:38 GrabServer control via XTEST.
22/10/2024 22:36:38
22/10/2024 22:36:38 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:38   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:38   (induced by either user keystroke or mouse input).
22/10/2024 22:36:38   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:38   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:38   Also see the -help entry for tuning parameters.
22/10/2024 22:36:38   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:38   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:38   periodic repaints.
22/10/2024 22:36:38
22/10/2024 22:36:38 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:38   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:38   Automatically switching to -xkb mode.
22/10/2024 22:36:38   If this makes the key mapping worse you can
22/10/2024 22:36:38   disable it with the "-noxkb" option.
22/10/2024 22:36:38   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:38
22/10/2024 22:36:38 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:38 X display is not capable of DPMS.
22/10/2024 22:36:38 --------------------------------------------------------
22/10/2024 22:36:38
22/10/2024 22:36:38 Default visual ID: 0x21
22/10/2024 22:36:38 Read initial data from X display into framebuffer.
22/10/2024 22:36:38 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:38
22/10/2024 22:36:38 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:38
22/10/2024 22:36:38 ListenOnTCPPort: Address already in use
22/10/2024 22:36:38 listen6: bind: Address already in use
22/10/2024 22:36:38 Not listening on IPv6 interface.
22/10/2024 22:36:38
22/10/2024 22:36:38 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:38 Xinerama: number of sub-screens: 1
22/10/2024 22:36:38 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:38
22/10/2024 22:36:38 fb read rate: 1214 MB/sec
22/10/2024 22:36:38 fast read: reset -defer ms to: 10
22/10/2024 22:36:38 The X server says there are 10 mouse buttons.
22/10/2024 22:36:38 Error: could not obtain listening port.
22/10/2024 22:36:38 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:42 passing arg to libvncserver: -rfbport
22/10/2024 22:36:42 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:43 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 785
22/10/2024 22:36:43 Using X display :1
22/10/2024 22:36:43 rootwin: 0x50d reswin: 0x800001 dpy: 0x842f75b0
22/10/2024 22:36:43
22/10/2024 22:36:43 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:43
22/10/2024 22:36:43 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:43   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:43   errors, etc) it may be disabled:
22/10/2024 22:36:43    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:43    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:43      moved window is released in the new position.
22/10/2024 22:36:43   Also see the -help entry for tuning parameters.
22/10/2024 22:36:43   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:43   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:43   periodic repaints.
22/10/2024 22:36:43 GrabServer control via XTEST.
22/10/2024 22:36:43
22/10/2024 22:36:43 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:43   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:43   (induced by either user keystroke or mouse input).
22/10/2024 22:36:43   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:43   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:43   Also see the -help entry for tuning parameters.
22/10/2024 22:36:43   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:43   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:43   periodic repaints.
22/10/2024 22:36:43
22/10/2024 22:36:43 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:43   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:43   Automatically switching to -xkb mode.
22/10/2024 22:36:43   If this makes the key mapping worse you can
22/10/2024 22:36:43   disable it with the "-noxkb" option.
22/10/2024 22:36:43   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:43
22/10/2024 22:36:43 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:43 X display is not capable of DPMS.
22/10/2024 22:36:43 --------------------------------------------------------
22/10/2024 22:36:43
22/10/2024 22:36:43 Default visual ID: 0x21
22/10/2024 22:36:43 Read initial data from X display into framebuffer.
22/10/2024 22:36:43 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:43
22/10/2024 22:36:43 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:43
22/10/2024 22:36:43 ListenOnTCPPort: Address already in use
22/10/2024 22:36:43 listen6: bind: Address already in use
22/10/2024 22:36:43 Not listening on IPv6 interface.
22/10/2024 22:36:43
22/10/2024 22:36:43 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:43 Xinerama: number of sub-screens: 1
22/10/2024 22:36:43 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:43
22/10/2024 22:36:43 fb read rate: 1210 MB/sec
22/10/2024 22:36:43 fast read: reset -defer ms to: 10
22/10/2024 22:36:43 The X server says there are 10 mouse buttons.
22/10/2024 22:36:43 Error: could not obtain listening port.
22/10/2024 22:36:43 deleted 32 tile_row polling images.
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:47 passing arg to libvncserver: -rfbport
22/10/2024 22:36:47 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:48 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 793
22/10/2024 22:36:48 Using X display :1
22/10/2024 22:36:48 rootwin: 0x50d reswin: 0x800001 dpy: 0x57aae5b0
22/10/2024 22:36:48
22/10/2024 22:36:48 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:48
22/10/2024 22:36:48 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:48   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:48   errors, etc) it may be disabled:
22/10/2024 22:36:48    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:48    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:48      moved window is released in the new position.
22/10/2024 22:36:48   Also see the -help entry for tuning parameters.
22/10/2024 22:36:48   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:48   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:48   periodic repaints.
22/10/2024 22:36:48 GrabServer control via XTEST.
22/10/2024 22:36:48
22/10/2024 22:36:48 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:48   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:48   (induced by either user keystroke or mouse input).
22/10/2024 22:36:48   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:48   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:48   Also see the -help entry for tuning parameters.
22/10/2024 22:36:48   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:48   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:48   periodic repaints.
22/10/2024 22:36:48
22/10/2024 22:36:48 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:48   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:48   Automatically switching to -xkb mode.
22/10/2024 22:36:48   If this makes the key mapping worse you can
22/10/2024 22:36:48   disable it with the "-noxkb" option.
22/10/2024 22:36:48   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:48
22/10/2024 22:36:48 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:48 X display is not capable of DPMS.
22/10/2024 22:36:48 --------------------------------------------------------
22/10/2024 22:36:48
22/10/2024 22:36:48 Default visual ID: 0x21
22/10/2024 22:36:48 Read initial data from X display into framebuffer.
22/10/2024 22:36:48 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:48
22/10/2024 22:36:48 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:48
22/10/2024 22:36:48 Listening for VNC connections on TCP port 5900
22/10/2024 22:36:48 Listening for VNC connections on TCP6 port 5900
22/10/2024 22:36:48 listen6: bind: Address already in use
22/10/2024 22:36:48 Not listening on IPv6 interface.
22/10/2024 22:36:48
22/10/2024 22:36:48 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:48 Xinerama: number of sub-screens: 1
22/10/2024 22:36:48 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:48
22/10/2024 22:36:48 fb read rate: 798 MB/sec
22/10/2024 22:36:48 fast read: reset -defer ms to: 10
22/10/2024 22:36:48 The X server says there are 10 mouse buttons.
22/10/2024 22:36:48 screen setup finished.
22/10/2024 22:36:48
22/10/2024 22:36:48 WARNING: You are running x11vnc WITHOUT a password.  See
22/10/2024 22:36:48 WARNING: the warning message printed above for more info.
22/10/2024 22:36:48

The VNC desktop is:      9ff55f62fcee:0

******************************************************************************
Have you tried the x11vnc '-ncache' VNC client-side pixel caching feature yet?

The scheme stores pixel data offscreen on the VNC viewer side for faster
retrieval.  It should work with any VNC viewer.  Try it by running:

    x11vnc -ncache 10 ...

One can also add -ncache_cr for smooth 'copyrect' window motion.
More info: http://www.karlrunge.com/x11vnc/faq.html#faq-client-caching

starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:50 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 802
22/10/2024 22:36:50 Using X display :1
22/10/2024 22:36:50 rootwin: 0x50d reswin: 0xa00001 dpy: 0x9c54580
22/10/2024 22:36:50
22/10/2024 22:36:50 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:50
22/10/2024 22:36:50 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:50   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:50   errors, etc) it may be disabled:
22/10/2024 22:36:50    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:50    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:50      moved window is released in the new position.
22/10/2024 22:36:50   Also see the -help entry for tuning parameters.
22/10/2024 22:36:50   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:50   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:50   periodic repaints.
22/10/2024 22:36:50 GrabServer control via XTEST.
22/10/2024 22:36:50
22/10/2024 22:36:50 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:50   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:50   (induced by either user keystroke or mouse input).
22/10/2024 22:36:50   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:50   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:50   Also see the -help entry for tuning parameters.
22/10/2024 22:36:50   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:50   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:50   periodic repaints.
22/10/2024 22:36:50
22/10/2024 22:36:50 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:50   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:50   Automatically switching to -xkb mode.
22/10/2024 22:36:50   If this makes the key mapping worse you can
22/10/2024 22:36:50   disable it with the "-noxkb" option.
22/10/2024 22:36:50   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:50
22/10/2024 22:36:50 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:50 X display is not capable of DPMS.
22/10/2024 22:36:50 --------------------------------------------------------
22/10/2024 22:36:50
22/10/2024 22:36:50 Default visual ID: 0x21
22/10/2024 22:36:50 Read initial data from X display into framebuffer.
22/10/2024 22:36:50 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:50
22/10/2024 22:36:50 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:50
22/10/2024 22:36:50 ListenOnTCPPort: Address already in use
22/10/2024 22:36:50 listen6: bind: Address already in use
22/10/2024 22:36:50 Not listening on IPv6 interface.
22/10/2024 22:36:50
22/10/2024 22:36:50 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:50 Xinerama: number of sub-screens: 1
22/10/2024 22:36:50 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:50
22/10/2024 22:36:50 fb read rate: 726 MB/sec
22/10/2024 22:36:50 fast read: reset -defer ms to: 10
22/10/2024 22:36:50 The X server says there are 10 mouse buttons.
22/10/2024 22:36:50 Error: could not obtain listening port.
22/10/2024 22:36:50 deleted 32 tile_row polling images.
starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:54 passing arg to libvncserver: -rfbport
22/10/2024 22:36:54 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:36:55 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 816
22/10/2024 22:36:55 Using X display :1
22/10/2024 22:36:55 rootwin: 0x50d reswin: 0xa00001 dpy: 0x7064a580
22/10/2024 22:36:55
22/10/2024 22:36:55 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:36:55
22/10/2024 22:36:55 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:36:55   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:55   errors, etc) it may be disabled:
22/10/2024 22:36:55    - use '-nowf' to disable wireframing completely.
22/10/2024 22:36:55    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:36:55      moved window is released in the new position.
22/10/2024 22:36:55   Also see the -help entry for tuning parameters.
22/10/2024 22:36:55   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:55   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:55   periodic repaints.
22/10/2024 22:36:55 GrabServer control via XTEST.
22/10/2024 22:36:55
22/10/2024 22:36:55 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:36:55   use RECORD extension to try to detect scrolling windows
22/10/2024 22:36:55   (induced by either user keystroke or mouse input).
22/10/2024 22:36:55   If this yields undesired behavior (poor response, painting
22/10/2024 22:36:55   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:36:55   Also see the -help entry for tuning parameters.
22/10/2024 22:36:55   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:36:55   repaint the screen, also see the -fixscreen option for
22/10/2024 22:36:55   periodic repaints.
22/10/2024 22:36:55
22/10/2024 22:36:55 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:36:55   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:36:55   Automatically switching to -xkb mode.
22/10/2024 22:36:55   If this makes the key mapping worse you can
22/10/2024 22:36:55   disable it with the "-noxkb" option.
22/10/2024 22:36:55   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:36:55
22/10/2024 22:36:55 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:36:55 X display is not capable of DPMS.
22/10/2024 22:36:55 --------------------------------------------------------
22/10/2024 22:36:55
22/10/2024 22:36:55 Default visual ID: 0x21
22/10/2024 22:36:55 Read initial data from X display into framebuffer.
22/10/2024 22:36:55 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:36:55
22/10/2024 22:36:55 X display :1 is 32bpp depth=24 true color
22/10/2024 22:36:55
22/10/2024 22:36:55 ListenOnTCPPort: Address already in use
22/10/2024 22:36:55 listen6: bind: Address already in use
22/10/2024 22:36:55 Not listening on IPv6 interface.
22/10/2024 22:36:55
22/10/2024 22:36:55 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:36:55 Xinerama: number of sub-screens: 1
22/10/2024 22:36:55 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:36:55
22/10/2024 22:36:55 fb read rate: 648 MB/sec
22/10/2024 22:36:55 fast read: reset -defer ms to: 10
22/10/2024 22:36:55 The X server says there are 10 mouse buttons.
22/10/2024 22:36:55 Error: could not obtain listening port.
22/10/2024 22:36:55 deleted 32 tile_row polling images.
starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:36:59 passing arg to libvncserver: -rfbport
22/10/2024 22:36:59 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:37:00 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 861
22/10/2024 22:37:00 Using X display :1
22/10/2024 22:37:00 rootwin: 0x50d reswin: 0xa00001 dpy: 0x401c1580
22/10/2024 22:37:00
22/10/2024 22:37:00 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:37:00
22/10/2024 22:37:00 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:37:00   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:00   errors, etc) it may be disabled:
22/10/2024 22:37:00    - use '-nowf' to disable wireframing completely.
22/10/2024 22:37:00    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:37:00      moved window is released in the new position.
22/10/2024 22:37:00   Also see the -help entry for tuning parameters.
22/10/2024 22:37:00   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:00   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:00   periodic repaints.
22/10/2024 22:37:00 GrabServer control via XTEST.
22/10/2024 22:37:00
22/10/2024 22:37:00 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:37:00   use RECORD extension to try to detect scrolling windows
22/10/2024 22:37:00   (induced by either user keystroke or mouse input).
22/10/2024 22:37:00   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:00   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:37:00   Also see the -help entry for tuning parameters.
22/10/2024 22:37:00   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:00   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:00   periodic repaints.
22/10/2024 22:37:00
22/10/2024 22:37:00 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:37:00   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:37:00   Automatically switching to -xkb mode.
22/10/2024 22:37:00   If this makes the key mapping worse you can
22/10/2024 22:37:00   disable it with the "-noxkb" option.
22/10/2024 22:37:00   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:37:00
22/10/2024 22:37:00 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:37:00 X display is not capable of DPMS.
22/10/2024 22:37:00 --------------------------------------------------------
22/10/2024 22:37:00
22/10/2024 22:37:00 Default visual ID: 0x21
22/10/2024 22:37:00 Read initial data from X display into framebuffer.
22/10/2024 22:37:00 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:37:00
22/10/2024 22:37:00 X display :1 is 32bpp depth=24 true color
22/10/2024 22:37:00
22/10/2024 22:37:00 ListenOnTCPPort: Address already in use
22/10/2024 22:37:00 listen6: bind: Address already in use
22/10/2024 22:37:00 Not listening on IPv6 interface.
22/10/2024 22:37:00
22/10/2024 22:37:00 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:37:00 Xinerama: number of sub-screens: 1
22/10/2024 22:37:00 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:37:00
22/10/2024 22:37:00 fb read rate: 677 MB/sec
22/10/2024 22:37:00 fast read: reset -defer ms to: 10
22/10/2024 22:37:00 The X server says there are 10 mouse buttons.
22/10/2024 22:37:00 Error: could not obtain listening port.
22/10/2024 22:37:00 deleted 32 tile_row polling images.
starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:37:04 passing arg to libvncserver: -rfbport
22/10/2024 22:37:04 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:37:05 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 981
22/10/2024 22:37:05 Using X display :1
22/10/2024 22:37:05 rootwin: 0x50d reswin: 0xc00001 dpy: 0x4b84e580
22/10/2024 22:37:05
22/10/2024 22:37:05 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:37:05
22/10/2024 22:37:05 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:37:05   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:05   errors, etc) it may be disabled:
22/10/2024 22:37:05    - use '-nowf' to disable wireframing completely.
22/10/2024 22:37:05    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:37:05      moved window is released in the new position.
22/10/2024 22:37:05   Also see the -help entry for tuning parameters.
22/10/2024 22:37:05   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:05   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:05   periodic repaints.
22/10/2024 22:37:05 GrabServer control via XTEST.
22/10/2024 22:37:05
22/10/2024 22:37:05 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:37:05   use RECORD extension to try to detect scrolling windows
22/10/2024 22:37:05   (induced by either user keystroke or mouse input).
22/10/2024 22:37:05   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:05   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:37:05   Also see the -help entry for tuning parameters.
22/10/2024 22:37:05   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:05   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:05   periodic repaints.
22/10/2024 22:37:05
22/10/2024 22:37:05 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:37:05   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:37:05   Automatically switching to -xkb mode.
22/10/2024 22:37:05   If this makes the key mapping worse you can
22/10/2024 22:37:05   disable it with the "-noxkb" option.
22/10/2024 22:37:05   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:37:05
22/10/2024 22:37:05 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:37:05 X display is not capable of DPMS.
22/10/2024 22:37:05 --------------------------------------------------------
22/10/2024 22:37:05
22/10/2024 22:37:05 Default visual ID: 0x21
22/10/2024 22:37:05 Read initial data from X display into framebuffer.
22/10/2024 22:37:05 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:37:05
22/10/2024 22:37:05 X display :1 is 32bpp depth=24 true color
22/10/2024 22:37:05
22/10/2024 22:37:05 ListenOnTCPPort: Address already in use
22/10/2024 22:37:05 listen6: bind: Address already in use
22/10/2024 22:37:05 Not listening on IPv6 interface.
22/10/2024 22:37:05
22/10/2024 22:37:05 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:37:05 Xinerama: number of sub-screens: 1
22/10/2024 22:37:05 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:37:05
22/10/2024 22:37:05 fb read rate: 2323 MB/sec
22/10/2024 22:37:05 fast read: reset -defer ms to: 10
22/10/2024 22:37:05 The X server says there are 10 mouse buttons.
22/10/2024 22:37:05 Error: could not obtain listening port.
22/10/2024 22:37:05 deleted 32 tile_row polling images.
starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:37:09 passing arg to libvncserver: -rfbport
22/10/2024 22:37:09 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:37:10 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 1006
22/10/2024 22:37:10 Using X display :1
22/10/2024 22:37:10 rootwin: 0x50d reswin: 0xc00001 dpy: 0x42e85580
22/10/2024 22:37:10
22/10/2024 22:37:10 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:37:10
22/10/2024 22:37:10 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:37:10   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:10   errors, etc) it may be disabled:
22/10/2024 22:37:10    - use '-nowf' to disable wireframing completely.
22/10/2024 22:37:10    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:37:10      moved window is released in the new position.
22/10/2024 22:37:10   Also see the -help entry for tuning parameters.
22/10/2024 22:37:10   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:10   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:10   periodic repaints.
22/10/2024 22:37:10 GrabServer control via XTEST.
22/10/2024 22:37:10
22/10/2024 22:37:10 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:37:10   use RECORD extension to try to detect scrolling windows
22/10/2024 22:37:10   (induced by either user keystroke or mouse input).
22/10/2024 22:37:10   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:10   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:37:10   Also see the -help entry for tuning parameters.
22/10/2024 22:37:10   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:10   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:10   periodic repaints.
22/10/2024 22:37:10
22/10/2024 22:37:10 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:37:10   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:37:10   Automatically switching to -xkb mode.
22/10/2024 22:37:10   If this makes the key mapping worse you can
22/10/2024 22:37:10   disable it with the "-noxkb" option.
22/10/2024 22:37:10   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:37:10
22/10/2024 22:37:10 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:37:10 X display is not capable of DPMS.
22/10/2024 22:37:10 --------------------------------------------------------
22/10/2024 22:37:10
22/10/2024 22:37:10 Default visual ID: 0x21
22/10/2024 22:37:10 Read initial data from X display into framebuffer.
22/10/2024 22:37:10 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:37:10
22/10/2024 22:37:10 X display :1 is 32bpp depth=24 true color
22/10/2024 22:37:10
22/10/2024 22:37:10 ListenOnTCPPort: Address already in use
22/10/2024 22:37:10 listen6: bind: Address already in use
22/10/2024 22:37:10 Not listening on IPv6 interface.
22/10/2024 22:37:10
22/10/2024 22:37:10 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:37:10 Xinerama: number of sub-screens: 1
22/10/2024 22:37:10 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:37:10
22/10/2024 22:37:10 fb read rate: 2412 MB/sec
22/10/2024 22:37:10 fast read: reset -defer ms to: 10
22/10/2024 22:37:10 The X server says there are 10 mouse buttons.
22/10/2024 22:37:10 Error: could not obtain listening port.
22/10/2024 22:37:10 deleted 32 tile_row polling images.
starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:37:14 passing arg to libvncserver: -rfbport
22/10/2024 22:37:14 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:37:15 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 1014
22/10/2024 22:37:15 Using X display :1
22/10/2024 22:37:15 rootwin: 0x50d reswin: 0xc00001 dpy: 0xaa6de580
22/10/2024 22:37:15
22/10/2024 22:37:15 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:37:15
22/10/2024 22:37:15 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:37:15   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:15   errors, etc) it may be disabled:
22/10/2024 22:37:15    - use '-nowf' to disable wireframing completely.
22/10/2024 22:37:15    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:37:15      moved window is released in the new position.
22/10/2024 22:37:15   Also see the -help entry for tuning parameters.
22/10/2024 22:37:15   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:15   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:15   periodic repaints.
22/10/2024 22:37:15 GrabServer control via XTEST.
22/10/2024 22:37:15
22/10/2024 22:37:15 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:37:15   use RECORD extension to try to detect scrolling windows
22/10/2024 22:37:15   (induced by either user keystroke or mouse input).
22/10/2024 22:37:15   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:15   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:37:15   Also see the -help entry for tuning parameters.
22/10/2024 22:37:15   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:15   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:15   periodic repaints.
22/10/2024 22:37:15
22/10/2024 22:37:15 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:37:15   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:37:15   Automatically switching to -xkb mode.
22/10/2024 22:37:15   If this makes the key mapping worse you can
22/10/2024 22:37:15   disable it with the "-noxkb" option.
22/10/2024 22:37:15   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:37:15
22/10/2024 22:37:15 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:37:15 X display is not capable of DPMS.
22/10/2024 22:37:15 --------------------------------------------------------
22/10/2024 22:37:15
22/10/2024 22:37:15 Default visual ID: 0x21
22/10/2024 22:37:15 Read initial data from X display into framebuffer.
22/10/2024 22:37:15 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:37:15
22/10/2024 22:37:15 X display :1 is 32bpp depth=24 true color
22/10/2024 22:37:15
22/10/2024 22:37:15 ListenOnTCPPort: Address already in use
22/10/2024 22:37:15 listen6: bind: Address already in use
22/10/2024 22:37:15 Not listening on IPv6 interface.
22/10/2024 22:37:15
22/10/2024 22:37:15 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:37:15 Xinerama: number of sub-screens: 1
22/10/2024 22:37:15 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:37:15
22/10/2024 22:37:15 fb read rate: 2367 MB/sec
22/10/2024 22:37:15 fast read: reset -defer ms to: 10
22/10/2024 22:37:15 The X server says there are 10 mouse buttons.
22/10/2024 22:37:15 Error: could not obtain listening port.
22/10/2024 22:37:15 deleted 32 tile_row polling images.
starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:37:19 passing arg to libvncserver: -rfbport
22/10/2024 22:37:19 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:37:20 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 1023
22/10/2024 22:37:20 Using X display :1
22/10/2024 22:37:20 rootwin: 0x50d reswin: 0xc00001 dpy: 0xc9b0e580
22/10/2024 22:37:20
22/10/2024 22:37:20 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:37:20
22/10/2024 22:37:20 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:37:20   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:20   errors, etc) it may be disabled:
22/10/2024 22:37:20    - use '-nowf' to disable wireframing completely.
22/10/2024 22:37:20    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:37:20      moved window is released in the new position.
22/10/2024 22:37:20   Also see the -help entry for tuning parameters.
22/10/2024 22:37:20   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:20   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:20   periodic repaints.
22/10/2024 22:37:20 GrabServer control via XTEST.
22/10/2024 22:37:20
22/10/2024 22:37:20 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:37:20   use RECORD extension to try to detect scrolling windows
22/10/2024 22:37:20   (induced by either user keystroke or mouse input).
22/10/2024 22:37:20   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:20   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:37:20   Also see the -help entry for tuning parameters.
22/10/2024 22:37:20   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:20   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:20   periodic repaints.
22/10/2024 22:37:20
22/10/2024 22:37:20 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:37:20   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:37:20   Automatically switching to -xkb mode.
22/10/2024 22:37:20   If this makes the key mapping worse you can
22/10/2024 22:37:20   disable it with the "-noxkb" option.
22/10/2024 22:37:20   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:37:20
22/10/2024 22:37:20 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:37:20 X display is not capable of DPMS.
22/10/2024 22:37:20 --------------------------------------------------------
22/10/2024 22:37:20
22/10/2024 22:37:20 Default visual ID: 0x21
22/10/2024 22:37:20 Read initial data from X display into framebuffer.
22/10/2024 22:37:20 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:37:20
22/10/2024 22:37:20 X display :1 is 32bpp depth=24 true color
22/10/2024 22:37:20
22/10/2024 22:37:20 ListenOnTCPPort: Address already in use
22/10/2024 22:37:20 listen6: bind: Address already in use
22/10/2024 22:37:20 Not listening on IPv6 interface.
22/10/2024 22:37:20
22/10/2024 22:37:20 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:37:20 Xinerama: number of sub-screens: 1
22/10/2024 22:37:20 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:37:20
22/10/2024 22:37:20 fb read rate: 2215 MB/sec
22/10/2024 22:37:20 fast read: reset -defer ms to: 10
22/10/2024 22:37:20 The X server says there are 10 mouse buttons.
22/10/2024 22:37:20 Error: could not obtain listening port.
22/10/2024 22:37:20 deleted 32 tile_row polling images.
starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:37:24 passing arg to libvncserver: -rfbport
22/10/2024 22:37:24 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:37:25 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 1316
22/10/2024 22:37:25 Using X display :1
22/10/2024 22:37:25 rootwin: 0x50d reswin: 0xc00001 dpy: 0xdf43c580
22/10/2024 22:37:25
22/10/2024 22:37:25 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:37:25
22/10/2024 22:37:25 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:37:25   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:25   errors, etc) it may be disabled:
22/10/2024 22:37:25    - use '-nowf' to disable wireframing completely.
22/10/2024 22:37:25    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:37:25      moved window is released in the new position.
22/10/2024 22:37:25   Also see the -help entry for tuning parameters.
22/10/2024 22:37:25   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:25   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:25   periodic repaints.
22/10/2024 22:37:25 GrabServer control via XTEST.
22/10/2024 22:37:25
22/10/2024 22:37:25 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:37:25   use RECORD extension to try to detect scrolling windows
22/10/2024 22:37:25   (induced by either user keystroke or mouse input).
22/10/2024 22:37:25   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:25   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:37:25   Also see the -help entry for tuning parameters.
22/10/2024 22:37:25   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:25   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:25   periodic repaints.
22/10/2024 22:37:25
22/10/2024 22:37:25 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:37:25   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:37:25   Automatically switching to -xkb mode.
22/10/2024 22:37:25   If this makes the key mapping worse you can
22/10/2024 22:37:25   disable it with the "-noxkb" option.
22/10/2024 22:37:25   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:37:25
22/10/2024 22:37:25 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:37:25 X display is not capable of DPMS.
22/10/2024 22:37:25 --------------------------------------------------------
22/10/2024 22:37:25
22/10/2024 22:37:25 Default visual ID: 0x21
22/10/2024 22:37:25 Read initial data from X display into framebuffer.
22/10/2024 22:37:25 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:37:25
22/10/2024 22:37:25 X display :1 is 32bpp depth=24 true color
22/10/2024 22:37:25
22/10/2024 22:37:25 ListenOnTCPPort: Address already in use
22/10/2024 22:37:25 listen6: bind: Address already in use
22/10/2024 22:37:25 Not listening on IPv6 interface.
22/10/2024 22:37:25
22/10/2024 22:37:25 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:37:25 Xinerama: number of sub-screens: 1
22/10/2024 22:37:25 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:37:25
22/10/2024 22:37:25 fb read rate: 2368 MB/sec
22/10/2024 22:37:25 fast read: reset -defer ms to: 10
22/10/2024 22:37:25 The X server says there are 10 mouse buttons.
22/10/2024 22:37:25 Error: could not obtain listening port.
22/10/2024 22:37:25 deleted 32 tile_row polling images.
starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:37:29 passing arg to libvncserver: -rfbport
22/10/2024 22:37:29 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:37:30 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 1335
22/10/2024 22:37:30 Using X display :1
22/10/2024 22:37:30 rootwin: 0x50d reswin: 0xc00001 dpy: 0x470c3580
22/10/2024 22:37:30
22/10/2024 22:37:30 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:37:30
22/10/2024 22:37:30 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:37:30   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:30   errors, etc) it may be disabled:
22/10/2024 22:37:30    - use '-nowf' to disable wireframing completely.
22/10/2024 22:37:30    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:37:30      moved window is released in the new position.
22/10/2024 22:37:30   Also see the -help entry for tuning parameters.
22/10/2024 22:37:30   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:30   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:30   periodic repaints.
22/10/2024 22:37:30 GrabServer control via XTEST.
22/10/2024 22:37:30
22/10/2024 22:37:30 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:37:30   use RECORD extension to try to detect scrolling windows
22/10/2024 22:37:30   (induced by either user keystroke or mouse input).
22/10/2024 22:37:30   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:30   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:37:30   Also see the -help entry for tuning parameters.
22/10/2024 22:37:30   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:30   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:30   periodic repaints.
22/10/2024 22:37:30
22/10/2024 22:37:30 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:37:30   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:37:30   Automatically switching to -xkb mode.
22/10/2024 22:37:30   If this makes the key mapping worse you can
22/10/2024 22:37:30   disable it with the "-noxkb" option.
22/10/2024 22:37:30   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:37:30
22/10/2024 22:37:30 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:37:30 X display is not capable of DPMS.
22/10/2024 22:37:30 --------------------------------------------------------
22/10/2024 22:37:30
22/10/2024 22:37:30 Default visual ID: 0x21
22/10/2024 22:37:30 Read initial data from X display into framebuffer.
22/10/2024 22:37:30 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:37:30
22/10/2024 22:37:30 X display :1 is 32bpp depth=24 true color
22/10/2024 22:37:30
22/10/2024 22:37:30 ListenOnTCPPort: Address already in use
22/10/2024 22:37:30 listen6: bind: Address already in use
22/10/2024 22:37:30 Not listening on IPv6 interface.
22/10/2024 22:37:30
22/10/2024 22:37:30 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:37:30 Xinerama: number of sub-screens: 1
22/10/2024 22:37:30 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:37:30
22/10/2024 22:37:30 fb read rate: 1652 MB/sec
22/10/2024 22:37:30 fast read: reset -defer ms to: 10
22/10/2024 22:37:30 The X server says there are 10 mouse buttons.
22/10/2024 22:37:30 Error: could not obtain listening port.
22/10/2024 22:37:30 deleted 32 tile_row polling images.
starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:37:34 passing arg to libvncserver: -rfbport
22/10/2024 22:37:34 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:37:35 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 1351
22/10/2024 22:37:35 Using X display :1
22/10/2024 22:37:35 rootwin: 0x50d reswin: 0xc00001 dpy: 0xa2962580
22/10/2024 22:37:35
22/10/2024 22:37:35 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:37:35
22/10/2024 22:37:35 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:37:35   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:35   errors, etc) it may be disabled:
22/10/2024 22:37:35    - use '-nowf' to disable wireframing completely.
22/10/2024 22:37:35    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:37:35      moved window is released in the new position.
22/10/2024 22:37:35   Also see the -help entry for tuning parameters.
22/10/2024 22:37:35   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:35   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:35   periodic repaints.
22/10/2024 22:37:35 GrabServer control via XTEST.
22/10/2024 22:37:35
22/10/2024 22:37:35 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:37:35   use RECORD extension to try to detect scrolling windows
22/10/2024 22:37:35   (induced by either user keystroke or mouse input).
22/10/2024 22:37:35   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:35   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:37:35   Also see the -help entry for tuning parameters.
22/10/2024 22:37:35   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:35   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:35   periodic repaints.
22/10/2024 22:37:35
22/10/2024 22:37:35 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:37:35   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:37:35   Automatically switching to -xkb mode.
22/10/2024 22:37:35   If this makes the key mapping worse you can
22/10/2024 22:37:35   disable it with the "-noxkb" option.
22/10/2024 22:37:35   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:37:35
22/10/2024 22:37:35 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:37:35 X display is not capable of DPMS.
22/10/2024 22:37:35 --------------------------------------------------------
22/10/2024 22:37:35
22/10/2024 22:37:35 Default visual ID: 0x21
22/10/2024 22:37:35 Read initial data from X display into framebuffer.
22/10/2024 22:37:35 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:37:35
22/10/2024 22:37:35 X display :1 is 32bpp depth=24 true color
22/10/2024 22:37:35
22/10/2024 22:37:35 ListenOnTCPPort: Address already in use
22/10/2024 22:37:35 listen6: bind: Address already in use
22/10/2024 22:37:35 Not listening on IPv6 interface.
22/10/2024 22:37:35
22/10/2024 22:37:35 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:37:35 Xinerama: number of sub-screens: 1
22/10/2024 22:37:35 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:37:35
22/10/2024 22:37:35 fb read rate: 1731 MB/sec
22/10/2024 22:37:35 fast read: reset -defer ms to: 10
22/10/2024 22:37:35 The X server says there are 10 mouse buttons.
22/10/2024 22:37:35 Error: could not obtain listening port.
22/10/2024 22:37:35 deleted 32 tile_row polling images.
starting vnc
x11vnc process crashed, restarting...
x11vnc stderr output:
22/10/2024 22:37:39 passing arg to libvncserver: -rfbport
22/10/2024 22:37:39 passing arg to libvncserver: 5900
###############################################################
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  **  WARNING  **  WARNING  **  WARNING  **  WARNING  **   @#
#@                                                           @#
#@        YOU ARE RUNNING X11VNC WITHOUT A PASSWORD!!        @#
#@                                                           @#
#@  This means anyone with network access to this computer   @#
#@  may be able to view and control your desktop.            @#
#@                                                           @#
#@ >>> If you did not mean to do this Press CTRL-C now!! <<< @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
#@                                                           @#
#@  You can create an x11vnc password file by running:       @#
#@                                                           @#
#@       x11vnc -storepasswd password /path/to/passfile      @#
#@  or   x11vnc -storepasswd /path/to/passfile               @#
#@  or   x11vnc -storepasswd                                 @#
#@                                                           @#
#@  (the last one will use ~/.vnc/passwd)                    @#
#@                                                           @#
#@  and then starting x11vnc via:                            @#
#@                                                           @#
#@      x11vnc -rfbauth /path/to/passfile                    @#
#@                                                           @#
#@  an existing ~/.vnc/passwd file from another VNC          @#
#@  application will work fine too.                          @#
#@                                                           @#
#@  You can also use the -passwdfile or -passwd options.     @#
#@  (note -passwd is unsafe if local users are not trusted)  @#
#@                                                           @#
#@  Make sure any -rfbauth and -passwdfile password files    @#
#@  cannot be read by untrusted users.                       @#
#@                                                           @#
#@  Use x11vnc -usepw to automatically use your              @#
#@  ~/.vnc/passwd or ~/.vnc/passwdfile password files.       @#
#@  (and prompt you to create ~/.vnc/passwd if neither       @#
#@  file exists.)  Under -usepw, x11vnc will exit if it      @#
#@  cannot find a password to use.                           @#
#@                                                           @#
#@                                                           @#
#@  Even with a password, the subsequent VNC traffic is      @#
#@  sent in the clear.  Consider tunnelling via ssh(1):      @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/#tunnelling            @#
#@                                                           @#
#@  Or using the x11vnc SSL options: -ssl and -stunnel       @#
#@                                                           @#
#@  Please Read the documentation for more info about        @#
#@  passwords, security, and encryption.                     @#
#@                                                           @#
#@    http://www.karlrunge.com/x11vnc/faq.html#faq-passwd    @#
#@                                                           @#
#@  To disable this warning use the -nopw option, or put     @#
#@  'nopw' on a line in your ~/.x11vncrc file.               @#
#@                                                           @#
#@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@@#
###############################################################
22/10/2024 22:37:40 x11vnc version: 0.9.16 lastmod: 2019-01-05  pid: 1501
22/10/2024 22:37:40 Using X display :1
22/10/2024 22:37:40 rootwin: 0x50d reswin: 0xc00001 dpy: 0x19bfe580
22/10/2024 22:37:40
22/10/2024 22:37:40 ------------------ USEFUL INFORMATION ------------------
22/10/2024 22:37:40
22/10/2024 22:37:40 Wireframing: -wireframe mode is in effect for window moves.
22/10/2024 22:37:40   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:40   errors, etc) it may be disabled:
22/10/2024 22:37:40    - use '-nowf' to disable wireframing completely.
22/10/2024 22:37:40    - use '-nowcr' to disable the Copy Rectangle after the
22/10/2024 22:37:40      moved window is released in the new position.
22/10/2024 22:37:40   Also see the -help entry for tuning parameters.
22/10/2024 22:37:40   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:40   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:40   periodic repaints.
22/10/2024 22:37:40 GrabServer control via XTEST.
22/10/2024 22:37:40
22/10/2024 22:37:40 Scroll Detection: -scrollcopyrect mode is in effect to
22/10/2024 22:37:40   use RECORD extension to try to detect scrolling windows
22/10/2024 22:37:40   (induced by either user keystroke or mouse input).
22/10/2024 22:37:40   If this yields undesired behavior (poor response, painting
22/10/2024 22:37:40   errors, etc) it may be disabled via: '-noscr'
22/10/2024 22:37:40   Also see the -help entry for tuning parameters.
22/10/2024 22:37:40   You can press 3 Alt_L's (Left "Alt" key) in a row to
22/10/2024 22:37:40   repaint the screen, also see the -fixscreen option for
22/10/2024 22:37:40   periodic repaints.
22/10/2024 22:37:40
22/10/2024 22:37:40 XKEYBOARD: number of keysyms per keycode 7 is greater
22/10/2024 22:37:40   than 4 and 51 keysyms are mapped above 4.
22/10/2024 22:37:40   Automatically switching to -xkb mode.
22/10/2024 22:37:40   If this makes the key mapping worse you can
22/10/2024 22:37:40   disable it with the "-noxkb" option.
22/10/2024 22:37:40   Also, remember "-remap DEAD" for accenting characters.
22/10/2024 22:37:40
22/10/2024 22:37:40 X FBPM extension not supported.
Xlib:  extension "DPMS" missing on display ":1".
22/10/2024 22:37:40 X display is not capable of DPMS.
22/10/2024 22:37:40 --------------------------------------------------------
22/10/2024 22:37:40
22/10/2024 22:37:40 Default visual ID: 0x21
22/10/2024 22:37:40 Read initial data from X display into framebuffer.
22/10/2024 22:37:40 initialize_screen: fb_depth/fb_bpp/fb_Bpl 24/32/4096
22/10/2024 22:37:40
22/10/2024 22:37:40 X display :1 is 32bpp depth=24 true color
22/10/2024 22:37:40
22/10/2024 22:37:40 ListenOnTCPPort: Address already in use
22/10/2024 22:37:40 listen6: bind: Address already in use
22/10/2024 22:37:40 Not listening on IPv6 interface.
22/10/2024 22:37:40
22/10/2024 22:37:40 Xinerama is present and active (e.g. multi-head).
22/10/2024 22:37:40 Xinerama: number of sub-screens: 1
22/10/2024 22:37:40 Xinerama: no blackouts needed (only one sub-screen)
22/10/2024 22:37:40
22/10/2024 22:37:40 fb read rate: 1196 MB/sec
22/10/2024 22:37:40 fast read: reset -defer ms to: 10
22/10/2024 22:37:40 The X server says there are 10 mouse buttons.
22/10/2024 22:37:40 Error: could not obtain listening port.
22/10/2024 22:37:40 deleted 32 tile_row polling images.
starting vnc
^Cx11vnc process crashed, restarting...


