# Lab05 - testJmp

> Normal console output
>
> You can make your own output by using Typora. 
>
> Powered by YDJSIR, 2020



## After LDC exec:

    Methods in current thread:
    ConversionTest : main
    
    Contents in operand stack:
    value = 1082088489
    
    Contents in local var:

### Next frame doesn't change.Method is still ConversionTest : main
----------------------------------------------------------------------
## After LDC2_W exec:
    Methods in current thread:
    ConversionTest : main
    
    Contents in operand stack:
    value = 1082088489
    value = 515396076
    value = 1074785157
    
    Contents in local var:

### Next frame doesn't change.Method is still ConversionTest : main
----------------------------------------------------------------------
## After LDC2_W exec:
    Methods in current thread:
    ConversionTest : main
    
    Contents in operand stack:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    
    Contents in local var:

### Next frame doesn't change.Method is still ConversionTest : main
----------------------------------------------------------------------
## After LDC exec:
    Methods in current thread:
    ConversionTest : main
    
    Contents in operand stack:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    
    Contents in local var:

### Next frame doesn't change.Method is still ConversionTest : main
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    java/lang/Object : <clinit>
    
    Contents in operand stack:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    
    Contents in local var:

### Next frame changed.Method is java/lang/Object : \<clinit>

----------------------------------------------------------------------
## After INVOKE_STATIC exec:

    Methods in current thread:
    ConversionTest : main
    java/lang/Object : <clinit>
    
    Contents in operand stack:
    
    Contents in local var:

### Next frame doesn't change.Method is still java/lang/Object : \<clinit>

----------------------------------------------------------------------
## After RETURN exec:
    Methods in current thread:
    ConversionTest : main
    
    Contents in operand stack:
    
    Contents in local var:

### Next frame changed.Method is ConversionTest : main

----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After DLOAD_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 515396076
    value = 1074785157
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After D2F exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 1082088489
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After FSTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After FLOAD_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 1082088489
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After FSTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After FLOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 1082088489
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After FLOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 1082088489
    value = 1082088489
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 1082088489
    value = 1082088489
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalFloat
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489

### Next frame changed.Method is TestUtil : equalFloat
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalFloat
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 1082088489
    value = 1082088489

### Next frame doesn't change.Method is still TestUtil : equalFloat
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 1082088489

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After DLOAD_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 515396076
    value = 1074785157
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After D2I exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 3
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ISTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After FLOAD_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 1082088489
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After F2I exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 3
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ISTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 3
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 3
    value = 3
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 3
    value = 3

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 3
    value = 3

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 3
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 3
    value = 3
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 3
    value = 3

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 3
    value = 3

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After DLOAD_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 0
    value = 1105199104
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After D2I exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 2147483647
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ISTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 2147483647
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LDC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 2147483647
    value = 2147483647
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 2147483647
    value = 2147483647

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 2147483647
    value = 2147483647

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After DLOAD_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 0
    value = 1105199104
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After D2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -2147483648
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LSTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LLOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -2147483648
    value = -1
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LDC2_W exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -2147483648
    value = -1
    value = -2147483648
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LCMP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After IFEQ exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 2147483647
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After FLOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 2147483647
    value = 1325400064
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After F2I exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 2147483647
    value = 2147483647
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After IF_ICMPEQ exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LLOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -2147483648
    value = -1
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After FLOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -2147483648
    value = -1
    value = 1325400064
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After F2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -2147483648
    value = -1
    value = -2147483648
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LCMP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After IFEQ exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 3
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 3
    value = 3
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 3
    value = 3

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 3
    value = 3

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After IFEQ exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After SIPUSH exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ISTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After GOTO exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2B exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ISTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After BIPUSH exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -128
    value = -128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = -128
    value = -128

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = -128
    value = -128

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2C exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ISTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After SIPUSH exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 128
    value = 128

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 128
    value = 128

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2D exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 0
    value = 1080033280
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After DCONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 0
    value = 1080033280
    value = 0
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After DADD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 0
    value = 1080033280
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After D2I exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 128
    value = 128

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 128
    value = 128

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    value = 128
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LADD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 256
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 256
    value = 0
    value = -128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 256
    value = 0
    value = -128
    value = -1
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LADD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After L2I exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 128
    value = 128

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 128
    value = 128

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    value = 128
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LADD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 256
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 256
    value = 0
    value = -128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 256
    value = 0
    value = -128
    value = -1
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LADD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After L2D exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 0
    value = 1080033280
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After DCONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 0
    value = 1080033280
    value = 0
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After DADD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 0
    value = 1080033280
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After D2I exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 128
    value = 128

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 128
    value = 128

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    value = 128
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LADD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 256
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 256
    value = 0
    value = -128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2L exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 256
    value = 0
    value = -128
    value = -1
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After LADD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After L2F exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 1124073472
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After FCONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 1124073472
    value = 0
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After FADD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 1124073472
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After F2I exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 128
    value = 128

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 128
    value = 128

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After BIPUSH exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 128
    value = 8
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ISHL exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 32768
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 128
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ISTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 32768
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = 32768
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 32768
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After I2S exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -32768
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 32768
    value = -128
    value = 128

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ISTORE exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 32768
    value = -128
    value = 128
    value = -32768

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -32768
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 32768
    value = -128
    value = 128
    value = -32768

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After ILOAD exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -32768
    value = 32768
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 32768
    value = -128
    value = 128
    value = -32768

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INEG exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    value = -32768
    value = -32768
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 32768
    value = -128
    value = 128
    value = -32768

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 32768
    value = -128
    value = 128
    value = -32768

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = -32768
    value = -32768

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = -32768
    value = -32768

### Next frame changed.Method is ConversionTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    ConversionTest : main
    ConversionTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 32768
    value = -128
    value = 128
    value = -32768

### Next frame doesn't change.Method is still ConversionTest : test
----------------------------------------------------------------------
## After RETURN exec:
    Methods in current thread:
    ConversionTest : main
    
    Contents in operand stack:
    
    Contents in local var:
    value = 1082088489
    value = 515396076
    value = 1074785157
    value = 0
    value = 1105199104
    value = 1325400064
    value = 1082088489
    value = 1082088489
    value = 3
    value = 3
    value = 2147483647
    value = -2147483648
    value = -1
    value = 32768
    value = -128
    value = 128
    value = -32768

### Next frame changed.Method is ConversionTest : main
----------------------------------------------------------------------



# Process finished with exit code 0