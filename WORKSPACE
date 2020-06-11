workspace(name = "base_sphinx")

# FIXME, should I just get this from flite? Or sperate it into its own library? Or come up with a better way of loading deps?
load('@base_sphinx//toolchain:load_sound_linux_dep.bzl', 'loadLinux_X86_64bit')
load('@base_sphinx//toolchain:load_sound_linux_dep.bzl', 'alsa_X86_64bit')

loadLinux_X86_64bit()
alsa_X86_64bit()