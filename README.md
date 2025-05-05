# Containerized Pipewire and Pulseaudio utils

These are the pipewire and pulseaudio utils, snapped and ready to be
used with the snapped pipewire server.

Don't forget to connect the `pipewire` plug to the corresponding slot,
and to set, if needed, the PIPEWIRE_RUNTIME_DIR and the PULSE_SERVER
environment variables. For example:

    export PIPEWIRE_RUNTIME_DIR=/run/user/1000/snap.pipewire
    export PULSE_SERVER=unix:/run/user/1000/snap.pipewire/pulse/native
