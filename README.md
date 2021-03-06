# binary_trees
A binary tree is a tree data structure in which each node has at most two children, which are referred to as the left child and the right child.

This topic's aim was also to understand the following concepts:-

* What is a binary tree
* What is the difference between a binary tree and a Binary Search Tree
* What is the possible gain in terms of time complexity compared to linked lists
* What are the depth, the height, the size of a binary tree
* What are the different traversal methods to go through a binary tree
* What is a complete, a full, a perfect, a balanced binary tree


## DATA STRUCTURES

The following data structure was used to accomplish the tasks for this project

### Basic Binary Tree

```c

/**
 * struct binary_tree_s - Binary tree node
 *
 * @n: Integer stored in the node
 * @parent: Pointer to the parent node
 * @left: Pointer to the left child node
 * @right: Pointer to the right child node
 */
struct binary_tree_s
{
    int n;
    struct binary_tree_s *parent;
    struct binary_tree_s *left;
    struct binary_tree_s *right;
};

typedef struct binary_tree_s binary_tree_t;

```

### Binary Search Tree

```c

typedef struct binary_tree_s bst_t;

```

### AVL Tree

```c

typedef struct binary_tree_s avl_t;

```

### Max Binary Heap

```c

typedef struct binary_tree_s heap_t;

```

## FILES

The following files were used to test my understanding on the concepts

[printing_funcs.c](../master/printing_funcs.c)

Contains functions used only for visualization purposes

[binary_trees.h](../master/binary_trees.h)

Contains function prototypes, headers and data structure declarations

[0-binary_tree_node.c](../master/0-binary_tree_node.c)

Function that creates a binary tree node

[1-binary_tree_insert_left.c](../master/1-binary_tree_insert_left.c)

Function that inserts a node as the left-child of another node

[2-binary_tree_insert_right.c](../master/2-binary_tree_insert_right.c)

Function that inserts a node as the right-child of another node

[3-binary_tree_delete.c](../master/3-binary_tree_delete.c)

Function that deletes an entire binary tree

[4-binary_tree_is_leaf.c](../master/4-binary_tree_is_leaf.c)

Function that checks if a node is a leaf

[5-binary_tree_is_root.c](../master/5-binary_tree_is_root.c)

Function that checks if a given node is a root

[6-binary_tree_preorder.c](../master/6-binary_tree_preorder.c)

Function that goes through a binary tree using pre-order traversal

[7-binary_tree_inorder.c](../master/7-binary_tree_inorder.c)

Function that goes through a binary tree using in-order traversal

[8-binary_tree_postorder.c](../master/8-binary_tree_postorder.c)

Function that goes through a binary tree using post-order traversal

[9-binary_tree_height.c](../master/9-binary_tree_height.c)

Function that measures the height of a binary tree

[10-binary_tree_depth.c](../master/10-binary_tree_depth.c)

Function that measures the depth of a node in a binary tree

[11-binary_tree_size.c](../master/11-binary_tree_size.c)

Function that measures the size of a binary tree

[12-binary_tree_leaves.c](../master/12-binary_tree_leaves.c)

Function that counts the leaves in a binary tree

[13-binary_tree_nodes.c](../master/13-binary_tree_nodes.c)

Function that counts the nodes with at least 1 child in a binary tree

[14-binary_tree_balance.c](../master/14-binary_tree_balance.c)

Function that measures the balance factor of a binary tree

[15-binary_tree_is_full.c](../master/15-binary_tree_is_full.c)

Function that checks if a binary tree is full

[16-binary_tree_is_perfect.c](../master/16-binary_tree_is_perfect.c)

Function that checks if a binary tree is perfect

[17-binary_tree_sibling.c](../master/17-binary_tree_sibling.c)

Function that finds the sibling of a node

[18-binary_tree_uncle.c](../master/18-binary_tree_uncle.c)

Function that finds the uncle of a node

