# drirc_acceleration_idea + dual speed intel https://github.com/Griggorii/linux_xorg_glamor_perfomance_drawing_dual
drirc , linux , acceleration , dri , universal hack * testing

$ cd ~/

$ git clone https://github.com/Griggorii/drirc_acceleration_idea

$ cd drirc_acceleration_idea

1) Variant run terminal locate drirc command:

$ sudo cp drirc /etc

2) Variant run terminal locate drirc command:

$ mv drirc .drirc && mv .drirc ~/

Exit end reboot session run terminal command:

$ glxgears test variant

$ vblank_mode=0 glxgears

$ vblank_mode=1 glxgears

$ vblank_mode=1 stub_occlusion_query=1 fragment_shader=1 glxgears

$ vblank_mode=0 stub_occlusion_query=0 fragment_shader=0 glxgears

$ vblank_mode=0 stub_occlusion_query=1 fragment_shader=0 glxgears

$ vblank_mode=0 stub_occlusion_query=1 fragment_shader=1 glxgears

$ vblank_mode=0 stub_occlusion_query=0 fragment_shader=1 glxgears

$ vblank_mode=1 stub_occlusion_query=0 fragment_shader=1 glxgears

$ vblank_mode=1 stub_occlusion_query=0 fragment_shader=0 glxgears

$ vblank_mode=1 stub_occlusion_query=1 fragment_shader=0 glxgears

____________________________________________________________________________________

Dri prime nvidia variant test glxgears

$ DRI_PRIME=1 glxgears

$ DRI_PRIME=0 glxgears

$ DRI_PRIME=0 vblank_mode=0 stub_occlusion_query=1 fragment_shader=1 glxgears

$ DRI_PRIME=1 vblank_mode=1 stub_occlusion_query=1 fragment_shader=1 glxgears

$ DRI_PRIME=0 vblank_mode=1 stub_occlusion_query=0 fragment_shader=0 glxgears

$ DRI_PRIME=0 vblank_mode=1 stub_occlusion_query=0 fragment_shader=1 glxgears


$ echo $vblank_mode 1

$ echo $vblank_mode 0

$ echo -e $vblank_mode 1

$ echo -e $vblank_mode 0

$ echo -e $vblank_mode 1 glxgears





