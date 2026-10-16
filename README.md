# Cutroom

A native homebrew application for a jailbroken PlayStation 5: a lightweight photo editor driven by the gamepad, with live preview and network transfer of finished results. Image operations run on the CPU over an RGBA buffer and only the finished texture is uploaded to the console, so the editor does not depend on the system image codecs, whose behaviour on the console is unconfirmed. The project is meant to grow into video as well, provided that video export turns out to be feasible in practice.
