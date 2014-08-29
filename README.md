##ObjC Data Tyep Size
确定32位和64位下各数据类型占用的字节大小。

###32位下的情形
示例程序:

    NSLog(@"32 bit 下 sizeof(char) = %lu 个字节", sizeof(char));
    NSLog(@"32 bit 下 sizeof(unsigned char) = %lu 个字节", sizeof(unsigned char));
    NSLog(@"32 bit 下 sizeof(short) = %lu 个字节", sizeof(short));
    NSLog(@"32 bit 下 sizeof(unsigned short) = %lu 个字节", sizeof(unsigned short));
    NSLog(@"32 bit 下 sizeof(int) = %lu 个字节", sizeof(int));
    NSLog(@"32 bit 下 sizeof(unsigned int) = %lu 个字节", sizeof(unsigned int));
    NSLog(@"32 bit 下 sizeof(long) = %lu 个字节", sizeof(long));
    NSLog(@"32 bit 下 sizeof(unsigned long) = %lu 个字节", sizeof(unsigned long));
    NSLog(@"32 bit 下 sizeof(long long) = %lu 个字节", sizeof(long long));
    NSLog(@"32 bit 下 sizeof(unsigned long long) = %lu 个字节", sizeof(unsigned long long));
    NSLog(@"32 bit 下 sizeof(BOOL) = %lu 个字节", sizeof(BOOL));
    NSLog(@"32 bit 下 sizeof(bool) = %lu 个字节", sizeof(bool));
    NSLog(@"32 bit 下 sizeof(float) = %lu 个字节", sizeof(float));
    NSLog(@"32 bit 下 sizeof(double) = %lu 个字节", sizeof(double));
    NSLog(@"32 bit 下 sizeof(int8_t) = %lu 个字节", sizeof(int8_t));
    NSLog(@"32 bit 下 sizeof(int16_t) = %lu 个字节", sizeof(int16_t));
    NSLog(@"32 bit 下 sizeof(int32_t) = %lu 个字节", sizeof(int32_t));
    NSLog(@"32 bit 下 sizeof(int64_t) = %lu 个字节", sizeof(int64_t));
    NSLog(@"32 bit 下 sizeof(uint8_t) = %lu 个字节", sizeof(uint8_t));
    NSLog(@"32 bit 下 sizeof(uint16_t) = %lu 个字节", sizeof(uint16_t));
    NSLog(@"32 bit 下 sizeof(uint32_t) = %lu 个字节", sizeof(uint32_t));
    NSLog(@"32 bit 下 sizeof(uint64_t) = %lu 个字节", sizeof(uint64_t));
    

对应输出:

	32 bit 下 sizeof(char) = 1 个字节
	32 bit 下 sizeof(unsigned char) = 1 个字节
	32 bit 下 sizeof(short) = 2 个字节
	32 bit 下 sizeof(unsigned short) = 2 个字节
	32 bit 下 sizeof(int) = 4 个字节
	32 bit 下 sizeof(unsigned int) = 4 个字节
	32 bit 下 sizeof(long) = 4 个字节
	32 bit 下 sizeof(unsigned long) = 4 个字节
	32 bit 下 sizeof(long long) = 8 个字节 
	32 bit 下 sizeof(unsigned long long) = 8 个字节
	32 bit 下 sizeof(BOOL) = 1 个字节
	32 bit 下 sizeof(bool) = 1 个字节
	32 bit 下 sizeof(float) = 4 个字节
	32 bit 下 sizeof(double) = 8 个字节 
	32 bit 下 sizeof(int8_t) = 1 个字节
	32 bit 下 sizeof(int16_t) = 2 个字节
	32 bit 下 sizeof(int32_t) = 4 个字节
	32 bit 下 sizeof(int64_t) = 8 个字节
	32 bit 下 sizeof(uint8_t) = 1 个字节
	32 bit 下 sizeof(uint16_t) = 2 个字节
	32 bit 下 sizeof(uint32_t) = 4 个字节
	32 bit 下 sizeof(uint64_t) = 8 个字节
	
	
###64位下的情形

