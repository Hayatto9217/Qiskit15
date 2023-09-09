# Qiskit15

Extended Simulatorは、Qiskit-Aer の最新リリースで利用可能な量子回路を古典的にシミュレートするための新しいメソッドです。

本手法は、Bravyi, Browne, Calpin, Campbell, Gosset & Howard 2018 らによる Simulation of quantum circuits by low-rank stabilizer decompositions by Bravyi, Browne, Calpin, Campbell, Gosset & Howard, 2018, arXiv:1808.00128 論文に掲載されたアイデアを実装したものです。

それは量子回路の異なる表現を使用し、それはいくつかのユニークな機能を与えます。 このノートブックは、拡張スタビライザ方式ができることのいくつかの例を示します。

Extended Stabilizerメソッドは2つの部分から構成されています。 1つ目は、量子回路を スタビライザ回路 に分解する方法で、古典的に効率的にシミュレーションできる特別なクラスの回路です。 次に、これらの回路を組み合わせて測定を行う方法です。

