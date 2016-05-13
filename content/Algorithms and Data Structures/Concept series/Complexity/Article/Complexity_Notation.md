Title: Complexity：Asymptotic Notation(漸進符號)  
Date: 2016-5-11 20:31 
Category: 演算法與資料結構  
Tags: C++, Intro, Complexity, Big-O,  
Summary: 介紹用來分析Complexity(複雜度)的Asymptotic Notation(漸進符號)。


</br>
###先備知識與注意事項

假設有天想要印書出版，印刷廠一共有六台機器，效率如圖一，橫軸表示「書的數量」，縱軸表示「需要的工作天」，


<center>
![cc][f1]

**圖一：。**
</center>


|       |$N!$ |$2^N$|$N^2$|&nbsp;&nbsp;$N\log{N}$|$N$  |&nbsp;&nbsp;$\log{N}$|
|:---   |:---:|:---:|:---:|:---:|:---:|:---:|
|$N=5$  |$120$  |$32$ |$25$|$8.05$ |$5$  |$1.6$|
|$N=100$|&nbsp;&nbsp;&nbsp;&nbsp;$9\times10^{157}$|&nbsp;&nbsp;$1.3\times10^{30}$|&nbsp;&nbsp;$10000$|$460$ |&nbsp;&nbsp;$100$|$4.6$|




// 放數據

印刷機器比較老舊，處理資料的速度

處理5本書，要120天，
處理100本書，要

***

##目錄

* [使用Asymptotic Notation的優點](#an)
* [$\Theta-$Notation](#tight)
* [$O-$Notation](#bo)
* [$\Omega-$Notation](#bw)
* [$o-$Notation](#so)
* [$\omega-$Notation](#sw)
* [參考資料](#ref)
* [Complexity系列文章](#series)


</br>

<a name="an"></a>

##使用Asymptotic Notation的優點

// 為什麼要使用





</br>  

<a name="tight"></a>

###$\Theta-$Notation

// 定義

// 範例, 繪圖


</br>    

<a name="bo"></a>

###$O-$Notation



</br>  

<a name="bw"></a>

###$\Omega-$Notation



</br>

<a name="so"></a>

###$o-$Notation


</br>

<a name="sw"></a>

###$\omega-$Notation




[f1]: f1.png
[f2]: f2.png



</br>  


 
以上便是以Array表示Set之介紹。


</br>

***

<a name="ref"></a>

###參考資料：

* [Introduction to Algorithms, Ch3](http://www.amazon.com/Introduction-Algorithms-Edition-Thomas-Cormen/dp/0262033844) 
* [Fundamentals of Data Structures in C++, Ch1](http://www.amazon.com/Fundamentals-Data-Structures-Ellis-Horowitz/dp/0929306376)
* [Big-O Algorithm Complexity Cheat Sheet](http://bigocheatsheet.com/)
* [Infinite Loop：複雜度分析 - Complexity Analysis](http://program-lover.blogspot.tw/2008/10/complexity-analysis.html)




<a name="series"></a>

</br>

###Complexity系列文章

[Complexity：Asymptotic Notation(漸進符號)]()  


回到目錄：

[目錄：演算法與資料結構](http://alrightchiu.github.io/SecondRound/mu-lu-yan-suan-fa-yu-zi-liao-jie-gou.html)

</br>

