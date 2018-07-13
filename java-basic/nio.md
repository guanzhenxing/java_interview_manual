# NIO

## IO操作最佳实践

- 使用有缓冲的IO类,不要单独读取字节或字符
- 使用NIO和NIO 2或者AIO,而非BIO
- 在finally中关闭流
- 使用内存映射文件获取更快的IO

