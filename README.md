d # 数据科学（Python实现）
## 作者：刘晓凯


## 前言

本书的编写动机最初来源于我在本科期间于郑州大学信息工程学院参与《数据科学》一书的编篡经历。当时，我的计算机专业引路人王振飞老师为本书主编，其余他的硕士生为本书的编委。而我是作为一名副主编的身份来统筹编写《数据科学》一书。我主要内容设计，负责统筹大家的工作，并负责编写主要的章节（总计章数的一半）。

虽然，在编写《数据科学》一书时，我投入了巨大的精力。但是，遗憾的是，自我离开郑州大学进入华中科技大学攻读网络安全硕士后，就逐渐没有听到关于本书的编篡进展，且这本书直到我硕士毕业我也没能见到它的出版。我离开郑州大学之时，该书已经完成了十之七八，很遗憾最终没能看到印有我名字的书籍，哪怕是草稿也没有。

我在入读华中科技大学两年后，偶然间看到了我于本科期间缩写的书籍草稿。想到本书籍的出版一直了无音信，为了能帮助读者学习Python与大学数学，并为开源社区做一份贡献，我决定将本书进行开源，并将原来的《数据科学》一书一分为二分别为《数据科学》与《使用Python学习高等数学》两部分。前者着重从宏观角度介绍数据科学的理论与实践，后者则是在讲解高等数学的同时辅以详细的Python实践。目前，这两本教程已经在Github开源，并使用Gitbook对本书进行在线展示，供读者学习。

遗憾的是，由于书籍编篡是一项繁琐且耗时的工作，我只有在我的课余时间才有时间去完成他们。因此，本书尚有诸多需要补充及校对的地方。如发现错误，请谅解。若您能为本书提供意见，或着报告错误于我，我将感激不尽！

Johannes Liu

Huazhong University of Science and Technology

## 寻求帮助

欢迎愿意参加此书籍编篡工作的本科生，研究生与我联系！本书的正式版本将按照贡献进行署名及致谢。

## 本书组织结构

本书组织结构如下

├─Appendix-A
│      A.1-Calculus.md
│      A.2-Linear_Algebra.md
│      A.3-Probability_Statistics.md
│      Appendix.0-Mathematics_Foundation.md
│          
├─Appendix-B
│      B.0-Foundation_Markdown.md
│      B.1-Prelimary.md
│      B.2-Basic_Grammar.md
│      B.3-Jupyter_for_Markdown.md
│      B.4-Reference.md
│      B.5-Practice.md
│          
├─Appendix-C
│      C.0-Foundation_Jupyter_Kernal.md
│      C.1-Introduction_to_Jupyter_Kernal.md
│      C.2-Kernal_Manipulation.md
│      C.3-Install_Kernal.md
│      C.4-Meta_Kernal.md
│      C.5-Extensive_Reading_Materials.md
│          
├─Appendix-D
│      D.0-Foundation_Git.md
│      D.1-Introduction_to_Git.md
│      D.2-Git_Commands.md
│      D.3-Extensive_Reading_Materials.md
│      
├─Appendix-E
│      E.0-Foundation_Docker.md
│      E.1-Prelimary.md
│      E.2-Basic_Manipulator.md
│      E.3-Reference.md
│          
├─Chapter1
│      1.0-Prelimary.md
│      1.1-Data_Science_Introduction.md
│      1.2-Why_Choose_Python.md
│      1.3-The_History_of_Python.md
│      1.4-Install_Python_Interpreter.md
│      1.5-Hello_world.md
│      1.6-Comments.md
│      1.7-Extensive_Reading_Materials.md
│      1.8-Summary.md
│      1.9-Practice.md
│      
├─Chapter10
│      10.0-Foundation_Signal_Processing.md
│      10.1-Foundation_PyWavelets.md
│      10.2-Theory_Wavelets.md
│      10.3-Wavelets.md
│      10.4-Signal_Mode.md
│      10.5-Discrete_Reverse_Transform.md
│      10.6-DWT_IDWT_SWT.md
│      
├─Chapter11
│      11.0-Foundation_Matplotlib.md
│      11.1-Introduction_to_Matplotlib.md
│      11.2-Elements.md
│      11.3-Stat_Plot.md
│      11.4-Auxilary_Function.md
│      11.5-Plot3D.md
│      11.6-Summary.md
│      
├─Chapter12
│      12.0-Foundation_Mayavi.md
│      12.1-Introduction_to_Mayavi.md
│      12.2-Application.md
│      12.3-Mlab.md
│      12.4-Advanced_Application.md
│      12.5-Extensive_Reading_Materials.md
│          
├─Chapter13
│      13.0-Foundation_Data_Analysis.md
│      13.1-Prelimary.md
│      13.2-Data_Type.md
│      13.3-Basic_Manipulation.md
│      13.4-Advanced_Manipulation.md
│      13.5-Input_Output.md
│      13.6-HPC.md
│      13.7-Extensive_Reading_Materials.md
│      
├─Chapter2
│      2.0-Build_Environment.md
│      2.1-Package.md
│      2.2-Anaconda.md
│      2.3-Jupyter.md
│      2.4-IDE.md
│      2.5-Text_Editor.md
│      2.6-Extensive_Reading.md
│      2.7-Summary.md
│      2.8-Practice.md
│      
├─Chapter3
│      3.0-Basic_Data_Structure.md
│      3.1-Basic_Object.md
│      3.10-Practice.md
│      3.2-Numeric.md
│      3.3-Combination.md
│      3.4-File.md
│      3.5-Dynamics.md
│      3.6-String_Format.md
│      3.7-Art_of_Programming.md
│      3.8-Summary.md
│      3.9-Extensive.md
│    
├─Chapter4
│      4.0-Practice.md
│      4.1-Control_Sequence.md
│      4.2-Assignment.md
│      4.3-Input.md
│      4.4-Output.md
│      4.5-Exception.md
│      4.6-Summary.md
│      4.7-Practice.md
│      
├─Chapter5
│      5.0-Function.md
│      5.1-What_is_function.md
│      5.2-Function_Declare.md
│      5.3-Name_Space.md
│      5.4-Return.md
│      5.5-Multiplex.md
│      5.6-Function_Application.md
│      5.7-Summary.md
│      5.8-Practice.md
│      
├─Chapter6
│      6.0-Object-Oriented.md
│      
├─Chapter7
│      7.0-NumPy_Foundation