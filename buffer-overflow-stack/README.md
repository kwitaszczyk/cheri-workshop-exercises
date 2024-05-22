1. Compile the program for the hybrid ABI

2. Compile the program for CheriABI

   Consider adding `-g` for debug symbols.

3. Run the program for both ABIs

4. For the CheriABI program:

   * Enter CHERI GDB with a core dump

   * Analyse what instruction failed and why

   * Read the code and try to fix the issue
