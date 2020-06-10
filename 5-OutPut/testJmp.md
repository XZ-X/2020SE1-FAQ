# Lab05 - testJmp

> Normal console output
>
> You can make your own output by using Typora. 
>
> Powered by YDJSIR, 2020



## After ICONST_N exec:
    Methods in current thread:
    JmpTest : main
    
    Contents in operand stack:
    value = 0
    
    Contents in local var:

### Next frame doesn't change.Method is still JmpTest : main
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    JmpTest : main
    
    Contents in operand stack:
    value = 0
    value = 0
    
    Contents in local var:

### Next frame doesn't change.Method is still JmpTest : main
----------------------------------------------------------------------
## After ICONST_N exec:
    Methods in current thread:
    JmpTest : main
    
    Contents in operand stack:
    value = 0
    value = 0
    value = 1
    
    Contents in local var:

### Next frame doesn't change.Method is still JmpTest : main
----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    JmpTest : main
    java/lang/Object : <clinit>
    
    Contents in operand stack:
    value = 0
    value = 0
    value = 1
    
    Contents in local var:

### Next frame changed.Method is java/lang/Object : \<clinit>

----------------------------------------------------------------------
## After INVOKE_STATIC exec:

    Methods in current thread:
    JmpTest : main
    java/lang/Object : <clinit>
    
    Contents in operand stack:
    
    Contents in local var:

### Next frame doesn't change.Method is still java/lang/Object : \<clinit>

----------------------------------------------------------------------
## After RETURN exec:
    Methods in current thread:
    JmpTest : main
    
    Contents in operand stack:
    
    Contents in local var:

### Next frame changed.Method is JmpTest : main

----------------------------------------------------------------------
## After INVOKE_STATIC exec:
    Methods in current thread:
    JmpTest : main
    JmpTest : testJmp
    
    Contents in operand stack:
    
    Contents in local var:

### Next frame changed.Method is JmpTest : testJmp
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    JmpTest : main
    JmpTest : testJmp
    
    Contents in operand stack:
    value = 0
    
    Contents in local var:
    value = 0
    value = 0
    value = 1

### Next frame doesn't change.Method is still JmpTest : testJmp
----------------------------------------------------------------------
## After IFEQ exec:
    Methods in current thread:
    JmpTest : main
    JmpTest : testJmp
    
    Contents in operand stack:
    
    Contents in local var:
    value = 0
    value = 0
    value = 1

### Next frame doesn't change.Method is still JmpTest : testJmp
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    JmpTest : main
    JmpTest : testJmp
    
    Contents in operand stack:
    value = 0
    
    Contents in local var:
    value = 0
    value = 0
    value = 1

### Next frame doesn't change.Method is still JmpTest : testJmp
----------------------------------------------------------------------
## After IFNE exec:
    Methods in current thread:
    JmpTest : main
    JmpTest : testJmp
    
    Contents in operand stack:
    
    Contents in local var:
    value = 0
    value = 0
    value = 1

### Next frame doesn't change.Method is still JmpTest : testJmp
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    JmpTest : main
    JmpTest : testJmp
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 0
    value = 0
    value = 1

### Next frame doesn't change.Method is still JmpTest : testJmp
----------------------------------------------------------------------
## After IFEQ exec:
    Methods in current thread:
    JmpTest : main
    JmpTest : testJmp
    
    Contents in operand stack:
    
    Contents in local var:
    value = 0
    value = 0
    value = 1

### Next frame doesn't change.Method is still JmpTest : testJmp
----------------------------------------------------------------------
## After ILOAD_N exec:
    Methods in current thread:
    JmpTest : main
    JmpTest : testJmp
    
    Contents in operand stack:
    value = 1
    
    Contents in local var:
    value = 0
    value = 0
    value = 1

### Next frame doesn't change.Method is still JmpTest : testJmp
----------------------------------------------------------------------
## After IFEQ exec:
    Methods in current thread:
    JmpTest : main
    JmpTest : testJmp
    
    Contents in operand stack:
    
    Contents in local var:
    value = 0
    value = 0
    value = 1

### Next frame doesn't change.Method is still JmpTest : testJmp
----------------------------------------------------------------------
## After GOTO exec:
    Methods in current thread:
    JmpTest : main
    JmpTest : testJmp
    
    Contents in operand stack:
    
    Contents in local var:
    value = 0
    value = 0
    value = 1

### Next frame doesn't change.Method is still JmpTest : testJmp
----------------------------------------------------------------------
## After RETURN exec:
    Methods in current thread:
    JmpTest : main
    
    Contents in operand stack:
    
    Contents in local var:
    value = 0
    value = 0
    value = 1

### Next frame changed.Method is JmpTest : main
----------------------------------------------------------------------



# Process finished with exit code 0