# how-to-optimize-gemm
ColMajor gemm optimization

考虑到移动端卷积优化一般使用`arm`架构芯片，
因此基于 [blis-lab](https://github.com/flame/blislab) 文档实现`arm64`版行主序`gemm`优化。
原文为列主序`x86 SSE`代码。

本系列优化教程在[简书文档](https://www.jianshu.com/p/26f24f464016)