示例程序:

    NSLog(@"64 bit 下 sizeof(char) = %lu 个字节", sizeof(char));
    NSLog(@"64 bit 下 sizeof(unsigned char) = %lu 个字节", sizeof(unsigned char));
    NSLog(@"64 bit 下 sizeof(short) = %lu 个字节", sizeof(short));
    NSLog(@"64 bit 下 sizeof(unsigned short) = %lu 个字节", sizeof(unsigned short));
    NSLog(@"64 bit 下 sizeof(int) = %lu 个字节", sizeof(int));
    NSLog(@"64 bit 下 sizeof(unsigned int) = %lu 个字节", sizeof(unsigned int));
    NSLog(@"64 bit 下 sizeof(long) = %lu 个字节", sizeof(long));
    NSLog(@"64 bit 下 sizeof(unsigned long) = %lu 个字节", sizeof(unsigned long));
    NSLog(@"64 bit 下 sizeof(long long) = %lu 个字节", sizeof(long long));
    NSLog(@"64 bit 下 sizeof(unsigned long long) = %lu 个字节", sizeof(unsigned long long));
    NSLog(@"64 bit 下 sizeof(BOOL) = %lu 个字节", sizeof(BOOL));
    NSLog(@"64 bit 下 sizeof(bool) = %lu 个字节", sizeof(bool));
    NSLog(@"64 bit 下 sizeof(float) = %lu 个字节", sizeof(float));
    NSLog(@"64 bit 下 sizeof(double) = %lu 个字节", sizeof(double));
    NSLog(@"64 bit 下 sizeof(int8_t) = %lu 个字节", sizeof(int8_t));
    NSLog(@"64 bit 下 sizeof(int16_t) = %lu 个字节", sizeof(int16_t));
    NSLog(@"64 bit 下 sizeof(int32_t) = %lu 个字节", sizeof(int32_t));
    NSLog(@"64 bit 下 sizeof(int64_t) = %lu 个字节", sizeof(int64_t));
    NSLog(@"64 bit 下 sizeof(uint8_t) = %lu 个字节", sizeof(uint8_t));
    NSLog(@"64 bit 下 sizeof(uint16_t) = %lu 个字节", sizeof(uint16_t));
    NSLog(@"64 bit 下 sizeof(uint32_t) = %lu 个字节", sizeof(uint32_t));
    NSLog(@"64 bit 下 sizeof(uint64_t) = %lu 个字节", sizeof(uint64_t));
    
    
对应输出:

    64 bit 下 sizeof(char) = 1 个字节
    64 bit 下 sizeof(unsigned char) = 1 个字节
    64 bit 下 sizeof(short) = 2 个字节
    64 bit 下 sizeof(unsigned short) = 2 个字节
    64 bit 下 sizeof(int) = 4 个字节
    64 bit 下 sizeof(unsigned int) = 4 个字节
    64 bit 下 sizeof(long) = 8 个字节
    64 bit 下 sizeof(unsigned long) = 8 个字节
    64 bit 下 sizeof(long long) = 8 个字节
    64 bit 下 sizeof(unsigned long long) = 8 个字节
    64 bit 下 sizeof(BOOL) = 1 个字节
    64 bit 下 sizeof(bool) = 1 个字节
    64 bit 下 sizeof(float) = 4 个字节
    64 bit 下 sizeof(double) = 8 个字节
    64 bit 下 sizeof(int8_t) = 1 个字节
    64 bit 下 sizeof(int16_t) = 2 个字节
    64 bit 下 sizeof(int32_t) = 4 个字节
    64 bit 下 sizeof(int64_t) = 8 个字节
    64 bit 下 sizeof(uint8_t) = 1 个字节
    64 bit 下 sizeof(uint16_t) = 2 个字节
    64 bit 下 sizeof(uint32_t) = 4 个字节
    64 bit 下 sizeof(uint64_t) = 8 个字节

##总结
32 位与 64 位数据类型的主要区别是 `long`。在 32 位下 `long` 占 4 个字节，而在 64 位下 `long` 为 8 个字节。
建议：在进行较底层 iOS 程序开发的时候，建议使用与平台无关的显示的确定的数据类型。即 `int8_t`、`int16_t`、`int32_t`、`int64_t`、`uint8_t`、`uint16_t`、`uint32_t`、`uint64_t`。
