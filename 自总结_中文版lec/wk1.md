<h1>1. Introduction

- 1.1 What is an Algorithm?  
    
    **一些名词：**  

    - *Time complexity*: efficiency of an algorithm  
    - *Analyze an algorithm*: to determine its time complexity for the given type of inputs  
    - *Worse case analysis*: determine the largest number of basic steps needed to execute the algorithm for any input of size n  
    - *Average case analysis*  
    - *An algorithm is optimal*: it provides the necessary functionality with the smallest possible numbers of steps for each input
    - *Correctness*: correct functionality for all possible inputs (唯一确认correctness的方法是通过<u>数学证明</u>)  
    - *Problem solving*: 设计算法和合适的数据结构的过程
    - *Implement*: 通过代码实现算法

    **实现算法的标准(criteria)：**  

    - *reliability可靠度*: the implementation is correct and it will not introduce vulnerabilities漏洞 to the system that runs it.
    - *maintainability可维护性*: one can easily replace a part of the code in order to provide somewhat different functionality
    - *extensibility可延展性*: to obtain more features, additional piece of code can be integrated with the existing code with little or no modifications of the already existing code needed;
    - *reusability可重用性*: possibility of using parts of the code in another application. This is accomplished by modular design模块化设计.
    - *robustness稳健性*: 用户输入垃圾数据(unexpected or illegitimate input)时，程序不会崩;
    - *user friendliness*: users can interact with ease with the program during its execution;
    - *implementation time*: implementation takes a reasonable amount of programming time and other resources.
