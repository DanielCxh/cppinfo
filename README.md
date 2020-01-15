# C/CPP信息大全
关于 C/C++ 框架、库和资源的一系列汇总列表。

- [ 1. 标准库](#标准库)
- [ 2. 框架](#框架)
- [ 3. 人工智能](#人工智能)
- [ 4. 异步事件循环](#异步事件循环)
- [ 5. 音频](#音频)
- [ 6. 生态学](#生态学)
- [ 7. 压缩](#压缩)
- [ 8. 并发与多线程](#并发与多线程)
- [ 9. 容器](#容器)
- [10. 密码](#密码)
- [11. 数据库](#数据库)
- [12. 调试](#调试)
- [13. 游戏引擎](#游戏引擎)
- [14. HMI](#HMI)
- [15. 图形](#图形)
- [16. 图像处理](#图形处理)
- [17. 国际化](#国际化)
- [18. JSON](#JSON)
- [19. 日志](#日志)
- [20. 机器学习](#机器学习)
- [21. 数学库](#数学库)
- [22. 多媒体](#多媒体)
- [23. 网络](#网络)
- [24. 物理学](#物理学)
- [25. 机器人](#机器人)
- [26. 科学计算](#科学计算)
- [27. 脚本](#脚本)
- [28. 序列号](#序列号)
- [29. 视频](#视频)
- [30. 虚拟机](#虚拟机)
- [31. Web应用框架](#Web应用框架)
- [32. XML](#XML)
- [33. 通用组件](#通用组件)
- [34. 软件](#软件)
    - [编译器](#编译器)
    - [在线编译](#在线编译)
    - [调试器](#调试器)
    - [IDE](#IDE)
    - [构建系统](#构建系统)
    - [静态代码分析](#静态代码分析)
- [35. 在线代码仓库](#在线代码仓库)
- [36. 网站](#网站)

---

### 标准库
C++标准库，包括了STL容器，算法和函数等
+ [C++ Standard Library](http://www.cplusplus.com/reference/) - 是一系列类和函数的集合，使用核心语言编写，也是C++ISO自身标准的一部分
+ [Standard Template Library](http://www.martinbroadhurst.com/stl/) - 标准模板库
+ [C POSIX library](http://www.gnu.org/software/libc/libc.html) - POSIX系统的C标准库规范
+ [ISO C++ Standards Committee](https://github.com/cplusplus) - C++标准委员会

### 框架
C++通用框架和库
+ [Apache C++ Standard Library](http://stdcxx.apache.org/) - 一系列算法，容器，迭代器和其他基本组件的集合
+ [ASL](http://stlab.adobe.com/) - Adobe源代码库提供了同行的评审和可移植的C++源代码库
+ [Boost](https://github.com/boostorg) - 大量通用C++库的集合
+ [BDE](https://github.com/bloomberg/bde) - 来自于彭博资讯实验室的开发环境
+ [Cinder](https://libcinder.org/) - 提供专业品质创造性编码的开源开发社区
+ [Cxxomfort](http://ryan.gulix.cl/fossil.cgi/cxxomfort/index) - 轻量级的，只包含头文件的库，将C++ 11的一些新特性移植到C++03中
+ [Dlib](http://dlib.net/) - 使用契约式编程和现代C++科技设计的通用的跨平台的C++库
+ [EASTL](https://github.com/paulhodge/EASTL) - EA-STL公共部分
+ [ffead-cpp](https://github.com/sumeetchhetri/ffead-cpp) - 企业应用程序开发框架
+ [Folly](https://github.com/facebook/folly) - 由Facebook开发和使用的开源C++库
+ [JUCE](https://github.com/WeAreROLI/JUCE) - 包罗万象的C++类库，用于开发跨平台软件
+ [libPhenom](https://github.com/facebookarchive/libphenom) - 用于构建高性能和高度可扩展性系统的事件框架
+ [LibSourcey](https://github.com/sourcey/libsourcey) - 用于实时的视频流和高性能网络应用程序的C++11 evented IO
+ [LibU](https://github.com/koanlogic/libu) - C语言写的多平台工具库
+ [Loki](https://github.com/grafana/loki) - C++库的设计，包括常见的设计模式和习语的实现
+ [MiLi](https://bitbucket.org/fudepan/mili/wiki/Home) - 只含头文件的小型C++库
+ [openFrameworks](https://openframeworks.cc/) - 开发C++工具包，用于创意性编码
+ [Qt](https://www.qt.io/developers) - 跨平台的应用程序和用户界面框架
+ [ROOT](https://root.cern.ch/) - 具备所有功能的一系列面向对象的框架，能够非常高效地处理和分析大量的数据，为欧洲原子能研究机构所用
+ [STLport](http://www.stlport.org/) - 是STL具有代表性的版本
+ [STXXL](http://stxxl.org/) - 用于额外的大型数据集的标准模板库
+ [Ultimate++](http://www.ultimatepp.org/) - C++跨平台快速应用程序开发框架
+ [Windows Template Library](http://www.docsultant.com/site2/articles/wtl.html) - 用于开发Windows应用程序和UI组件的C++库
+ [Yomm11](https://github.com/jll63/yomm11) - C++11的开放multi-methods


### 人工智能
+ [btsk](https://github.com/aigamedev/btsk) - 游戏行为树启动器工具
+ [Evolving Objects](http://eodev.sourceforge.net/) - 基于模板的，ANSI C++演化计算库，能够帮助你非常快速地编写出自己的随机优化算法


### 异步事件循环
+ [Asio](https://think-async.com/Asio/) - 用于网络和底层I/O编程的跨平台的C++库
+ [libev](http://libev.schmorp.de/) - 功能齐全，高性能的时间循环，轻微地仿效libevent，但是不再像libevent一样有局限性
+ [libuv](https://github.com/libuv/libuv) - 跨平台异步I/O


### 音频
音频，声音，音乐，数字化音乐库
+ [FMOD](https://www.fmod.com/) - 易于使用的跨平台的音频引擎和音频内容的游戏创作工具
+ [Maximilian](https://github.com/micknoise/Maximilian) - C++音频和音乐数字信号处理库
+ [OpenAL](http://www.openal.org/) - 开源音频库—跨平台的音频API
+ [Opus](http://opus-codec.org/) - 完全开放的，免版税的，高度通用的音频编解码器
+ [speex](https://www.speex.org/) - 免费编解码器，为Opus所废弃
+ [Tonic](https://github.com/TonicAudio/Tonic) - C++易用和高效的音频合成
+ [Vorbis](https://xiph.org/vorbis/) - Ogg Vorbis是一种完全开放的，非专有的，免版税的通用压缩音频格式


### 生态学
生物信息，基因组学和生物技术
+ [libsequence](http://molpopgen.github.io/libsequence/) - 用于表示和分析群体遗传学数据的C++库
+ [seqAn](http://www.seqan.de/) - 专注于生物数据序列分析的算法和数据结构
+ [vcflib](https://github.com/vcflib/vcflib) - 用于解析和处理VCF文件的C++库
+ [Wham](https://github.com/zeeev/wham) - 直接把联想测试应用到BAM文件的基因结构变异


### 压缩
压缩和归档库
+ [bzip2](http://www.bzip.org/) - 完全免费，免费专利和高质量的数据压缩
+ [doboz](https://bitbucket.org/attila_afra/doboz/src/default/) - 能够快速解压缩的压缩库
+ [PhysicsFS](https://icculus.org/physfs/) - 对各种归档提供抽象访问的库，主要用于视频游戏，设计灵感部分来自于Quake3的文件子系统
+ [KArchive](https://cgit.kde.org/karchive.git) - 用于创建，读写和操作文件档案（例如zip和 tar）的库，它通过QIODevice的一系列子类，使用gzip格式，提供了透明的压缩和解压缩的数据
+ [LZ4](https://github.com/lz4/lz4) - 非常快速的压缩算法
+ [LZHAM](https://github.com/richgel999/lzham_codec) - 无损压缩数据库，压缩比率跟LZMA接近，但是解压缩速度却要快得多
+ [LZMA](https://www.7-zip.org/sdk.html) - 7z格式默认和通用的压缩方法
+ [LZMAT](http://www.matcode.com/lzmat.htm) - 及其快速的实时无损数据压缩库
+ [Miniz](https://github.com/richgel999/miniz) - 单一的C源文件，紧缩/膨胀压缩库，使用zlib兼容API，ZIP归档读写，PNG写方式
+ [minizip](https://github.com/nmoinvaz/minizip) - 支持PKWARE磁盘跨越，AES加密和IO缓冲
+ [Snappy](https://github.com/google/snappy) - 快速压缩和解压缩
+ [zlib](http://zlib.net/) - 非常紧凑的数据流压缩库


### 并发与多线程
+ [Boost.Compute](https://github.com/boostorg/compute) - 用于OpenCL的C++GPU计算库
+ [Bolt](https://github.com/HSA-Libraries/Bolt) - 针对GPU进行优化的C++模板库
+ [Intel TBB](https://github.com/intel/tbb) - Intel线程构件块
+ [libclsph](https://github.com/libclsph/libclsph) - 基于OpenCL的GPU加速SPH流体仿真库
+ [OpenCL](https://www.khronos.org/opencl/) - 并行编程的异构系统的开放标准
+ [OpenMP](https://www.openmp.org/) - OpenMP API
+ [Thrust](http://thrust.github.io/) - 类似于C++标准模板库的并行算法库
+ [HPX](https://github.com/STEllAR-GROUP/hpx/) - 用于任何规模的并行和分布式应用程序的通用C++运行时系统
+ [VexCL](https://github.com/ddemidov/vexcl) - 用于OpenCL/CUDA 的C++向量表达式模板库


### 容器
+ [C++ B-Tree](https://isocpp.org/blog/2013/02/b-tree-containers-from-google) - 基于B树数据结构，实现命令内存容器的模板库
+ [Hashmaps](https://github.com/goossaert/hashmap) - C++中开放寻址哈希表算法的实现


### 密码
+ [BCrypt](https://www.example-code.com/cpp/bcrypt_hash_password.asp) - 一个跨平台的文件加密工具，加密文件可以移植到所有可支持的操作系统和处理器中
+ [Botan](https://botan.randombit.net/) - C++加密库
+ [Crypto++](https://www.cryptopp.com/) - 一个有关加密方案的免费的C++库
+ [GnuPG](https://www.gnupg.org/) - OpenPGP标准的完整实现
+ [GnuTLS](http://www.gnutls.org/) - 实现了SSL，TLS和DTLS协议的安全通信库
+ [LibreSSL](http://www.libressl.org/) - 免费的SSL/TLS协议，属于2014 OpenSSL的一个分支
+ [libtomcrypt](https://github.com/libtom/libtomcrypt) - 一个非常全面的，模块化的，可移植的加密工具
+ [libsodium](https://github.com/jedisct1/libsodium) - 基于NaCI的加密库，固执己见，容易使用
+ [Nettle](http://www.lysator.liu.se/~nisse/nettle/) - 底层的加密库
+ [OpenSSL](https://www.openssl.org/) - 一个强大的，商用的，功能齐全的，开放源代码的加密库
+ [Tiny AES](https://github.com/kokke/tiny-AES-c) - 用C实现的一个小巧，可移植的实现了AES128ESB的加密算法


### 11.数据库
数据库，SQL服务器，ODBC驱动程序和工具
+ [hiberlite](https://github.com/paulftw/hiberlite) - 用于Sqlite3的C++对象关系映射
+ [hiredis](https://github.com/redis/hiredis) - 用于Redis数据库的很简单的C客户端库
+ [leveldb](https://github.com/google/leveldb) - 快速键值存储库
+ [symas LMDB](http://symas.com/mdb/) - 
+ [MySQL++](http://www.tangentsoft.net/mysql++/) - 封装了MySql的C API的C++ 包装器
+ [RocksDB](https://github.com/facebook/rocksdb) - 来自Facebook的嵌入键值的快速存储
+ [SQLite](https://www.sqlite.org/index.html) - 一个完全嵌入式的，功能齐全的关系数据库，只有几百KB，可以正确包含到你的项目中


### 调试
调试库， 内存和资源泄露检测，单元测试
+ [Boost.Test](https://www.boost.org/doc/libs/master/libs/test/doc/html/index.html) - Boost测试库
+ [Catch2](https://github.com/catchorg/Catch2) - 时尚的C++原生的框架，只包含头文件，用于单元测试，测试驱动开发和行为驱动开发
+ [CppUnit](https://www.freedesktop.org/wiki/Software/cppunit/) - 由JUnit移植过来的C++测试框架
+ [CTest](https://cmake.org/cmake/help/v2.8.8/ctest.html) - CMake测试驱动程序
+ [GoogleTest](https://github.com/google/googletest) - 谷歌C++测试框架
+ [ig-debugheep](https://github.com/deplinenoise/ig-debugheap) - 用于跟踪内存错误的多平台调试堆
+ [libtap](https://github.com/zorgnax/libtap) - 用C语言编写测试
+ [MemTrack](http://www.almostinfinite.com/memtrack.html) - 用于C++跟踪内存分配
+ [microprofile](https://bitbucket.org/jonasmeyer/microprofile/src) - 跨平台的网络试图分析器
+ [minUnit](http://www.jera.com/techinfo/jtns/jtn002.html) - 使用C写的迷你单元测试框架，只使用了两个宏
+ [Remotery](https://github.com/Celtoys/Remotery) - 用于web视图的单一C文件分析器
+ [UnitTest](https://github.com/unittest-cpp/unittest-cpp) - 轻量级的C++单元测试框架


### 游戏引擎
+ [Cocos2d-x](https://www.cocos.com/) - 一个跨平台框架，用于构建2D游戏，互动图书，演示和其他图形应用程序
+ [Grit](https://github.com/sparkprime/grit-engine) - 社区项目，用于构建一个免费的游戏引擎，实现开放的世界3D游戏
+ [Irrlicht](https://github.com/zaki/irrlicht) - C++语言编写的开源高性能的实时#D引擎
+ [Polycode](http://polycode.org/) - C++实现的用于创建游戏的开源框架（与Lua绑定）


### HMI
+ [CEGUI](http://static.cegui.org.uk/) - 很灵活的跨平台GUI库
+ [FLTK](https://www.fltk.org/index.php) - 快速，轻量级的跨平台的C++GUI工具包
+ [GTK](http://www.gtk.org/) - 用于创建图形用户界面的跨平台工具包
+ [gtkmm](https://www.gtkmm.org/en/) - 用于受欢迎的GUI库GTK+的官方C++接口
+ [imgui](https://github.com/ocornut/imgui) - 拥有最小依赖关系的立即模式图形用户界面
+ [libRocket](https://github.com/libRocket/libRocket) - C++ HTML/CSS 游戏接口中间件
+ [MyGUI](http://mygui.info/) - 快速，灵活，简单的GUI
+ [Ncurses](https://invisible-island.net/ncurses/) - 终端用户界面
+ [QCustomPlot](https://www.qcustomplot.com/) - 没有更多依赖关系的Qt绘图控件
+ [qwt](https://github.com/osakared/qwt/tree/trunk/qwt) - 用户与技术应用的Qt 控件
+ [QwtPlot3D](https://github.com/sintegrial/qwtplot3d) - 功能丰富的基于Qt/OpenGL的C++编程库，本质上提供了一群3D控件
+ [OtherUI](https://github.com/Twolewis/OtterUI) - 是用于嵌入式系统和互动娱乐软件的用户界面开发解决方案
+ [PDCurses](https://github.com/wmcbrine/PDCurses) - 包含源代码和预编译库的公共图形函数库
+ [wxWidget](http://wxwidgets.org/) - 允许开发人员使用一个代码库可以为widows， Mac OS X，Linux和其他平台创建应用程序


### 图形
+ [bgfx](https://github.com/bkaradzic/bgfx) - 跨平台的渲染库
+ [Cairo](http://www.cairographics.org/) - 支持多种输出设备的2D图形库
+ [Horde3D](https://github.com/horde3d/Horde3D) - 一个小型的3D渲染和动画引擎
+ [magnum](https://github.com/mosra/magnum) - C++11和OpenGL 2D/3D 图形引擎
+ [Ogre 3D](https://www.ogre3d.org/) - 用C++编写的一个面向场景，实时，灵活的3D渲染引擎（并非游戏引擎）
+ [OpenSceneGraph](http://www.openscenegraph.org/) - 具有高性能的开源3D图形工具包
+ [Panda3D](http://www.panda3d.org/) - 用于3D渲染和游戏开发的框架，用Python和C++编写
+ [skia](https://github.com/google/skia) - 用于绘制文字，图形和图像的完整的2D图形库
+ [Urho3D](https://github.com/urho3d/Urho3D) - 跨平台的渲染和游戏引擎


### 图形处理
+ [Boost.GIL](https://www.boost.org/doc/libs/1_56_0/libs/gil/doc/index.html) - 通用图像库
+ [CImg](http://cimg.eu/download.shtml) - 用于图像处理的小型开源C++工具包
+ [CxImage](https://github.com/movableink/cximage) - 用于加载，保存，显示和转换的图像处理和转换库，可以处理的图片格式包括 BMP, JPEG, GIF, PNG, TIFF, MNG, ICO, PCX, TGA, WMF, WBMP, JBG, 
+ [freeimage](https://github.com/imazen/freeimage) - 支持现在多媒体应用所需的通用图片格式和其他格式
+ [ITK](http://www.itk.org/) - 跨平台的开源图像分析系统
+ [imagemagick](https://imagemagick.org/index.php) - ImageMagick程序的C++接口
+ [OpenCV](https://opencv.org/) - 开源计算机视觉类库
+ [VIGRA](https://github.com/ukoethe/vigra) - 用于图像分析通用C++计算机视觉库
+ [VTK](https://vtk.org/) - 用于3D计算机图形学，图像处理和可视化的开源免费软件系统


### 17.国际化
+ [gettext](http://www.gnu.org/software/gettext/) - GNU `gettext`
+ [IBM ICU](http://site.icu-project.org/) - 提供Unicode 和全球化支持的C、C++ 和Java库
+ [libiconv](http://www.gnu.org/software/libiconv/) - 用于不同字符编码之间的编码转换库


### JSON
+ [frozen](https://github.com/cesanta/frozen) - C/C++的Json解析生成器
+ [jansson](https://github.com/akheron/jansson) - 进行编解码和处理Jason数据的C语言库
+ [jbson](https://github.com/chrismanning/jbson) - C++14中构建和迭代BSON data,和Json 文档的库
+ [JeayeSON](https://github.com/jeaye/jeayeson) - 非常健全的C++ JSON库，只包含头文件
+ [JSON++](https://github.com/hjiang/jsonxx) - C++ JSON 解析器
+ [josn-parser](https://github.com/udp/json-parser) - 用可移植的ANSI C编写的JSON解析器，占用内存非常少
+ [json11](https://github.com/dropbox/json11) - 一个迷你的C++11 JSON库
+ [jute](https://github.com/amir-s/jute) - 非常简单的C++ JSON解析器
+ [libjson](https://github.com/vincenthz/libjson) - C语言中的JSON解析和打印库，很容易和任何模型集成
+ [PicoJSON](https://github.com/kazuho/picojson) - C++中JSON解析序列化，只包含头文件
+ [Qt-json](https://github.com/qt-json/qt-json) - 用于JSON数据和 QVariant层次间的相互解析的简单类
+ [QJson](https://github.com/flavio/qjson) - 将JSON数据映射到QVariant对象的基于Qt的库
+ [RapidJSON](https://github.com/Tencent/rapidjson) - 用于C++的快速JSON 解析生成器，包含SAX和DOM两种风格的API
+ [YAJL](https://github.com/lloyd/yajl) - C语言中快速流JSON解析库


### 日志
+ [Boost.Log](https://www.boost.org/doc/libs/1_56_0/libs/log/doc/html/index.html) - 计非常模块化，并且具有扩展性
+ [EasyLoggine++](https://github.com/amrayn/easyloggingpp) - C++日志库，只包含单一的头文件
+ [log4cpp](https://github.com/orocos-toolchain/log4cpp) - 一系列C++类库，灵活添加日志到文件，系统日志，IDSA和其他地方
+ [templog](http://www.templog.org/) - 轻量级C++库，可以添加日志到你的CPP应用程序中


### 20.机器学习
+ [Caffe](https://github.com/BVLC/caffe) - 快速的神经网络框架
+ [CCV](https://github.com/liuliu/ccv) - 以C语言为核心的现代计算机视觉库
+ [mlpack](https://www.mlpack.org/) - 可扩展的C++机器学习库
+ [OpenCV](https://github.com/opencv/opencv) - 开源计算机视觉库
+ [Recommender](https://github.com/GHamrouni/Recommender) - 使用协同过滤进行产品推荐/建议的C语言库
+ [SHOGUN](https://github.com/shogun-toolbox/shogun) - SHOGUN机器学习工具
+ [SoFiA](https://github.com/SoFiA-Admin/SoFiA) - 机器学习的快速增量算法套件


### 数学库
+ [Armadillo](https://github.com/patrickfav/armadillo) - 高质量的C++线性代数库，速度和易用性做到了很好的平衡，语法和MatlAB很相似
+ [Blaze](https://github.com/blaze/blaze) - 高性能的C++数学库，用于密集和稀疏算法
+ [Ceres Solver](http://ceres-solver.org/) - 来自谷歌的C++库，用于建模和解决大型复杂非线性最小平方问题
+ [CGal](https://www.cgal.org/) - 高效，可靠的集合算法集合
+ [CML](https://github.com/demianmnave/CML/wiki/The-Configurable-Math-Library) - 用于游戏和图形的免费C++数学库
+ [Eigen](http://eigen.tuxfamily.org/index.php?title=Main_Page) - 高级C++模板头文件库，包括线性代数，矩阵，向量操作，数值解决和其他相关的算法
+ [GMP](https://gmplib.org/) - 用于个高精度计算的C/C++库，处理有符号整数，有理数和浮点数

### 多媒体
+ [GStreamer](https://gstreamer.freedesktop.org/) - 构建媒体处理组件图形的库
+ [Live555](http://www.live555.com/liveMedia/) - 使用开放标准协议(RTP/RTCP, RTSP, SIP) 的多媒体流库
+ [libVLC](https://wiki.videolan.org/LibVLC) - libVLC (VLC SDK)媒体框架
+ [QtAV](https://github.com/wang-bin/QtAV) - 基于Qt和FFmpeg的多媒体播放框架，能够帮助你轻而易举地编写出一个播放器
+ [SDL](http://www.libsdl.org/) - 简单直控媒体层
+ [SFML](http://www.sfml-dev.org/) - 快速，简单的多媒体库


### 网络
+ [ACE](https://github.com/ajaxorg/ace) - C++面向对象网络变成工具包
+ [ASIO](https://think-async.com/Asio/) - 用于网络和底层I/O编程的跨平台的C++库
+ [cpp-netlib](https://cpp-netlib.org/) - 高级网络编程的开源库集合
+ [dyad.c](https://github.com/rxi/dyad) - C语言的异步网络
+ [libcurl](https://curl.haxx.se/libcurl/) - 多协议文件传输库
+ [Mongoose](https://github.com/cesanta/mongoose) - 非常轻量级的网络服务器
+ [Muduo](https://github.com/chenshuo/muduo) - 用于Linux多线程服务器的C++非阻塞网络库
+ [net skeleton](https://github.com/cesanta/net_skeleton) - C/C++的TCP 客户端/服务器库
+ [WAFer](https://github.com/riolet/WAFer) - 基于C语言的超轻型软件平台，用于可扩展的服务器端和网络应用
+ [Onion](https://github.com/davidmoreno/onion) - C语言HTTP服务器库，其设计为轻量级，易使用
+ [POCO](https://github.com/pocoproject) - 用于构建网络和基于互联网应用程序的C++类库，可以运行在桌面，服务器，移动和嵌入式系统
+ [RakNet](https://github.com/facebookarchive/RakNet) - 为游戏开发人员提供的跨平台的开源C++网络引擎
+ [WebSocket++](https://github.com/zaphoyd/websocketpp) - 基于C++/Boost Aiso的websocket 客户端/服务器库
+ [ZeroMQ](https://zeromq.org/) - 高速，模块化的异步通信库


### 物理学
动力学仿真引擎
+ [Box2D](https://github.com/erincatto/Box2D) - 2D的游戏物理引擎
+ [Bullet](https://github.com/bulletphysics/bullet3) - 3D的游戏物理引擎
+ [Chipmunk2D](https://github.com/slembcke/Chipmunk2D) - 快速，轻量级的2D游戏物理库
+ [LiquidFun](https://github.com/google/liquidfun) - 2D的游戏物理引擎
+ [ODE](http://www.ode.org/) - 开放动力学引擎-开源，高性能库，模拟刚体动力学
+ [ofxBox2d](https://github.com/vanderlin/ofxBox2d) - Box2D开源框架包装器
+ [Simbody](https://github.com/simbody/simbody) - 高性能C++多体动力学/物理库，模拟关节生物力学和机械系统，像车辆，机器人和人体骨骼


### 25.机器人
+ [MOOS-IvP](https://oceanai.mit.edu/moos-ivp/pmwiki/pmwiki.php?n=Main.HomePage) - 一组开源C++模块，提供机器人平台的自主权，尤其是自主的海洋车辆
+ [MRPT](https://www.mrpt.org/) - 移动机器人编程工具包
+ [Point Cloud Library](https://github.com/PointCloudLibrary/pcl) - 点云库是一个独立的，大规模的开放项目，用于2D/3D图像和点云处理
+ [Robotics Library (RL)](https://www.roboticslibrary.org/) - 一个独立的C++库，包括机器人动力学，运动规划和控制
+ [ROS](http://wiki.ros.org/) - 机器人操作系统，提供了一些库和工具帮助软件开发人员创建机器人应用程序


### 科学计算
+ [FFTW](http://www.fftw.org/) - 用一维或者多维计算DFT的C语言库
+ [GSL](http://www.gnu.org/software/gsl/) - GNU科学库


### 27.脚本
+ [ChaiScript](https://github.com/ChaiScript/ChaiScript/) - 用于C++的易于使用的嵌入式脚本语言
+ [Lua](http://www.lua.org/) - 用于配置文件和基本应用程序脚本的小型快速脚本引擎
+ [Luaxx](https://github.com/dafrito/luacxx) - 用于创建Lua绑定的C++ 11 API
+ [SWIG](http://www.swig.org/) - 一个可以让你的C++代码链接到JavaScript，Perl，PHP，Python，Tcl和Ruby的包装器/接口生成器
+ [V7](https://github.com/cesanta/v7) - 嵌入式的JavaScript 引擎
+ [V8](https://github.com/v8/v8) - 谷歌的快速JavaScript引擎，可以被嵌入到任何C++应用程序中


### 序列号
+ [CAP'N PROTO](https://capnproto.org/) - 快速数据交换格式和RPC系统
+ [cereal](https://github.com/USCiLab/cereal) - C++11 序列化库
+ [FlatBuffers](https://github.com/google/flatbuffers) - 内存高效的序列化库
+ [msgpack](https://github.com/msgpack/msgpack-c) - C/C++的高效二进制序列化库，例如 JSON
+ [Protocol Buffers](https://github.com/protocolbuffers/protobuf) - 协议缓冲，谷歌的数据交换格式
+ [Protocol-c]()https://github.com/protobuf-c/protobuf-c - C语言的协议缓冲实现
+ [Simple Binary Encoding](https://github.com/real-logic/simple-binary-encoding) - 用于低延迟应用程序的对二进制格式的应用程序信息的编码和解码
+ [Thrift](https://thrift.apache.org/) - 高效的跨语言IPC/RPC，用于C++，Java，Python，PHP，C#和其它多种语言中，最初由Twitter开发


### 视频
+ [libvpx](https://github.com/webmproject/libvpx) - VP8/VP9编码解码SDK
+ [FFmpeg](https://www.ffmpeg.org/) - 一个完整的，跨平台的解决方案，用于记录，转换视频和音频流
+ [libde265](https://github.com/strukturag/libde265) - 开放的h.265视频编解码器的实现
+ [OpenH264](https://github.com/cisco/openh264) - 开源H.264 编解码器
+ [Theora](https://www.theora.org/) - 免费开源的视频压缩格式


### 虚拟机
+ [CarpVM](https://github.com/tekknolagi/carp) - C中有趣的VM，让我们一起来看看这个
+ [MicroPython](https://github.com/micropython/micropython) - 旨在实现单片机上Python3.x的实现
+ [TinyVM](https://github.com/jakogut/tinyvm) - 用纯粹的ANSI C编写的小型，快速，轻量级的虚拟机

### Web应用框架
+ [Civetweb](https://github.com/civetweb/civetweb) - 提供易于使用，强大的，C/C++嵌入式Web服务器，带有可选的CGI，SSL和Lua支持
+ [CppCMS](http://cppcms.com/wikipp/en/page/main) - 免费高性能的Web开发框架
+ [Crow](https://github.com/ipkn/crow) - 一个C++微型web框架
+ [Kore](https://kore.io/) - 使用C语言开发的用于web应用程序的超快速和灵活的web服务器/框架
+ [libOnion](https://www.coralbits.com/libonion/) - 轻量级的库，帮助你使用C编程语言创建web服务器
+ [QDjango](https://github.com/jlaine/qdjango/) - 使用C++编写的，基于Qt库的web框架，试图效仿Django API，因此得此名
+ [wt](https://www.webtoolkit.eu/wt) - 开发Web应用的C++库

### XML
+ [Expat](https://libexpat.github.io/) - 用C语言编写的xml解析库
+ [Libxml2](http://xmlsoft.org/) - Gnome的xml C解析器和工具包
+ [Libxmljs](https://github.com/libxmljs/libxmljs) - C++的xml解析器
+ [PugiXML](https://pugixml.org/) - 用于C++的，支持XPath的轻量级，简单快速的XML解析器
+ [rapidxml](https://github.com/dwd/rapidxml) - 试图创建最快速的XML解析器，同时保持易用性，可移植性和合理的W3C兼容性
+ [TinyXML-2](https://github.com/leethomason/tinyxml2) - TinyXML的一个全新的接口，使用了C++的许多许多优势，模板，异常和更好的异常处理
+ [Xerces-C](http://xerces.apache.org/xerces-c/) - 用可移植的C++的子集编写的XML验证解析器

### 通用组件
+ [FMT](https://github.com/fmtlib/fmt) - C++的小型，安全和快速格式化库
+ [Casacore](https://github.com/casacore/casacore) - 从aips++ 派生的一系列C++核心库
+ [cxx-prettyprint](https://github.com/louisdx/cxx-prettyprint) - 用于C++容器的打印库
+ [DynaForms](https://www.dynaforms.com/en/home.html) - 易于使用的PDF生成库
+ [gcc-poison](https://github.com/leafsr/gcc-poison) - 帮助开发人员禁止应用程序中的不安全的C/C++函数的简单的头文件
+ [Google Test](https://github.com/google/googletest) - 进行单元测试的工具
+ [HTTP Parser](https://github.com/nodejs/http-parser) - C的http请求/响应解析器
+ [libevil](https://github.com/avati/libevil) - 许可证管理器
+ [libusb](https://github.com/libusb/libusb) - 允许移动访问USB设备的通用USB库
+ [PCRE](http://pcre.org/) - 正则表达式C库，灵感来自于Perl中正则表达式的功能
+ [Remote Call Framework](http://www.deltavsoft.com/) - C++的进程间通信框架
+ [Scintilla](https://scintilla.org/) - 开源的代码编辑控件
+ [Serial Communication Library](https://github.com/wjwwood/serial) - C++语言编写的跨平台，串口库
+ [Simple Dynamic Strings](https://github.com/antirez/sds) - C的简单动态字符串库
+ [SLRE](https://github.com/cesanta/slre) - 超轻的正则表达式库
+ [Stage Simulator](https://github.com/rtv/Stage) - 移动机器人模拟器
+ [ZBar](https://github.com/ZBar/ZBar) - 条形码扫描器’库，可以扫描照片，图片和视频流中的条形码，并返回结果
+ [CppVerbalExpressions](https://github.com/VerbalExpressions/CppVerbalExpressions) - 易于使用的C++正则表达式
+ [QtVerbalExpressions](https://github.com/VerbalExpressions/QtVerbalExpressions) - 基于C++ VerbalExpressions 库的Qt库
+ [PHP-CPP](https://github.com/CopernicaMarketingSoftware/PHP-CPP) - 使用C++来构建PHP扩展的库
+ []() - C的另一个字符串库，功能更丰富，但是没有缓冲溢出问题，还包含了一个C++包装器


### 软件
#### 编译器
+ [Clang](http://clang.llvm.org/) - 由苹果公司开发的
+ [GCC](https://gcc.gnu.org/) - GNU编译器集合
+ [Intel C++ Compiler](https://software.intel.com/en-us/c-compilers) - 由英特尔公司开发
+ [LLVM](http://llvm.org/) - 模块化和可重用编译器和工具链技术的集合
+ [Microsoft Visual C++ ](https://msdn.microsoft.com/en-us/library/aa187916.aspx) - MSVC，由微软公司开发
+ [Open Watcom](https://github.com/open-watcom/open-watcom-v2) - Watcom，C，C++和Fortran交叉编译器和工具
+ [tcc](https://bellard.org/tcc/) - 轻量级的C语言编译器

#### 在线编译
+ [codepad](http://codepad.org/) - 在线编译器/解释器，一个简单的协作工具
+ [coliru](http://coliru.stacked-crooked.com/) - 在线编译器/shell， 支持各种C++编译器
+ [Compiler Explorer](https://gcc.godbolt.org/) - 交互式编译器，可以进行汇编输出
+ [ideone](https://ideone.com/) - 一个在线编译器和调试工具，允许你在线编译源代码并执行，支持60多种编程语言

#### 调试器
+ [GDB](https://www.gnu.org/software/gdb/) - GNU调试器
+ [Valgrind](http://valgrind.org/) - 内存调试，内存泄露检测，性能分析工具


#### IDE
+ [AppCode](https://www.jetbrains.com/objc/) - 构建与JetBrains’ IntelliJ IDEA 平台上的用于Objective-C，C,C++，Java和Java开发的集成开发环境
+ [CLion](https://www.jetbrains.com/clion/) - 来自JetBrains的跨平台的C/C++的集成开发环境
+ [CodeBlocks](http://www.codeblocks.org/) - 免费C，C++和Fortran的集成开发环境
+ [CodeLite](https://codelite.org/) - 一个跨平台的免费的C/C++集成开发环境
+ [Eclipse CDT](http://www.eclipse.org/cdt/) - 基于Eclipse平台的功能齐全的C和C++集成开发环境
+ [Geany](https://www.geany.org/) - 轻量级的快速，跨平台的集成开发环境
+ [IBM VisualAge](https://www.ibm.com/products/software) - 来自IBM的家庭计算机集成开发环境
+ [Irony-Mode](https://github.com/Sarcasm/irony-mode) - 由libclang驱动的用于Emacs的C/C++微模式
+ [KDevelop](https://www.kdevelop.org/) - 免费开源集成开发环境
+ [Misrosoft Visual Studio](https://visualstudio.microsoft.com/zh-hans/?rr=https%3A%2F%2Fwww.cnblogs.com%2F) - 来自微软的集成开发环境
+ [Qt Creator](https://www.qt.io/developers) - 跨平台的C++，Javascript和QML集成开发环境，也是Qt SDK的一部分
+ [rtags](https://github.com/Andersbakken/rtags) - C/C++的客户端服务器索引，用于 跟基于clang的emacs的集成
+ [Xcode](https://developer.apple.com/xcode/) - 由苹果公司开发


#### 构建系统
+ [Bear](https://github.com/rizsotto/Bear) - 用于为clang工具生成编译数据库的工具
+ [CMake](https://cmake.org/) - 跨平台的免费开源软件用于管理软件使用独立编译的方法进行构建的过程
+ [CPM](https://github.com/iauns/cpm) - 基于CMake和Git的C++包管理器
+ [FASTBuild](https://www.fastbuild.org/docs/home.html) - 高性能，开源的构建系统，支持高度可扩展性的编译，缓冲和网络分布
+ [Ninja](https://github.com/ninja-build/ninja) - 专注于速度的小型构建系统
+ [SCons](https://www.scons.org/) - 使用Python scipt 配置的软件构建工具
+ [Tundra](https://github.com/deplinenoise/tundra) - 性能的代码构建系统，甚至对于非常大型的软件项目，也能提供最好的增量构建次
+ [tup](http://gittup.org/tup/) - 基于文件的构建系统，用于后台监控变化的文件

#### 静态代码分析
+ [CppCheck](https://github.com/danmar/cppcheck/) - 静态C/C++代码分析工具
+ [OCLint](http://oclint.org/) - 用于C，C++和Objective-C的静态源代码分析工具，用于提高质量，减少瑕疵
+ [Clang Static Analyzer](http://clang-analyzer.llvm.org/index.html) - 查找C，C++和Objective-C程序bug的源代码分析工具


### 在线代码仓库
+ [GitHub]() - 最知名的Git仓库
+ [GitLab]() - 
+ [Bitbucket](https://bitbucket.org/product/) - 优秀的Git仓库


### 网站
+ [cplusplus](http://www.cplusplus.com/) - C++官方学习网站
+ [Awesome C++](https://cpp.libhunt.com/) - C++开源库集合
