# GFUZZ based on AFL++ 4.05c

```
  ./afl-fuzz -i $seeds -o $output -J $program -k $generator_base_path -- ./$target_program
```