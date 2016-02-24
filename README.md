# knowledge
一些知识点记录
#####继承构造
A extends B<br/>
B中有方法(print,say)<br/>
A中有方法(print)<br/>
1.B b=new B();<br/>
b.print()<br/>
首先进入B构造，在调用B中的print方法<br/>

2.B b=new A();<br/>
b.print()<br/>
首先进入B的构造，在进入A的构造，再调用A中的print<br/>

3.B b =new A();<br/>
b.say()<br/>
首先进入B的构造，在进入A的构造，在调用B中的say<br/>

4. A a =new A();<br/>
a.say<br/>
首先进入B的构造，在进入A的构造，在调用B中的say<br/>
