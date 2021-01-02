# Markdown on VS Code

---

- *This is a tutorial on how to use markdown through Visual Stuido Code.*
- *The source code is [here](https://github.com/ejbo/markdown/blob/master/markdown.md). Check out the examples that are written in markdown by click :pen: (```Edit this file```)*.
- *To help make this tutorial better, please send email to `zhenglin@ucsb.edu`*.
---

[TOC]

---

### **Extention**

- ***Markdown All in One:*** Markdown shortcuts.
- ***Markdown Preview Enhanced:*** Preview the Markdown in HTML's style. 
- ***Markdown PDF:*** Convert .md file to other formats. 
- ***Markdown Preview Github Styling:*** Preview the Markdown in Github's style.

---

### **Title**

- <font color = "blue">*syntax:*</font>
  ``#``
  <font color = "green"> code: </font>
  `` # Heading One ``
   <font color = "green"> output: </font>
  # Heading One
    
- <font color = "blue">*syntax:*</font>
  ``##``
  <font color = "green"> code: </font>
  `` ## Heading Two ``
  <font color = "green"> output: </font>
  ## Heading Two
  
- <font color = "blue">*syntax:*</font>
  ``###``
  <font color = "green"> code: </font>
  `` ### Heading Three ``
  <font color = "green"> output: </font>

  ### Heading Three

- <font color = "blue">*syntax:*</font>
  ``####``
  <font color = "green"> code: </font>
  `` #### Heading Four ``
  <font color = "green"> output: </font>

  #### Heading Four

- <font color = "blue">*syntax:*</font>
  ``#####``
  <font color = "green"> code: </font>
  `` ##### Heading Five ``
  <font color = "green"> output: </font>

  ##### Heading Five

---

### **Code**

- ***A whole section of code***: 

    <font color = "blue">*syntax:*</font>
    ` ```code``` `

    |code|output|
    |----|------|
    |` ```Hello Markdown!``` `| ```Hello Markdown!```|

    - When you need to write the particular programming language, specify it after the first ` ``` `
    
    <font color = "green"> code: </font>
    ![example](./pics/section_code%20example.png)
    <font color = "green"> output: </font>
    ```c++ 
    cout << "Hello Markdown!" << endl;
    ```

- ***Code in the sentences***：

    When needs to include the code in a sentence(a line):

    *syntax:* ` `` code `` ` or `` `code` ``
    
    |code|output|
    |----|------|
    |I want to say` ``Hello Markdown!`` `| I want to say ``Hello Markdown!``| 


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
  
  |code|output|
  |----|------|
  |```**text**```|**text**|

- ***Inclined***

  |code|output|
  |----|------|
  |```*text*```|*text*| 

- ***Delete***

  |code|output|
  |----|------|
  |```~~text~~```|~~text~~| 
  
- ***Label***
  
  - *Superscript*
  
    |code|output|
    |----|------|
    |```label <sup> text </sup>```|label <sup> text </sup>|
    |```label^text^```| label^text^| 
       
  - *Subscipt*
    |code|output|
    |----|------|
    |```label <sub> text </sub>```|label <sub> text </sub>|
    |```label~text~```|label~text~|   

  - *Footnote*
    |code|output|
    |----|------|
    |``label [^text]`` <br>``[^text]:this is the footnote for Label-Footnote.``|label [^text]
    [^text]:this is the footnote for Label-Footnote.
    
    "^text" is used for matching the "label". The footnote is shown as "[1]", which means "^text" does not affect the appearance of the footnote.

- ***Cutting Line***
  
  ```---```

- ***Color***

  |code|output|
  |----|------|
  |``<font color = #FF0000> Red Text </font>``|<font color = #FF0000> Red Text </font>|
  |``<font color = "blue"> Blue Text </font>``|<font color = "blue"> Blue Text </font>|
    

- ***Reference***
  
  <font color = "blue">*syntax:*</font>
  ``>``
  <font color = "green"> code: </font>
  ``>This is the reference``
  <font color = "green"> output: </font>
  >This is the reference
---

### **Insert**

- ***Insert Image***
  
  - **From Local**
    <font color = "blue">*syntax:*</font>
    ```![image_name](path)```

    - The image_name can be whatever you want to call it. It just show as a reference for your markdown.
    - Back to the previous level: `../whatever_image`
    - Go to another folder in the current level: `folder/whatever_image`
  
    <font color = "green"> code: </font>
    ```![Cyberbunk2077](pics/Cyberbunk2077.png)```
    <font color = "green"> output: </font>
    ![Cyberbunk2077](pics/Cyberbunk2077.png)
  
  - **From Link**
  
    <font color = "blue">*syntax:*</font>
    ```**![image_name](link)```
    <font color = "green"> code: </font>
    ```![Dota2](https://img.dota2.com.cn/dota2/eb/82/eb823ad9ca2ac2b755739f61f8204ff91608268237.jpg)```
    <font color = "green"> output: </font>
    ![Dota2](https://img.dota2.com.cn/dota2/eb/82/eb823ad9ca2ac2b755739f61f8204ff91608268237.jpg)

- ***Insert URL*** 
  
  <font color = "blue">*syntax:*</font>
  ```[text](URL)```
  - ``text`` here is the content you want to show on the markdown page. ``URL`` is the link of the website. 

  |code|output|
  |----|------|
  |```[Here](https://google.com) is Google```|[Here](https://google.com) is Google|

- ***Insert Emoji***

  *emoji cheat sheet:*

  > https://www.webfx.com/tools/emoji-cheat-sheet/

  | code | output|
  | ---  | ---   |
  |```:kissing_smiling_eyes:```|:kissing_smiling_eyes:|
  

       
  
