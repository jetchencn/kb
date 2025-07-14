https://mp.weixin.qq.com/s/F5HvtNdLLakTfqTgoTFIWw?clicktime=1752223333&enterid=1752223333&scene=90&subscene=236&xtrack=1

Unix是一个非常牛逼的操作系统。它的“子孙后代”无处不在，包括Linux、macOS，以及BSD家族。我特别喜欢它的三条设计哲学：
第一，一切皆文件（**Everything is a file**）。在Unix里边，无论是硬件设备、进程、还是网络连接，都可以被抽象成文件。然后你就可以用同一套简单的操作，比如open、read、write，来进行统一的交互。
第二，做一件事，并把它做好（**Do One Thing and Do It Well）**。程序应该保持简单，专注于一个核心功能。于是，命令就是程序；一条命令就专注干好一件事。
第三，也是最关键的一条——程序之间相互协作（**Write programs to work together**）。这条哲学要求，每个程序的输出都应该能成为另一个程序的输入。这就诞生了Unix历史上最伟大的发明之一：管道，就是这根神奇的竖线 |。它能像水管一样把一个命令的输出直接连接到下一个命令的输入。