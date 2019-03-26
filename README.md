# 历史

稍微很长的历史，来源网络，可以先跳过。

## C语言的发展阶段

C 语言之所以命名为 C，是因为 C 语言源自 Ken Thompson 发明的 B 语言，而 B 语言则源自 BCPL 语言。

- 1967年，剑桥大学的Martin Richards对CPL语言进行了简化，于是产生了BCPL（Basic Combined Programming Language）语言。
- 20世纪60年代，美国AT&T公司贝尔实验室（AT&T Bell Laboratory）的研究员Ken Thompson闲来无事，手痒难耐，想玩一个他自己编的，模拟在太阳系航行的电子游戏——Space Travel。他背着老板，找到了台空闲的机器——PDP-7。但这台机器没有操作系统，而游戏必须使用操作系统的一些功能，于是他着手为PDP-7开发操作系统。后来，这个操作系统被命名为——UNIX。
- 1970年，美国贝尔实验室的 Ken Thompson，以BCPL语言为基础，设计出很简单且很接近硬件的B语言（取BCPL的首字母）。并且他用B语言写了第一个UNIX操作系统。
- 1971年，同样酷爱Space Travel的Dennis M.Ritchie为了能早点儿玩上游戏，加入了Thompson的开发项目，合作开发UNIX。他的主要工作是改造B语言，使其更成熟。
- 1972年，美国贝尔实验室的 D.M.Ritchie 在B语言的基础上最终设计出了一种新的语言，他取了BCPL的第二个字母作为这种语言的名字，这就是C语言。
- 1973年初，C语言的主体完成。Thompson和Ritchie迫不及待地开始用它完全重写了UNIX。此时，编程的乐趣使他们已经完全忘记了那个"Space Travel"，一门心思地投入到了UNIX和C语言的开发中。随着UNIX的发展，C语言自身也在不断地完善。直到今天，各种版本的UNIX内核和周边工具仍然使用C语言作为最主要的开发语言，其中还有不少继承Thompson和Ritchie之手的代码。在开发中，他们还考虑把UNIX移植到其他类型的计算机上使用。C语言强大的移植性（Portability）在此显现。机器语言和汇编语言都不具有移植性，为x86开发的程序，不可能在Alpha,SPARC和ARM等机器上运行。而C语言程序则可以使用在任意架构的处理器上，只要那种架构的处理器具有对应的C语言编译器和库，然后将C源代码编译、连接成目标二进制文件之后即可运行。
- 1977年，Dennis M.Ritchie发表了不依赖于具体机器系统的C语言编译文本《可移植的C语言编译程序》。
- 1978年由美国电话电报公司(AT&T）贝尔实验室正式发表了C语言。布莱恩·柯林汉（Brian Kernighan） 和 丹尼斯·里奇（Dennis Ritchie） 出版了一本书，名叫《The C Programming Language》。这本书被 C语言开发者们称为K&R，很多年来被当作 C语言的非正式的标准说明。人们称这个版本的 C语言为K&R C。
- 1982年，很多有识之士和美国国家标准协会为了使这个语言健康地发展下去，决定成立C标准委员会，建立C语言的标准。委员会由硬件厂商，编译器及其他软件工具生产商，软件设计师，顾问，学术界人士，C语言作者和应用程序员组成。
- 1989年，ANSI发布了第一个完整的C语言标准——ANSI X3.159—1989，简称“C89”，不过人们也习惯称其为“ANSI C”。
- 1990年，国际标准化组织（ISO）和国际电工委员会（IEC）把C89标准定为C语言的国际标准，命名为`ISO/IEC 9899:1990 - Programming languages -- C`。因为此标准是在1990年发布的，所以有些人把简称作C90标准。不过大多数人依然称之为C89标准，因为此标准与ANSI C89标准完全等同。
- 1994年，国际标准化组织（ISO）和国际电工委员会（IEC）发布了C89标准修订版，名叫`ISO/IEC 9899:1990/Cor 1:1994` ，有些人简称为C94标准。
- 1995年，国际标准化组织（ISO）和国际电工委员会（IEC）再次发布了C89标准修订版，名叫`ISO/IEC 9899:1990/Amd 1:1995 - C Integrity `，有些人简称为C95标准。
- 1999年，国际标准化组织（ISO）和国际电工委员会（IEC）发布了C语言的新标准，名叫`ISO/IEC 9899:1999 - Programming languages -- C`，简称C99标准。这是C语言的第二个官方标准。
- 2011年，国际标准化组织（ISO）和国际电工委员会（IEC）再次发布了C语言的新标准，名叫`ISO/IEC 9899:2011 - Information technology -- Programming languages -- C` ，简称C11标准，原名C1X。这是C语言的第三个官方标准，也是C语言的最新标准。
- 2018年6月，C18标准，C语言编程的现行标准。它没有引入新的语言特性，只是对C11中的缺陷进行了技术修正和澄清。

标准： **C89**/ANSIC/C90 -- C94 -- C95 -- **C99** -- **C11** -C18

## C++语言的发展阶段

最初导致C++诞生的原因是在Bjarne博士等人试图去分析UNIX的内核的时候，这项工作开始于1979年4月，当时由于没有合适的工具能够有效的分析由于内核分布而造成的网络流量，以及怎样将内核模块化。
同年10月，Bjarne博士完成了一个可以运行的预处理程序，称之为Cpre，它为C加上了类似Simula的类机制。在这个过程中，Bjarne博士开始思考是不是要开发一种新的语言，当时贝尔实验室对这个想法很感兴趣，就让Bjarne博士等人组成一个开发小组，专门进行研究。

当时不是叫做C++，而是C with class，这是把它当作一种C语言的有效扩充。由于当时C语言在编程界居于老大的地位，要想发展一种新的语言，最强大的竞争对手就是C语言，所以当时有两个问题最受关注：C++要在运行时间、代码紧凑性和
数据紧凑性方面能够与C语言相媲美，但是还要尽量避免在语言应用领域的限制。在这种情况下，一个很自然的想法就是让C++从C语言继承过来，但是我们的Bjarne博士更具有先见之明，他为了避免受到C语言的局限性，参考了很多的语言，例如：从Simula继承了类的概念，从Algol68继承了运算符重载、引用以及在任何地方声明变量的能力

第一个带有类编译器的C被称为Cfront，它来自于名为CPre的C编译器。它是一个用类代码将C语言翻译成普通C语言的程序。值得注意的一点是Cfront大部分是用C语言编写的，这使得它成为了一个自托管编译器(一个可以自己编译的编译器)。Cfront后来在1993年被抛弃，因为很难将新的特性集成到其中，即c++异常。尽管如此，Cfront对未来编译器的实现和Unix操作系统产生了巨大的影响。

下面让我们来一起看一下C++历史上的主要事件：

- 1983年， Rick Mascitti建议C with class命名为CPlusPlus，即C++，第一个C++实现投入使用。大约在这个时候添加了许多新特性，其中最引人注目的是虚拟函数、函数重载、带&符号的引用、const关键字和使用两个前斜杠的单行注释(这是从BCPL语言中提取的特性)。
- 1985年2月， 第一个C++ Release E发布。10月，CFront的第一个商业发布：CFront Release 1.0。Bjarne博士完成了经典巨著The C++ Programming Language第一版。同年，c++作为商业产品实现，语言还没有正式标准化，这使得这本书成为一个非常重要的参考
- 1986年11月，C++第一个商业移植CFront 1.1,Glockenspiel。
- 1987年2月， CFront Release 1.2发布。11月，第一个USENIX C++会议在新墨西哥州举行。
- 1988年10月，第一次USENIX C++实现者工作会议在科罗拉多州举行。
- 1989年12月，ANSI X3J16在华盛顿组织会议。语言再次更新，包括受保护成员和静态成员，以及来自几个类的继承。
- 1990年3月， 第一次ANSI X3J16技术会议在新泽西州召开。5月， C++的又一个传世经典ARM诞生。7月， 模板被加入。11月，异常被加入。同年，Borland的Turbo c++编译器将作为商业产品发布。Turbo c++增加了大量的额外库，这将对c++的开发产生相当大的影响。虽然Turbo c++的最后一个稳定版本是在2006年，但是编译器仍然被广泛使用。
- 1991年6月， The C++ Programming Language第二版完成。第一次ISO WG21会议在瑞典召开。10月，CFront Release 3.0发布。
- 1993年3月， 运行时类型识别在俄勒冈州被加入。7月， 名字空间在德国慕尼黑被加入。
- 1994年8月， ANSI/ISO委员会草案登记。
- 1997年7月， The C++ Programming Language第三版完成。10月，ISO标准通过表决被接受
- 1998年，c++标准委员会发布了`c++ ISO/IEC 14882:1998`的第一个国际标准，也就是所谓的c++ 98。注释的c++参考手册据说对标准的开发有很大的影响。标准模板库从1979年开始概念开发，也包括在内。
- 2003年，委员会对1998年标准报告的多个问题作出了回应，并对其进行了相应的修订。更改后的语言被称为c++ 03。
- 2005年，c++标准委员会发布了一份技术报告(TR1)，详细描述了他们计划添加到最新的c++标准中的各种特性。新标准被非正式地称为c++ 0x，因为它预计将在第一个十年结束前的某个时候发布。然而，具有讽刺意味的是，新标准要到2011年年中才会发布。在此之前发布了一些技术报告，一些编译器开始为新特性添加实验支持。
- 2011年年中，新的c++标准(被称为c++ 11)完成。Boost库项目对新标准产生了相当大的影响，一些新模块直接来自相应的Boost库。一些新特性包括正则表达式支持(正则表达式的细节可以在这里找到),一个全面的随机化图书馆,一个新的c++库,原子的支持,一个标准的线程库(直到2011 C和c++都缺乏),一个新的循环语法提供功能类似于某些其他语言foreach循环,auto关键字,新的容器类,更好地支持union联合体和数组初始化列表,和可变模板。
- 2014年12月，C++ ISO/IEC标准的最新版本C++14。C++14是对C++11的小范围的扩展，主要内容是修复bug和略微提高性能。
- 2017年12月，ISO C++ 委员会正式发布了 C++ 17 标准，官方名称为 ISO/IEC 14882:2017。基于 C++ 14，C++ 17 旨在使 C++ 成为一个不那么臃肿复杂的编程语言，以简化该语言的日常使用，使开发者可以更简单地编写和维护代码。C++ 17 是对 C++ 语言的重大更新，引入了许多新的语言特性。
- 2019春季会议在夏威夷科纳举办，委员会在这次会议中确定了下一个国际标准 C++20 的全部特性，这标志着 C++20 的特性设计工作已完成。

标准： **C++98** -- C++03 -- **C++11** -- **C++14** -- **C++17** -- C++20

STL（Standard Template Library，标准模板库)是惠普实验室开发的一系列软件的统称。它是由Alexander Stepanov、Meng Lee和David R Musser在惠普实验室工作时所开发出来的。STL的代码从广义上讲分为三类：algorithm（算法）、container（容器）和iterator（迭代器），几乎所有的代码都采用了模板类和模版函数的方式，这相比于传统的由函数和类组成的库来说提供了更好的代码重用机会。

