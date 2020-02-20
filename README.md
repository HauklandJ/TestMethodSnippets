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
  
  Your cursor is placed at the acces modifier which is `public` by default, tab to move to the return type which is `void` by default and the method name which is `New_test` by default. Hit enter to be placed under `Arrange`.
