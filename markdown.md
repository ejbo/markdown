# Markdown on VS Code

---

- *This is a tutorial on how to use markdown through VS Code.*
- *The source code is [here](https://github.com/ejbo/markdown/blob/master/markdown.md). Check out the examples that are written in markdown by click ```Edit this file```*

---

### **Extention**

- ***Markdown All in One:*** Markdown shortcuts.
- ***Markdown Preview Enhanced:*** Preview the Markdown in HTML's style. 
- ***Markdown PDF:*** Convert .md file to other formats. 
- ***Markdown Preview Github Styling:*** Preview the Markdown in Github's style.

---

### **Title**

- `` # Heading One ``
  
  # Heading One
    
- `` ## Heading Two``

  ## Heading Two
  
- `` ### Heading Three ``

  ### Heading Three

- `` #### Heading Four ``

  #### Heading Four

- `` ##### Heading Five ``

  ##### Heading Five

---

### **Code**

- ***A whole section of code***: 

    - Using a pair of triple `` ` `` to include the code. 

    - When you need to write the particular programming language, specify the language after the first triple `` ` ``
      
    Have a try:

    ```c++
    cout << "Hello Markdown!" << endl;
    ```

- ***Code in the sentences***：

    When needs to include the code in a sentence, use double `` ` ``

    Have a try:

    I learned C++ last quarter ``cout << "hello"； ``

---

### **List**

- ***Ordered***
  1. Press ```1.``` and ```Space``` to start
  2. Automatically generate next list when press ```Enter```
     1. To start a sublist.
     2. Press ```tab```

- ***Unordered***
  - Press ```-``` then ```tab```

---

### **Layout**

- ***Bold***
  
  ```**text**```

   **text**

- ***Inclined***

  ```*text*```

   *text*

- ***Delete***

  ```~~text~~```

   ~~text~~

- ***Label***
  
  - *Superscript*
    - ```label <sup> text </sup>```
      label <sup> text </sup>
    - ```label^text^```
      label^text^
    
  - *Subscipt*
    - ```label <sub> text </sub>```
      label <sub> text </sub>
    - ```label~text```
      label~text~

  - *Footnote*
    ```
    label [^text]
    [^text]:this is the footnote for Label-Footnote.
    ```
    label [^text]
    [^text]:this is the footnote for Label-Footnote.

    "^text" is used for matching the "label". The footnote is shown as "[1]", which means "^text" does not affect the appearance of the footnote. 

- ***Cutting Line***
  
  ```---```

- ***Color***
   
  ``<font color = #FF0000> Red Text </font>``

    <font color = #FF0000> Red Text </font>

- ***Reference***

  ``>This is the reference.``

  >This is the reference.

---

### **Insert**

- ***Insert Image***
  
  - **From Local**
  
    ```![image_name](path)```

    The image_name can be whatever you want to call it. It just show as a reference for your markdown.

    *e.g:*

    ```![Cyberbunk2077](1.png)```

    ![Cyberbunk2077](1.png)
  
  - **From Link**
  
    ```![image_name](link)```

    *e.g:*

    ```![Dota2](https://img.dota2.com.cn/dota2/eb/82/eb823ad9ca2ac2b755739f61f8204ff91608268237.jpg)```

    ![Dota2](https://img.dota2.com.cn/dota2/eb/82/eb823ad9ca2ac2b755739f61f8204ff91608268237.jpg)

- ***Insert URL***

  ```[text](URL)```

  ``text`` here is the content you want to show on the markdown page. ``URL`` is the link of the website. 

  *e.g:*

  ```[Here](https://github.com/ejbo/markdown/blob/master/markdown.md) is the markdown page of this tutorial.```

  [Here](https://github.com/ejbo/markdown/blob/master/markdown.md) is the markdown page of this tutorial.

- ***Insert Emoji***

  > https://www.webfx.com/tools/emoji-cheat-sheet/

  ```:kissing_smiling_eyes:```
  :kissing_smiling_eyes:


    

       
  
