
## Exercise 2.1

We consider $(\R \setminus  \{-1\},\star)$, where   
$a\star b := ab+a+b,\quad a,b\in \R\setminus\{-1\}$  

<b>a</b>. show that $(\R \setminus  \{-1\},\star)$ is an Abelian group.

<b>b</b>. solve $ 3\star x \star x = 15 $ in Abelian group $(\R \setminus  \{-1\},\star)$, where $\star$ is defined as previous. 

### Solution

#### Concepts Explaination 
$\R \setminus  \{-1\}$ means the set of all real numbers except for -1  

$a\star b$ [is defined](https://math.stackexchange.com/questions/25214/what-does-mean) to be $ab+a+b$.  

<b>Abelian group</b>(2.4.1) or commutative group simply means when apply an operation to two elements, the order of the elements will not effect the result.

#### Solution for question a
we need to proof that operation $\star$ in group $\R \setminus  \{-1\}$ is commutative. $a\star b \implies b\star a = b+a+ba$ 

\[\because (\R \setminus  \{-1\},\cdot,+), \text{is an Abelian group} \\
\therefore a(b+1)+b = b+a(1+b) = b+a+ab = b+a+ba
\]

#### Solution for question b
\[ 3\star x \star x = 3\star (x^2+2x) = 3(x^2+2x)+3+(x^2+2x)\implies\\
4x^2+8x+3 = 15\\
x_1 = -3, x_2 =1
\]
