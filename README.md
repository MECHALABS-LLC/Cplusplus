The C++ language has two main components: a direct mapping of hardware features provided primarily by the C subset, and zero-overhead abstractions based on those mappings. 
Stroustrup describes C++ as "a light-weight abstraction programming language [designed] for building and using efficient and elegant abstractions";
and "offering both hardware access and abstraction is the basis of C++. Doing it efficiently is what distinguishes it from other languages."

C++ inherits most of C's syntax. A hello world program that conforms to the C standard is also a valid C++ hello world program. 
The following is Bjarne Stroustrup's version of the Hello world program that uses the C++ Standard Library stream facility to write a message to standard output:

#include <iostream>
int main()
{
    std::cout << "Hello, world!\n";
}
Object storage
As in C, C++ supports four types of memory management: static storage duration objects, thread storage duration objects, automatic storage duration objects, and dynamic storage duration objects.
