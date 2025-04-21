**Exception** : It is an event that occurs during the execution of the program. It will disrupt your program normal flow. It creates the Exception object which contain the information about the Error like its type of Exception, Message and Stack Trace. Runtime system will use this Exception Object and find the class which can handle the exception.

In Java, exceptions are part of the Throwable class hierarchy. Here's an overview of the exception hierarchy:

1. **Throwable**
The root class for all exceptions and errors in Java is Throwable. It has two main subclasses:
  - Exception
  - Error
    
2. **Exception**
The Exception class is used for conditions that an application might want to catch. It has two main categories:
  - Checked Exceptions: Must be declared in the method signature using throws or handled with a try-catch block.
  - Unchecked Exceptions: These are the exceptions which occurs during runtime and compiler not forcing us to handle them. Do not need to be declared or caught.

  - 
Common Subclasses of Exception:
**Checked Exceptions:**
  - IOException
  - FileNotFoundException
  - SQLException
  - ClassNotFoundException
  - InterruptedException
    
**Unchecked Exceptions (RuntimeException):**
   - NullPointerException
   - ArrayIndexOutOfBoundsException
   - IllegalArgumentException
   - ArithmeticException
     
3. **Error**
The Error class represents serious problems that applications should not try to catch. These are typically issues with the JVM or system resources.

Common Subclasses of Error:
