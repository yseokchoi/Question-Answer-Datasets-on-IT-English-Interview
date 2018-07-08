# Question-Answer(QA) Datasets on IT English Interview

IT 관련 영어 면접 데이터 셋



## QA Datasets

**SITES**

- https://www.tutorialspoint.com/tutorialslibrary.htm
- https://career.guru99.com/top-100-core-java-interview-questions/
- https://www.javacodegeeks.com/2014/04/java-interview-questions-and-answers.html
- https://www.javatpoint.com/interview-questions-and-answers



**Number of QA Pairs**

|            Sub-domain            | Number of QA Pairs |
| :------------------------------: | :----------------: |
| C/C++/Java Programming Languages |        885         |
|   Other Programming Languages    |       1,155        |
|             Database             |        700         |
|           Web Related            |       1,217        |
|            Java Tech             |        879         |
|               etc.               |       1,482        |
|            **TOTAL**             |     **6,318**      |

- The average number of **sentences** in questions and answers are ***1.04*** and ***2.25***, respectively.
- The average number of **words** in questions and answers are ***9.13*** and ***15.99***, respectively.



**Question Sentence Types**

|    Question Sentence Type     | Distribution |                           Keyword                            |
| :---------------------------: | :----------: | :----------------------------------------------------------: |
|   Iterrogative(WH question)   | 87.1%(5,500) | what(3,724)   how(1,091)   which(476)   why(90)<br />when(78)  where(23)  who(18) |
| Iterrogative(Yes/No question) |  6.16%(389)  |           can(155)  be(133)  do(96)  would/will(5)           |
|          Imperative           |  6.24%(394)  | explain(240) name(41) define(32) write(30)<br />give(17) list(12) etc.(22) |
|          Declarative          |   0.5(35)    |                                                              |



**Examples**

|  ID  | Sub-domain  |                           Question                           |                            Answer                            |
| :--: | :---------: | :----------------------------------------------------------: | :----------------------------------------------------------: |
|  78  |      C      | What is the difference between method overloading and method overriding in C#? | Method parameters must be different in method overloading whereas it must be same in method overriding. |
| 125  |      C      |       Distinguish between shallow copy and deep copy.        | Deep copy is achieved using copy constructor and or overloading assignment operator. |
| 154  |      C      |                    What is polymorphism?                     | In object-oriented programming paradigm, polymorphism is often expressed as 'one interface, multiple functions'. |
| 165  |      C      |             How C# supports static polymorphism?             | Static polymorphism. They are: Function overloading Operator overloading |
| 818  |  Database   |         What are the advantages of using a package?          | Modularity Easy to design the applications Better performance Hiding information Added functionality Overloading |
| 2498 |    Java     |    What is Function Overriding and Overloading in Java ?     | Method overloading in Java occurs when two or more methods in the same class have the exact same name, but different parameters. On the other hand, method overriding is defined as the case when a child class redefines the same method as a parent class |
| 2560 |    Java     | Can we use different return types for methods when overridden? | The basic requirement of method overriding in Java is that the overridden method should have same name,  and parameters |
| 2758 |    Java     | Can we override a method by using same method name and arguments but different return types? | The basic condition of method overriding is that method name, arguments as well as return type must he exactly same as is that of the method being overridden. |
| 2807 |    Java     |                What is covariant return type?                | Since java5, it is possible to override any method by changing the return type if the return type of the subclass overriding method is subclass type. |
| 4125 | Programming |              What is the use of final keyword?               | PHP 5 introduces the final keyword, which prevents child classes from overriding a method by prefixing the definition with final. |



**Analysis on QA Datasets**

- QA_ANALYZED_OUT.txt

- Using the Stanford Parsing

- Format

  Line1: **Question/Answer ID**

  Line2: **Sentence**

  Line3: **Number of Words**

  Line4-: **POS TAGGING & Dependency Analyzed**

  

**Evaluation Datasets**

- QA Datasets의 동일한 질문에 대한 4개의 사이트를 제외한 사이트에서 추출한 다른 답

- The average number of **words** in evaluation datasets are ***2.68***.

- Examples

  | 정답<br /> 질문 ID |                             응답                             |
  | :----------------: | :----------------------------------------------------------: |
  |        125         | Shallow Copy: Simply makes a copy of the reference to A into B. Deep copy: Simply makes a copy of all the members of A, allocates memory in a different location for B and then assigns the copied members to B to achieve deep copy. |
  |        405         | The COMMIT statement terminates the current transaction and ensures that changes made in the transaction are persistent. |
  |     1284, 2249     | A thread is an execution context, which is all the information a CPU needs to execute a stream of instructions. |
  |     2830, 2985     | The applet is a small Internet-based program written in Java. Applets can also be run as HTML. The applet is usually embedded in the HTML page of the website and can be executed within the browser. |
  |  3093, 3716, 4329  | A session is a semi-permanent interactive information interchange. A session is set up or established at a certain point in time, and then torn down at some later point. An established communication session may involve more than one message in each direction. |




## English Interview Datasets

영어 면접 질문-대답 데이터 셋

- file : **english interview_180708.xls**
- 591 Question-Answer Pairs
- The average number of **sentences** in questions and answers are ***1.04*** and ***3.27***, respectively.
- The average number of **words** in questions and answers are ***10.14*** and ***55.29***, respectively.



**Examples**

|                          Question                           |                            Answer                            |
| :---------------------------------------------------------: | :----------------------------------------------------------: |
|              Could you tell me about yourself               | Sure, Nice to meet you. My name is Min-Ji Lee currently senior student majoring in Airline service Tourism. I’m the oldest daughter of family with two younger brothers. I’m an outgoing and friendly person who enjoys traveling and meeting. I think I’m natural born flight attendant because I can make such bright smile on my face all the time. |
| Have you ever been in difficult situation  while traveling? | I have been to Hong Kong during the summer season. It was very muggy and humid.  So it was very difficult to travel. But thanks to the traveling, I am not easily affected by hot weather and I can enjoy summer now. |
|          What were your failures in your last job?          | One of the failures that I encountered in the company  was during the product launching of a new set of mobile phones that was targeted for the female segment of our consumer market.  I concluded that with the new design and user functions that we have developed,  we will be able to capture a major portion of this market and increase our profitability by as much as Unfortunately,  our competitor launched a similar type of product for much lower price and we lost our competitive edge in the market.  This experience taught me the importance of understanding our competitor‘s behavior when planning strategies. |

