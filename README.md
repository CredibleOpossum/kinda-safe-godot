# kinda-safe-godot
kinda safe godot: sandboxing, file isolation

While I can not find any way to escape this sandbox, it's very possible it can be done.

This enviroment exposes many directories using symlinks to your actual computer, this leaks some information (installed programs, resource usage, etc).

A bash enviroment can not be started inside the sandbox as it uses syscalls not permitted
