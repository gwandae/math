\title{\vspace{3 cm}7-1 이산확률변수 aX+b의 기댓값과 표준편차}
\author{이한희}
\maketitle

 #### 개념열기

 $Y=aX+b\quad$ ($a, b$는 상수, $a\ne0$) 일 때,

 $E(Y)=E(aX+b)$

 $=(ax_1+b)p_1+\cdots+(ax_n+b)p_n$

 $=a(x_1p_1+\cdots+x_np_n)+b(p_1+\cdots p_n)$

 $=aE(X)+b$

 $V(Y)=V(aX+b)$

 $=\bigg((ax_1+b)-\Big(aE(X)+b\Big)\bigg)^2p_1+\cdots$

 $=a^2\bigg(x_1-E(X)\bigg)^2p_1+\cdots$

 $=a^2V(X)$

 $\sigma(Y)=\sqrt{V(Y)}=\sqrt{a^2V(X)}=|a|\,\sigma(X)$

 #### 개념1. 이산확률변수 $aX+B$의 기댓값, 분산, 표준편차

 $E(aX+b)=aE(X)+b$

 $V(aX+b)=a^2V(X)$

 $\sigma(aX+b)=|a|\,\sigma(X)$

 #### 문제5. 확률변수 $X$의 평균이 10, 분산이 5일 때, 다음 확률변수의 평균, 분산, 표준편차를 각각 구하시오.

 (1) $2X+3$

 (2) $-X+1$

 풀이

$E(X)=10,\ V(X)=5$

 (1) 

 $E(2X+3)=2E(X)+3=23$

 $V(2X+3)=2^2\times5=20$

 $\sigma(2X+3)=2\sqrt5$

 (2)

 $E(-X+1)=-E(X)+1=-9$

 $V(-X+1)=V(X)=5$

 $\sigma(-X+1)=\sqrt5$

 #### 예제3. 확률변수 $X$의 평균이 $m$, 표준편차가 $\sigma$일 때, 확률변수 $Z=\dfrac{X-m}{\sigma}$의 평균과 분산을 구하시오.

 $E(X)=m,\ V(X)=\sigma^2$

 $E(Z)=E\left(\dfrac{X-m}{\sigma}\right)=\dfrac{1}{\sigma}E(X)-\dfrac{m}{\sigma}=\dfrac{m}{\sigma}-\dfrac{m}{\sigma}=0$

 $V(Z)=V\left(\dfrac{X-m}{\sigma}\right)=\dfrac{1}{\sigma^2}V(X)=\dfrac{1}{\sigma^2}\times\sigma^2=1$

 분산$=$표준편차$^2$

 #### 수역기. 어느 시험에서 전체 응시자의 시험 점수를 확률변수 $X$라고 하자. $X$의 평균이 $m$점, 표준편차가 $\sigma$점일 때, 

 $T=100+20\left(\dfrac{X-m}{\sigma}\right)$

 을 표준점수라고 한다. 다음 상민이와 세미의 물음에 각각 답해보자.

 그림

 풀이 상민

 $E(T)=E\Bigg(100+20\left(\dfrac{X-m}{\sigma}\right)\Bigg)$

 $=100+20\times\dfrac{E(X)-m}{\sigma}=100$

 $\sigma(T)=\sigma\Bigg(100+20\left(\dfrac{X-m}{\sigma}\right)\Bigg)$

 $=\dfrac{20}{\sigma}\times\sigma(X)=20$

 평균을 0으로 만들어주는 테크닉

 풀이 세미

 $X=90, m=60, \sigma=15$

 $T=100+20\times\dfrac{90-60}{15}=140$

 