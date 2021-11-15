# Deadlock and Optimizations

Explain your optimizations if applicable

#Freeing code
Modified solve() function in ai.c to free sokoban struct in line 337
Modified find_solution() function in ai.c to free pq in line 303
Modified free_memory() function in ai.c to free expanded_nodes_table in line 146
