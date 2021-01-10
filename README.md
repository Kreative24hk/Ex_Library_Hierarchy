# Ex_Library_Hierarchy

This library is for showing how packages are constructed in Python. You can download and save this pacakge into the python site-package folder. And then, check the package's structure by using the sample code below.

## Check the MyMethod_1() in MyModule_1

<pre>
<code>
from Ex_Library_Hierarchy import MyModule_1

MyModule_1.MyMethod_1()
</code>
</pre>

### Expected output
```
__init__.py inside the PACKAGE:Ex_Library_Hierarchy is executed ...
This is MyMethod_1 in MyModule_1.py
```

## Check the MyMethod_2() in MyClass_1 of MyModule_1

```
from Ex_Library_Hierarchy import MyModule_1

object_1 = MyModule_1.MyClass_1()
object_1.MyMethod_2()
```

### Expected output
```
__init__.py inside the PACKAGE:Ex_Library_Hierarchy is executed ...
This is MyMethod_2 in MyClass_1 of MyModule_1.py
```

## Check the MyVariable_1 and _2 in MyClass_1 of MyModule_1
```
from Ex_Library_Hierarchy import MyModule_1

object_1 = MyModule_1.MyClass_1()

print (object_1.MyVariable_1)
print (object_1.MyVariable_2)
```

### Expected output
```
__init__.py inside the PACKAGE:Ex_Library_Hierarchy is executed ...
This is MyVariable_1 in MyClass_1 of MyModule_1.py
This is MyVariable_2 in MyClass_1 of MyModule_1.py
```


- - -
[Description Korean Version] (https://kreative24hk.tistory.com/69)
