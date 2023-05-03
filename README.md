Download Link: https://assignmentchef.com/product/solved-cs-201-data-structures-library-phase-2
<br>



Phase 2 of the CS201 programming project, we will be built around a balanced binary search tree.  In particular, you should implement red-black trees as described in the CLRS textbook for the class RBTree.

The public methods of your class should include the following (keytype and valuetype indicate the types from the template):

<table width="623">

 <tbody>

  <tr>

   <td width="228">Function</td>

   <td width="312">Description</td>

   <td width="84">Runtime</td>

  </tr>

  <tr>

   <td width="228">RBTree();</td>

   <td width="312">Default Constructor. The tree should be empty</td>

   <td width="84">O(1)</td>

  </tr>

  <tr>

   <td width="228">RBTree(keytype k[], valuetype V[], int s);</td>

   <td width="312">For this constructor the tree should be built using the arrays K and V containing s items of keytype and valuetype.</td>

   <td width="84">O(s lg s)</td>

  </tr>

  <tr>

   <td width="228">~RBTree();</td>

   <td width="312">Destructor for the class.</td>

   <td width="84">O(n)</td>

  </tr>

  <tr>

   <td width="228">valuetype * search(keytype k);</td>

   <td width="312">Traditional search.  Should return a pointer to the valuetype stored with the key.  If the key is not stored in the tree then the function should return NULL.</td>

   <td width="84">O(lg n)</td>

  </tr>

  <tr>

   <td width="228">void insert(keytype k, valuetype v);</td>

   <td width="312">Inserts the node with key k and value v into the tree.</td>

   <td width="84">O(lg n)</td>

  </tr>

  <tr>

   <td width="228">int remove(keytype k);</td>

   <td width="312">Removes the node with key k and returns 1.  If key k is not found then remove should return 0.</td>

   <td width="84">O(lg n)</td>

  </tr>

  <tr>

   <td width="228">int rank(keytype k);</td>

   <td width="312">Returns the rank of the key k in the tree.  Returns 0 if the key k is not found. The smallest item in the tree is rank 1.</td>

   <td width="84">O(lg n)</td>

  </tr>

  <tr>

   <td width="228">keytype  select(int pos);</td>

   <td width="312">Order Statistics. Returns the key of the node at position pos in the tree.  Calling with pos = 1 should return the smallest key in the tree, pos = n should return the largest.</td>

   <td width="84">O(lg n)</td>

  </tr>

  <tr>

   <td width="228">keytype *successor(keytype k)</td>

   <td width="312">Returns a pointer to the key after k in the tree.  Should return NULL if no successor exists.</td>

   <td width="84">O(lg n)</td>

  </tr>

  <tr>

   <td width="228">keytype *predecessor(keytype k)</td>

   <td width="312">Returns a pointer to the key before k in the tree.  Should return NULL if no predecessor exists.</td>

   <td width="84">O(lg n)</td>

  </tr>

  <tr>

   <td width="228">int size();</td>

   <td width="312">returns the number of nodes in the tree.</td>

   <td width="84">O(1)</td>

  </tr>

  <tr>

   <td width="228">void preorder();</td>

   <td width="312">Prints the keys of the tree in a preorder traversal.</td>

   <td width="84">O(n)</td>

  </tr>

  <tr>

   <td width="228">void inorder();</td>

   <td width="312">Prints the keys of the tree in an inorder traversal.</td>

   <td width="84">O(n)</td>

  </tr>

  <tr>

   <td width="228">void postorder();</td>

   <td width="312">Prints the keys of the tree in a postorder traversal.</td>

   <td width="84">O(n)</td>

  </tr>

 </tbody>

</table>




Your class should include proper memory management, including a destructor, a copy constructor, and a copy assignment operator.




For submission, all the class code should be in a file named RBTree.cpp.  Create a makefile for the project that compiles the file phase2main.cpp and creates an executable named phase2.  A sample makefile is available on Blackboard.  Place both RBTree.cpp and makefile into a zip file and upload the file to Blackboard.

☐ Create your RBTree class

☐ Modify the makefile to work for your code (changing compiler flags is all that is necessary)

☐   Test your RBTree class with the sample main provided on the cs-intro server

☐   Make sure your executable is named phase2

☐   Develop additional test cases with different types, and larger trees

☐   Create the zip file with RBTree.cpp and makefile

☐   Upload your zip file to Blackboard




No late submissions will be accepted.  There will be an opportunity to resubmit by March 26.  Resubmissions will have a 20 point penalty.


