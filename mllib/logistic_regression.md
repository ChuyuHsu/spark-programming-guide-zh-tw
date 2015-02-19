# 邏輯斯迴歸(Logistic regression)
邏輯斯迴歸廣泛被運用於二元變量預測。它是之前"數學公式"一節中竹竹尸一中描述的線性方法，其損失函數是logistic losss:
$$
L(w;x,y)=log(1+exp(-yx^Tx))
$$
迴輯斯迴歸算法的產出是一個卜口田中土輯斯迴歸模型。給定新數據點$$x$$，該模型運用下面的邏輯函數來預測：
$$
f(z)=\frac{1}{1+e^{-z}}
$$
在這裡，$$z=w^Tx$$。預設情況下，若$$f(w^Tx)\gt0.5$$輸出是正例，否則是反例。與線性SVM不同之處在於，線性迴歸模型$$f(z)$$輸出含有一個機率解釋(即$$x$$)是正例的機率。