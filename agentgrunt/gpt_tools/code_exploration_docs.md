# Code Exploration Tools

- bfs_find(base, pattern): Finds filenames matching a pattern using breadth-first search. Use to locate specific files in a directory structure.
- grep(file_path, pattern, recursive): Searches for a pattern in a file or directory (optionally recursively). Use to locate specific content within files. Use this as a last resort, instead preferng the provided git binary's `git grep` feature
- tree(directory, prefix, depth_remaining): Prints a directory tree. Use to visualize directory structures.
- find_function_signatures(file_path, language): Finds function signatures in a file. Use for code analysis.
- extract_function(file_path, signature, language): Extracts the code of a function using its signature. Use to work on specific functions.
