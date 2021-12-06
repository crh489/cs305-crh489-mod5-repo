# cs305-crh489-mod5-repo
Repository for NAU course CS305, for assignment module 5. Created by student user crh489.


<h1>CS 249 Final Exam Study List</h1>
<p>
Be able to analyze any of the following methods, including tracing operations given some data
Be able to write parts or all of any of the following methods
Be able to trace a BFS or DFS through a given graph


<h2>PA07</h2>
    public LL_IteratorClass()  
    <br>public LL_IteratorClass( LL_IteratorClass copied )  
    <br>public void displayIterator()  
    <br>public NodeClass getCurrentPriorRef()  
    <br>public int getValueAtCurrent()  
    <br>public boolean hasNext()  
    <br>public boolean hasPrev()  
    <br>public void insertAtCurrent( int newVal )  
    <br>public void insertAtEnd( int newVal )  
    <br>public void insertAtFront( int newVal )  
    <br>public boolean moveNext()  
    <br>public boolean movePrev()  
    <br>public int removeAtCurrent()  
    <br>public boolean setToFirst()  
    <br>public boolean setToLast()  
 
<h2>PA08</h2>
  public BST_Class()
  <br>public BST_Class( BST_Class copied )
  <br>private StudentClassNode copyConstHelper( StudentClassNode copiedRef )
  <br>public void insert( StudentClassNode inData )
  <br>private void insertHelper( StudentClassNode localRoot, 
                                                    StudentClassNode inData )
  <br>public String outputInOrder()
  <br>private void outputInOrderHelper( StudentClassNode localRoot )
  <br>public String outputPostOrder()
  <br>private void outputPostOrderHelper( StudentClassNode localRoot )
  <br>public String outputPreOrder()
  <br>private void outputPreOrderHelper( StudentClassNode localRoot )
  <br>private StudentClassNode removeFromMax( StudentClassNode parent, 
                                                    StudentClassNode child )
  <br>public StudentClassNode removeNode( StudentClassNode inData )
  <br>private StudentClassNode removeNodeHelper( StudentClassNode localRoot,
                                                   StudentClassNode outData )
  <br>public StudentClassNode search( StudentClassNode searchData )
  <br>private StudentClassNode searchHelper( StudentClassNode localRoot, 
                                                StudentClassNode searchData )

<h2>PA09</h2>
  public TwoThreeTreeClass()
  <br>public TwoThreeTreeClass( TwoThreeTreeClass copied )
  <br>private TwoThreeNodeClass 
                     copyConstructorHelper( TwoThreeNodeClass workingCopiedRef )
  <br>private void addAndOrganizeData( TwoThreeNodeClass localRef, String itemStr )
  <br>public void addItem( String itemStr )
  <br>private void addItemHelper( TwoThreeNodeClass localRef, String itemStr )
  <br>public void clear()
  <br>public int compareStrings( String leftStr, String rightStr )
  <br>private void fixUpInsert( TwoThreeNodeClass localRef )
  <br>private boolean foundInNode( TwoThreeNodeClass localRef, String searchStr )
  <br>public String inOrderTraversal()
  <br>private void inOrderTraversalHelper( TwoThreeNodeClass localRef )
  <br>public boolean search( String searchStr )
  <br>private boolean searchHelper( TwoThreeNodeClass localRef, String searchStr )

<h2>PA10</h2>
  public OpCodeHeapClass()
  <br>public OpCodeHeapClass( OpCodeHeapClass copied )
  <br>public void addItem( OpCodeClass newItem )
  <br>private void bubbleUpArrayHeap( int currentIndex )
  <br>private void checkForResize()
  <br>public boolean isEmpty()
  <br>public OpCodeClass removeItem()
  <br>public void setDisplayFlag( boolean setState )
  <br>public void showArray()
  <br>private void trickleDownArrayHeap( int currentIndex )
<h2>PA11</h2>
  public BST_HashClass()
  <br>public BST_HashClass( int inTableSize )
  <br>public BST_HashClass( BST_HashClass copied )
  <br>public void addItem( String inName, 
                        int inStudentID, char inGender, double inGPA )
  <br>public void addItem( StudentClassNode newItem )
  <br>public void clearHashTable()
  <br>public StudentClassNode findItem( int studentID )
  <br>public int generateHash( StudentClassNode studentData )
  <br>public StudentClassNode removeItem( int studentID )
  <br>public void showHashTableStatus()
</p>