在C++标准中，STL被组织为下面的13个头文件：`<algorithm>、<deque>、<functional>、<iterator>、<vector>、<list>、<map>、<memory>、<numeric>、<queue>、<set>、<stack>和<utility>`。

[Boost](https://www.boost.org) 库通过加入一些在实践中非常有用的函数对 C++ 标准进行了补充。 由于 Boost C++ 库是基于 C++ 标准的，所以它们是使用最先进的 C++ 来实现的。 它们是平台独立的，并由于有一个大型的开发人员社区，它可以被包括 Windows 和 Linux 在内的许多操作系统所支持。 Boost库由C++标准委员会库工作组成员发起，其中有些内容有望成为下一代C++标准库内容。在C++社区中影响甚大，是不折不扣的“准”标准库。Boost由于其对跨平台的强调，对标准C++的强调，与编写平台无关。大部分boost库功能的使用只需包括相应头文件即可，少数（如正则表达式库，文件系统库等）需要链接库。可以说，Boost库是为C++语言标准库提供扩展的一些C++程序库的总称。C++11, C++14很多特性都是从boost库来的，如果所在的公司使用的编译器可以支持C++11或以上那么可以先用标准的来就行，不够再去翻翻boost。


# 正文

编译程序需要使用各种参数，所以很麻烦，出现了不同的make构建工具，这些工具遵循不同的规范和标准，所执行的Makefile格式也不同，但如果想让软件跨平台，必须要保证能够在不同平台编译，但使用这些make工具就得为每一种标准写一次Makefile，因此CMake应运而生。CMake首先允许开发者编写一种与平台无关的CMakeList.txt来定制整个编译流程，然后再根据目标用户的平台进一步生成所需的本地化Makefile和工程文件，如Unix的Makefile或Windows的Visual Studio。

## 程序编译

一般程序写完后需要编译成二进制机器码，然后再调用执行。

下面是一个本人工作中遇到的经典编译：

```sh
gcc read.c -o read.exe -g -Wall "common/common.c" "common/ss_help.c" "lib/base64/base64.c" "lib/cJSON/cJSON.c" \
-I"../include" -I"./common" -I"./lib" -I"./lib/base64" -I"./lib/cJSON"  \
-lslm_runtime -lslm_control -lss_user_login  -lm -ldl -lpthread \
-L"./" -L"./../lib64" \
-Wl,-rpath="./" -Wl,-rpath="./../lib64"
```

具体参数解释如下：

```
gcc     编译工具
read.c  主函数文件
-o read.exe     编译成read.exe二进制
-g              可以使用gdb调试
-Wall           生成所有警告信息
"common/common.c" "common/ss_help.c" "lib/base64/base64.c" "lib/cJSON/cJSON.c"  一起编译的其他C源文件
-I"../include" -I"./common" -I"./lib" -I"./lib/base64" -I"./lib/cJSON"          依赖的头文件所在目录
-lslm_runtime -lslm_control -lss_user_login  -lm -ldl -lpthread                 链接的动态库 libslm_runtime等，可用ldd read.exe查看
-L"./" -L"./../lib64"   放在/lib和/usr/lib和/usr/local/lib里的库直接用-l参数就能链接，否则要加上库文件所在的目录名
-Wl,-rpath=./           编译时指定的 -L  的目录，只是在程序链接成可执行文件时使用的。程序执行时动态链接库加载不到动态链接库，所以要加上。或者加上环境变量也可以：export LD_LIBRARY_PATH
```

是有点麻烦，因此使用构建工具很有必要。

## Cmake

参考: [Cmake](https://www.hahack.com/codes/cmake)，以下所有例子都是转载的网络并自己实验一遍的。

你或许听过好几种 Make 工具，例如 GNU Make ，QT 的 qmake ，微软的 MS nmake，BSD Make（pmake），Makepp，等等。这些 Make 工具遵循着不同的规范和标准，所执行的 Makefile 格式也千差万别。这样就带来了一个严峻的问题：如果软件想跨平台，必须要保证能够在不同平台编译。而如果使用上面的 Make 工具，就得为每一种标准写一次 Makefile ，这将是一件让人抓狂的工作。

CMake就是针对上面问题所设计的工具：它首先允许开发者编写一种平台无关的 CMakeList.txt 文件来定制整个编译流程，然后再根据目标用户的平台进一步生成所需的本地化 Makefile 和工程文件，如 Unix 的 Makefile 或 Windows 的 Visual Studio 工程。从而做到“Write once, run everywhere”。显然，CMake 是一个比上述几种 make 更高级的编译配置工具。一些使用 CMake 作为项目架构系统的知名开源项目有 VTK、ITK、KDE、OpenCV、OSG 等。

在 linux 平台下使用 CMake 生成 Makefile 并编译的流程如下：

1. 编写 CMake 配置文件 CMakeLists.txt 。
2. 执行命令 cmake PATH 或者 ccmake PATH 生成 Makefile。ccmake 和 cmake 的区别在于前者提供了一个交互式的界面。其中， PATH 是 CMakeLists.txt 所在的目录。
3. 使用 make 命令进行编译。

Debian/Ubuntu等系列apt套件安装：

```
sudo apt install cmake
cmake --version
```

### 单个源文件

可以进入查看:

```
cd Demo1
```

main.c:

```
#include <stdio.h>
#include <stdlib.h>
/**
 * power - Calculate the power of number.
 * @param base: Base value.
 * @param exponent: Exponent value.
 *
 * @return base raised to the power exponent.
 */
double power(double base, int exponent)
{
    int result = base;
    int i;

    if (exponent == 0) {
        return 1;
    }

    for(i = 1; i < exponent; ++i){
        result = result * base;
    }
    return result;
}
int main(int argc, char *argv[])
{
    if (argc < 3){
        printf("Usage: %s base exponent \n", argv[0]);
        return 1;
    }
    double base = atof(argv[1]);
    int exponent = atoi(argv[2]);
    double result = power(base, exponent);
    printf("%g ^ %d is %g\n", base, exponent, result);
    return 0;
}
```

CMakeLists.txt:

```
# CMake 最低版本号要求
cmake_minimum_required (VERSION 2.8)
# 项目信息
project (Demo1)
# 指定生成目标
add_executable(main main.c)
```

上面的 CMakeLists.txt 文件，依次出现了几个命令：

1. cmake_minimum_required：指定运行此配置文件所需的 CMake 的最低版本；
2. project：参数值是 Demo1，该命令表示项目的名称是 Demo1 。
3. add_executable： 将名为 main.c 的源文件编译成一个名称为 main 的可执行文件。


执行：

```
cmake .
make
./main 2 3
```