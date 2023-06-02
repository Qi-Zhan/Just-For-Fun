# SysR

A learning and just for full system emulator project inspired by [nemu](https://github.com/NJU-ProjectN/nemu).
We aim to implement almost everything in a computer system, including CPU, Memory, IO, OS, etc.

## Architecture
```
+-----------------+   +-----------------+   +-----------------+
|                 |   |                 |   |                 |
|   Application   |   |   Application   |   |   Application   |
|                 |   |                 |   |                 |
+-----------------+   +-----------------+   +-----------------+
|                 |   |                 |   |                 |
|      ABI        |   |      ABI        |   |     ABI         |
|    syscall      |   |     syscall     |   |    syscall      |
+-------------------------------------------------------------+   
|                                                             |
|                      Operating System                       |
|                           ROS                               |
+-------------------------------------------------------------+
|                                                             |
|                                                             |
|                           RAM                               |
+-------------------------------------------------------------+
|                                                             |
|                    (CPU, IO, Memory)                        |
|                          REMU                               |
+-------------------------------------------------------------+
```

TBD



## Abstract Machine Example

A simple typing game: 
![sdl](https://github.com/Qi-Zhan/SysR/assets/89050446/df7e74dc-1460-4214-af57-317aace421dd)



## Usage
```
$ cargo run --release -- -h TBD
```
