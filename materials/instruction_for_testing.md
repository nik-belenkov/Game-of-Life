#*** How to check with cppcheck ***

# Install cppcheck (Ubuntu)
  sudo apt install cppcheck

# Check pong.cpp, enable all checks:
  cppcheck --enable=all --suppress=missingIncludeSystem main.cpp

# Check all files in directory, enable all checks:
  cppcheck --enable=all --suppress=missingIncludeSystem src/


#*** How to check with clang-format ***

# Install cppcheck (Ubuntu)
  sudo apt install clang-format

## Instruction

1. Copy clang-format from materials/lintres/ into src.
2. In srs/ run command: "clang-format -n main.cpp" for checking on code style.
3. In srs/ run command: "clang-format -i main.cpp" for fixing problems.
