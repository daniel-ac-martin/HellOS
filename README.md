# HellOS

Bare bones "hello world" i386 kernel written in [Zig](https://ziglang.org/).

## Building

```
zig build --release=small
```

## Testing with qemu

```
qemu-system-i386 -kernel zig-out/bin/HellOs
```
