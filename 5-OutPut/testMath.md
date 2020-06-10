# Lab05 - testMath

> Normal console output
>
> You can make your own output by using Typora. 
>
> Powered by YDJSIR, 2020



## After BIPUSH exec:
    Methods in current thread:
    MathTest : main
    
    Contents in operand stack:
    value = 6
    
    Contents in local var:

### Next frame doesn't change.Method is still MathTest : main
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    MathTest : main
    
    Contents in operand stack:
    value = 6
    value = 5
    
    Contents in local var:

### Next frame doesn't change.Method is still MathTest : main
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    MathTest : main
    java/lang/Object : <clinit>
    
    Contents in operand stack:
    value = 6
    value = 5
    
    Contents in local var:

### Next frame changed.Method is java/lang/Object : \<clinit>
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    MathTest : main
    java/lang/Object : <clinit>
    
    Contents in operand stack:
    
    Contents in local var:

### Next frame doesn't change.Method is still java/lang/Object : \<clinit>

----------------------------------------------------------------------
## After RETURN exec:
    Methods in current thread:
    MathTest : main
    
    Contents in operand stack:
    
    Contents in local var:

### Next frame changed.Method is MathTest : main
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:

### Next frame changed.Method is MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    
    Contents in local var:
    value = 6
    value = 5

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    value = 5
    
    Contents in local var:
    value = 6
    value = 5

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After IADD exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 11
    
    Contents in local var:
    value = 6
    value = 5

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ISTORE_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 11
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After BIPUSH exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 11
    value = 11
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After IF_ICMPNE exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    value = 5
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ISUB exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 1
    value = 1
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After IF_ICMPNE exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    value = 5
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After IMUL exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 30
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After BIPUSH exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 30
    value = 30
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After IF_ICMPNE exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    value = 5
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After IDIV exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 1
    value = 1
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After IF_ICMPNE exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After BIPUSH exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    value = 6
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 6
    value = 6
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 6
    value = 6

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 6

### Next frame changed.Method is MathTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 5
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    value = 5
    value = 5
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame changed.Method is TestUtil : equalInt
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    TestUtil : equalInt
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 5
    value = 5

### Next frame doesn't change.Method is still TestUtil : equalInt
----------------------------------------------------------------------
## After IRETURN exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 5
    value = 5

### Next frame changed.Method is MathTest : test
----------------------------------------------------------------------
## After POP exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After GOTO exec:
    Methods in current thread:
    MathTest : main
    MathTest : test
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame doesn't change.Method is still MathTest : test
----------------------------------------------------------------------
## After RETURN exec:
    Methods in current thread:
    MathTest : main
    
    Contents in operand stack:
    
    Contents in local var:
    value = 6
    value = 5
    value = 11

### Next frame changed.Method is MathTest : main
----------------------------------------------------------------------



# Process finished with exit code 0