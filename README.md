
# embedded-library-used

## package manager

- [clib](https://github.com/clibs/clib) : Package manager for the C programming language.
- [C_std](https://github.com/KaisenAmin/c_std) : Implementation of C++ standard libraries in C
- [conan](https://github.com/conan-io/conan) : Conan - The open-source C and C++ package manager
- [stb](https://github.com/nothings/stb) : stb single-file public domain libraries for C/C++


## libc

- https://github.com/embeddedartistry/libc : libc targeted for embedded systems usage. Reduced set of functionality (due to embedded nature). Chosen for portability and quick bringup.
- https://github.com/DevSolar/pdclib : The Public Domain C Library
- https://github.com/picolibc/picolibc : picolibc - a C library designed for embedded 32- and 64- bit systems.





## sdk

- [Memfault Firmware SDK](https://github.com/memfault/memfault-firmware-sdk) : Memfault Firmware SDK for embedded systems.
- [Golioth Firmware SDK](https://github.com/golioth/golioth-firmware-sdk)
- [Swedish Embedded Platform SDK](https://github.com/swedishembedded/sdk)
- [C language utility library](https://github.com/MaJerle/lwutil) : Versatile and easy to use C language utility library with functions and macros commonly used in various applications

## rtos
- [freeRTOS](https://www.freertos.org/) : 简单够用的 RTOS
- [Zephyr OS](https://github.com/zephyrproject-rtos/zephyr) : 里面什么都有
- [MiROS](https://github.com/QuantumLeaps/MiROS) : 学习用的
- [YiYiYa](https://github.com/evilbinary/YiYiYa) : YiYiYa 一个os



## event framework
- [lwevt](https://github.com/MaJerle/lwevt) : 适用于【多生产者-单消费者】模型，比如多传感器数据的读取后统一管理
- [NevermindZZT/cpost](https://github.com/NevermindZZT/cpost) : c语言程序上下文切换和解耦的工具
  - [C语言模块化编程的完美解耦](https://nevermindzzt.github.io/2020/12/20/C%E8%AF%AD%E8%A8%80%E6%A8%A1%E5%9D%97%E5%8C%96%E7%BC%96%E7%A8%8B%E7%9A%84%E5%AE%8C%E7%BE%8E%E8%A7%A3%E8%80%A6/)
- [andsmedeiros/uevloop](https://github.com/andsmedeiros/uevloop) : A fast and lightweight event loop aimed at embedded platforms in C99.
- [eerimoq/async](https://github.com/eerimoq/async) : Asynchronous framework in C for systems where low memory usage is important.

## vm

- [MicroPython](https://github.com/micropython/micropython) : a lean and efficient Python implementation for microcontrollers and constrained systems
- [PikaPython](https://github.com/pikasTech/PikaPython) : An ultra-lightweight Python interpreter that runs with only 4KB of RAM, zero dependencies. It is ready to use out of the box without any configuration required and easy to extend with C. Similar project: MicroPython, JerryScript.
- [Rust Embedded](https://github.com/rust-embedded) : Enabling usage of Rust on Embedded Platforms (Embedded Linux / RTOS / Bare Metal)



## coroutine
- [protothread](http://dunkels.com/adam/pt/) : 线程中的非阻塞轮询框架

## memory manager
- [lwmem](https://github.com/MaJerle/lwmem) : 可控可调，挺好/realloc 有问题
- [libmemory](https://github.com/embeddedartistry/libmemory) : Embedded systems memory management library. Implementations for malloc(), free(), and other useful memory management functions
- [umm_malloc](https://github.com/rhempel/umm_malloc) : Memory Manager For Small(ish) Microprocessors
- [Doug Lea's malloc](https://github.com/sailfish009/malloc) : [g.oswego.edu/](https://gee.cs.oswego.edu/dl/html/malloc.html)
- [tbman](https://github.com/johsteffens/tbman) : Memory Manager - Fast, Scalable and Easy to use
- [O(1) heap](https://github.com/pavel-kirienko/o1heap) : Constant-complexity deterministic memory allocator (heap) for hard real-time high-integrity embedded systems. There is very little activity because the project is finished and does not require further changes.





## buffer
- [lwrb](https://github.com/MaJerle/lwrb) : 循环buffer，适用于传感器数据的读取和发送（特别是DMA）
- [Growable Memory Buffers for C99](https://github.com/skeeto/growable-buf)

## queue
- [wl_queue](https://github.com/Aladdin-Wang/wl_queue) : 一个C语言编写的支持任意类型的环形队列.

## frame packet
- [lwpkt](https://github.com/MaJerle/lwpkt) : 可用于打包传感器数据
- [STCmdP Protocol manager](https://www.st.com/en/embedded-software/x-cube-opus.html)

## printf
- [mpaland/printf](https://github.com/mpaland/printf) : Tiny, fast, non-dependent and fully loaded printf implementation for embedded systems. Extensive test suite passing.
- [eyalroz/printf](https://github.com/eyalroz/printf) : forked [mpaland/printf] Tiny, fast(ish), self-contained and fully loaded printf, sprinf etc. implementation, mainly for embedded systems
  - [Standalone printf/sprintf formatted printing function library](https://modm.io/reference/module/modm-printf/)
- [charlesnicholson/nanoprintf](https://github.com/charlesnicholson/nanoprintf) : The smallest public printf implementation for its feature set.
- [cjlano/tinyprintf](https://github.com/cjlano/tinyprintf) : A tiny printf and sprintf library for small embedded systems
  - [A tiny printf for embedded applications](http://www.sparetimelabs.com/tinyprintf/tinyprintf.php)
- [MaJerle/lwprintf](https://github.com/MaJerle/lwprintf) : Lightweight printf library optimized for embedded systems
- blog
  - [printf() and friends… yes, really :-)](https://eyalroz.github.io/software/printf/)
  - [An Embedded-friendly printf Implementation](https://embeddedartistry.com/blog/2019/11/06/an-embedded-friendly-printf-implementation/)

## log
- [rokath/trice](https://github.com/rokath/trice) : super fast and tiny embedded device C printf-like trace code (works also inside interrupts) and real-time PC logging (trace ID visualization)
  - Homepage : https://rokath.github.io/trice/
  - [Tracing & Logging with the `TRICE` Library (Interrupts too!)](https://interrupt.memfault.com/blog/trice)
  - [TriceUserGuide.md](https://github.com/rokath/trice/blob/master/docs/TriceUserGuide.md)
  - [TriceSpeed.md](https://github.com/rokath/trice/blob/master/docs/TriceSpeed.md)
  - [Trice Similarities and differences to printf usage](https://github.com/rokath/trice/blob/master/docs/TriceVsPrintfSimilaritiesAndDifferences.md#printf-like-functions)
- [μP7 (micro P7) ](https://baical.net/up7.html) : μP7 (micro P7) is lightweight C library for sending trace/logs & telemetry data from your Micro-controller’s firmware to host/HW FIFO/cycle buffer/network/etc. for further analysis. It is designed to be integrated on almost every microcontroller, even with very limited resources.
- [Zephyr Logging](https://docs.zephyrproject.org/3.1.0/services/logging/index.html)
- [rxi/log.c](https://github.com/rxi/log.c) : A simple logging library implemented in C99
- [rdpoor/ulog](https://github.com/rdpoor/ulog) : lightweight logging for embedded microcontrollers
- [martinribelotta/elog](https://github.com/martinribelotta/elog) : Embedded logger with minimal footprint and memory usage
- [EasyLogger](https://github.com/armink/EasyLogger)
- blog
  - [printf/log Debugging](https://emp.jamesmunns.com/debug/logging.html) : Embedded: The Missing Parts
  - [BEYOND PRINTF(): BETTER LOGGING PRACTICES FOR FASTER DEBUGGING](https://hackaday.com/2020/07/21/beyond-printf-better-logging-practices-for-faster-debugging/)
  - [Embedded Logging Framework for Spacecrafts](https://ui.adsabs.harvard.edu/abs/2013ESASP.720E..52D/abstract)
  - [McuLog: Logging Framework for small Embedded Microcontroller Systems](https://mcuoneclipse.com/2020/06/01/mculog-logging-framework-for-small-embedded-microcontroller-systems/)
  - [Logging On An Embedded System](https://blog.mbedded.ninja/programming/logging-on-an-embedded-system/)


## flash
- [SFUD](https://github.com/armink/SFUD)
- [Flash Circular Buffer (FCB)](https://docs.zephyrproject.org/3.2.0/services/storage/fcb/fcb.html) : Flash circular buffer provides an abstraction through which you can treat flash like a FIFO. You append entries to the end, and read data from the beginning.

## RPC

- eRPC : https://github.com/EmbeddedRPC/erpc

### flash database
- [FlashDB](https://github.com/armink/FlashDB)

## file system
- [littlefs](https://github.com/littlefs-project/littlefs) : Nor Flash
- [YafFS-2](https://yaffs.net/) : 适合 Nand Flash

## JSON
- [cJSON](https://github.com/DaveGamble/cJSON)
- [Lightweight JSON text parser](https://github.com/MaJerle/lwjson) : Lightweight JSON parser for embedded systems


## math library
- [CMSIS DSP](https://github.com/ARM-software/CMSIS-DSP) : CMSIS Version 5 Development Repository
- [libfixmath](https://github.com/PetteriAimonen/libfixmath) : Cross Platform Fixed Point Maths Library
- [smolar](https://github.com/Maharshi-Pandya/smolar) : a tiny multidimensional array implementation in C similar to numpy, but only one file.
- [Zephyr Scientific Library (zscilib)](https://github.com/zephyrproject-rtos/zscilib) : An open-source scientific computing library for embedded systems running Zephyr OS or standalone.
- [liquid-dsp](https://github.com/jgaeddert/liquid-dsp) : digital signal processing library for software-defined radios



## shell
- [letter shell](https://github.com/NevermindZZT/letter-shell) : 可以让串口对现有函数进行组合以及调用
- [Lightweight shell](https://github.com/MaJerle/lwshell) : Lightweight shell implementation for embedded systems



## button/key
- [MultiButton](https://github.com/0x1abin/MultiButton) : 按键管理
- [Lightweight event manager](https://github.com/MaJerle/lwbtn) : Lightweight button handler for embedded systems



## timer
- [MultiTimer](https://github.com/0x1abin/MultiTimer) : 软件定时器
- [perf_counter](https://github.com/GorgonMeducer/perf_counter) : A dedicated performance counter for Cortex-M systick. It shares the SysTick with users' original SysTick function without interfering it. This library will bring new functionalities, such as performance counter, delay_us and clock() service defined in time.h
- [Lightweight Date, Time & Cron](https://github.com/MaJerle/lwdtc) : Lightweight date, time & cron utilities for embedded systems
- [Lightweight Watchdog for embedded systems](https://github.com/MaJerle/lwwdg) : Lightweight watchdog for RTOS and embedded systems


## checksum
- [libcrc](https://github.com/lammertb/libcrc) : CRC 校验数据完整性

## Tracer
- [CmBacktrace](https://github.com/armink/CmBacktrace)

## oop framework
- [PLOOC](https://github.com/GorgonMeducer/PLOOC)

## test framework
- []()

## runtime
- []()

## dfu
- []()

## bootloader
- [mcuboot](https://www.mcuboot.com/)

## usb
- [tinyusb](https://github.com/hathach/tinyusb)

## bluetooth
- [btstack](https://github.com/bluekitchen/btstack)

## TCP/IP
- [uIP](https://www.wikiwand.com/en/UIP_(micro_IP))

## GUI
- [LVGL](https://lvgl.io/) : Light and Versatile Graphics Library

### Menu
- []()

## font
- []()

## mqtt
- [mqttclient](https://github.com/jiejieTop/mqttclient) : A high-performance, high-stability, cross-platform MQTT client, developed based on the socket API, can be used on embedded devices (FreeRTOS / LiteOS / RT-Thread / TencentOS tiny), Linux, Windows, Mac, with a very concise The API interface realizes the quality of service of QOS2 with very few resources, and seamlessly connects the mbedtls encryp…



## random number generator
- []()

## C++ template
- [Embedded Template Library (ETL)](https://github.com/ETLCPP/etl)

## public domain libraries
- [stb](https://github.com/nothings/stb)


## compression

- [heatshrink](https://github.com/atomicobject/heatshrink)
- [heatshrink-sfh](https://github.com/cnlohr/heatshrink-sfh) : Single-file-header, stripped-down version of the heatshrink decompression algorithm.
- [tinf - tiny inflate library](https://github.com/jibsen/tinf/) : Tiny inflate library (inflate, gzip, zlib)
- [Golomb-Rice Coding](https://urchin.earth.li/~twic/Golomb-Rice_Coding.html)
  - [brookicv/GolombCode](https://github.com/brookicv/GolombCode)
  - [Golomb及指数哥伦布编码原理介绍及实现](https://www.cnblogs.com/wangguchangqing/p/6297792.html)
  - [MichaelDipperstein/rice](https://github.com/MichaelDipperstein/rice)
  - [anirudhvr/golomb-coding](https://github.com/anirudhvr/golomb-coding)
- [kamyar-nemati/libecg](https://github.com/kamyar-nemati/libecg) : Hybrid lossless and lossy compression technique for ECG signals
- Run-length encoding algorithm
  - [MichaelDipperstein/rle](https://github.com/MichaelDipperstein/rle) : An ANSI C implementation of Run Length Encoding
- Huffman
  - [MichaelDipperstein/huffman](https://github.com/MichaelDipperstein/huffman) : An ANSI C implementation of Huffman coding
  - [Comparison Between (RLE And Huffman) Algorithmsfor Lossless Data Compression](https://core.ac.uk/download/pdf/228547034.pdf)
- Delta coding
  - [MichaelDipperstein/delta](https://github.com/MichaelDipperstein/delta) : an ANSI C implementation of adaptive delta coding
- BitArray
  - [noporpoise/BitArray](https://github.com/noporpoise/BitArray)
  - [MichaelDipperstein/bitarray](https://github.com/MichaelDipperstein/bitarray)
  - [ilanschnell/bitarray](https://github.com/ilanschnell/bitarray/blob/master/bitarray/_bitarray.c) : efficient arrays of booleans for Python

### ImageCodec

- [Quite OK Image Format](https://github.com/phoboslab/qoi) : The “Quite OK Image Format” for fast, lossless image compression
    - [qoir](https://github.com/nigeltao/qoir) : A fast, simple, lossless image file format.
    - [QOIX](https://github.com/AuburnSounds/gamut) : Image encoding and decoding library for D. Detailed layout control. Experimental codec QOIX.

#### PNG

- [libpng](http://www.libpng.org/pub/png/libpng.html)
- [LodePNG](https://github.com/lvandeve/lodepng) : 解码 VGA 图片需要 2.3MB 的内存空间
- [SPNG](https://github.com/randy408/libspng) : 对嵌入式比较友好，解码 VGA 图片只需要 50KB 空间
  - https://github.com/richgel999/miniz : 谷歌平替 zlib
- [PNGdec](https://github.com/bitbank2/PNGdec) : Arduino PNG image decoder library
- https://github.com/misc0110/libattopng
- https://github.com/elanthis/upng

#### JPG

- [libjpeg](https://libjpeg.sourceforge.net/)
- https://github.com/richgel999/picojpeg
- [TinyJPEG](https://github.com/serge-rgb/TinyJPEG) : Single header lib for JPEG encoding. Public domain. C99. stb style.



### GIF

- [Libnsgif](https://www.netsurf-browser.org/projects/libnsgif/) : 基本不需要额外内存空间
- https://giflib.sourceforge.net/
- https://github.com/lecram/gifdec : small C GIF decoder
- [AnimatedGIF](https://github.com/bitbank2/AnimatedGIF) : A lightweight Arduino GIF decoder for playing animated files from memory or files on SD cards





## code style
- [MaJerle/c-code-style](https://github.com/MaJerle/c-code-style)
- [mcinglis/c-style](https://github.com/mcinglis/c-style)

## blog
- [interrupt blog](https://interrupt.memfault.com/)

## Alternatives

- https://github.com/iDoka/awesome-embedded-software
- https://github.com/nhivp/Awesome-Embedded
- https://github.com/rust-embedded/awesome-embedded-rust
- https://github.com/fkromer/awesome-embedded-linux
