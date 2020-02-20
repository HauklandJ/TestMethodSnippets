# TestMethodSnippets
Cope snippets for test methods for C#, Visual studio

Add the snippets in Visual Studio by using the Code Snippets Manager. 

Open it by choosing **Tools > Code Snippets Manager**. 

Select **import**. 

Add the snippets to **My Code Snippets**.

The shortcut for the generic test method snippet is `tmet`, the following is generated:
```CSharp
	[TestMethod]
        public void Test()
        {
            // -- Arrange


            //-- Act


            //--Assert
         }
  ```
  The shortcut for the AreEquals test method snippet is `tmeteq`, the following is generated:
  
  ```CSharp
	    [TestMethod]
        public void Test()
        {
            // -- Arrange


            //-- Act


            //--Assert
	        Assert.AreEqual(expected, actual);
         }
  ```
  
  Your cursor is placed at the end of `Test`.
