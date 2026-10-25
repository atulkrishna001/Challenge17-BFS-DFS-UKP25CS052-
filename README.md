# Challenge 17-B09: File System Representation and Search Using BFS and DFS

## Aim
Represent a file system as a graph using an adjacency matrix and search it using BFS and DFS.

## Files
- `main.c` — C program
- `sample_input.txt` — sample input
- `sample_output.txt` — expected traversal/result (input prompts are omitted)

## How to run
Compile with a C compiler, for example:
`gcc main.c -o main`
Then run:
`./main`

Enter node names as single words (for example, `notes.txt`). Connections are treated as undirected edges.

## Sample result
BFS traversal: Root Documents Pictures Projects notes.txt photo.jpg
BFS result: File found
DFS traversal: Root Documents notes.txt Pictures photo.jpg Projects
DFS result: File found
