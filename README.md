# COD

##### Hello, World!

```C
#import "std/io.cd"

i32 main(i32 argc, char* argv) {
    io::printf("Hello, World!\n");
}
```

##### Comparison

```C
/******************** C ********************/
typedef struct {int a; int b;} SomeStruct;
typedef enum {
   SOME_A = 0, SOME_B, SOME_C
} SomeEnum;

SomeStruct somestruct_new(int a, int b) {
    return (SomeStruct){a, b};
}

void somestruct_do_stuff(SomeStruct* ptr) {
    ptr->a += ptr->b;
}

/******************** Cod ********************/
struct SomeStruct {
    i32 a, b;
}
enum SomeEnum {
    A = 0, B, C
}

for SomeStruct {
    Self new(i32 a, i32 b) {
        return Self {a, b};
    }
    void do_stuff(*self) {
         self.a += self.b;
    }
}


```
