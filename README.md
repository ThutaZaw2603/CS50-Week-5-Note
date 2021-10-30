# CS50-Week-5-Note
Cs50 Week5 Data-Structure Notes

## What Is Data-Structured
        It is the way of arranging the data to be able to use effectively.
        
## Summary Of Week 5
        1. Arrays
        2. Link Lists
        3. Binary Trees
        4. Hash Table
        5. Tries
        6. Abstract Data Structure
      
## 2. Link Lists
        Link lists are the data structure that each node in list is pointing to its contiguous another node.
        `` O(n) time ``
        [ Node 1 -> Node 2 -> Node 3 -> NULL ]
        
## 3. Binary Trees
        It is like the family tree that goes down from root node to children node.
        The left sub-node of current node will be smaller and the right will be greater than the current node.
                            
                               4
                            /     \
                           2       6
                          / \     / \
                         1   3   5   7
                         
        `` O(log(n)) recursively time ``
        
## 4. Hash Table  
        Hash Table is the array made of link list.
        `` O(n) time ``
        
                      [A  -> Aa   , B ->Bb      , C -> Cc ]
                      
## 5. Tries
        Tries is the binary tree made of array.
        `` O(1) ``
                      [A , B  C ]
                      /
                    [A,B, C]
                    
## 6.1 Queue 
        - First In First Out 
          Just the same idea of Java Script Callback Queue
          
## 6.2  Stack
        - Last In First Out 
          Just the same idea of Java Script Call Stack
          
          
## Typedef and Struct

          struct  = we can create our own custom data type with struct
                    ``C
                        struct customName{
                          init : number;
                          string : "string";
                          }
                     ``
                     
          typedef = we can rename the created data type with our own custom name
                    `` C
                    
                        typefef namedData newName;
                        
                     ``
                    
              
                           
