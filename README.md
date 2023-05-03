Download Link: https://assignmentchef.com/product/solved-cs_1d-homework-4-binary-search-trees
<br>
<strong>Binary Search Trees</strong>

<strong>(a) </strong>Implement classes TreeNode and BinarySearchTree. Use the following function prototypes as a starting point.

<table width="0">

 <tbody>

  <tr>

   <td width="686"><strong>template </strong>&lt;<strong>typename </strong>KeyType, <strong>typename </strong>ElementType&gt; <strong>class </strong>TreeNode{KeyType key;ElementType info;TreeNode * left, * right; <strong>public</strong>:TreeNode(KeyType newKey, ElementType newInfo, TreeNode *l, TreeNode *r); <strong>static </strong>TreeNode * newNode(KeyType k, ElementType e, TreeNode * l, TreeNode * r); <strong>static </strong>TreeNode * insert(KeyType key, ElementType info, TreeNode * t); <strong>static </strong>TreeNode * find(KeyType key , TreeNode * t); <strong>static </strong>TreeNode * remove(KeyType key , TreeNode * t); <strong>static void </strong>print(ostream &amp; out , TreeNode * t); <strong>static void </strong>deleteNode(TreeNode * t); <strong>static void </strong>deleteTree(TreeNode * t);};<strong>template </strong>&lt;<strong>typename </strong>KeyType, <strong>typename </strong>ElementType&gt; <strong>class </strong>BinarySearchTree{ TreeNode * root; <strong>public</strong>:<strong>void </strong>insert(KeyType key, ElementType info); ElementType find(KeyType key); <strong>void </strong>remove(KeyType key);<strong>void </strong>print(ostream &amp; out); };</td>

  </tr>

 </tbody>

</table>

1

<ol>

 <li>Implement TreeNode

  <ul>

   <li>It will have two data members – a KeyType which will be of type string, and an ElementType which will be of type int.</li>

   <li>ElementType (which will be the count (the frequency of occurrence) of each word in a given file).</li>

  </ul></li>

 <li>Implement BinarySearchTree

  <ul>

   <li>You may write some functions recursively.</li>

   <li>You do not have to show O(N) derivations if your functions are recursive.</li>

  </ul></li>

 <li>Write the following functions with the O(N) in the comments (unless recursive)

  <ul>

   <li>BinarySearchTree::insert(string s,int count) • BinarySearchTree::find(string s)</li>

  </ul></li>

</ol>

<h1><strong>CS1D Spring 2019 TTH 5PM                                    </strong>HW05: 100pts – Due: Thu 03/14/2019 7:20PM</h1>

<ul>

 <li>BinarySearchTree::remove(string s)</li>

 <li>TreeNode::insert()</li>

 <li>int &amp; BinarySearchTree::operator[] (string s)</li>

</ul>

<strong>(b)</strong>Convert TreeNode and BinarySearchTree into a template

<ol>

 <li>Convert TreeNode and BinarySearchTree into a template so that KeyType and ElementType may be specified with different types.</li>

 <li>Create a tar file which includes hw04.cpp, hw04f.cpp, hw04.h, and hw04.scr</li>

 <li>Submit hw04.tar to canvas by the due date on top of this page. 4. Be sure to include valgrind results in your script file</li>

</ol>