QUESTION 1-BFS

START

Create graph
visited = empty list
queue = [1]

WHILE queue is not empty:
    node = remove first element from queue

    IF node is not in visited:
        PRINT node
        Add node to visited

        FOR each neighbour of node:
            IF neighbour is not in visited:
                Add neighbour to queue

STOP



