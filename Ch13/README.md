# 13.1-1
ノートに描いた。

# 13.1-2
35の右下に36が入る。  
赤の場合：2色条件4に反するので2色木にならない。  
黒の場合：2色条件5に反するので2色木にならない。

# 13.1-3
2色木である。

# 13.1-4
黒節点の子が両方黒節点の場合は2。  
黒節点の子が片方赤節点の場合は3。  
黒節点の子が両方赤節点の場合は4。  
葉の深さはすべて等しくなる。

# 13.1-5
単純道の長さが最小値となるのは、その単純道上のすべての節点が黒である場合。  
単純道の長さが最大値となるのは、その単純道上において黒節点の出現頻度が最低である場合。すなわち、黒節点と赤節点が交互に存在する場合。  
最小値をnとすると、最大値は2nとなる。

# 13.1-6
最大値：2^2k-1  
最小値：2^k-1

# 13.2-2
基底：節点が1個の場合、可能な回転は0個。  
帰納：節点がk(≧1)個の場合に可能な回転がk-1個存在すると仮定する。節点を1つ増やすと、その節点はある節点の左の子か右の子となるが、左の子となる場合には可能な右回転の個数が1個増え、右の子となる場合には可能な左回転の個数が1個増える。すなわち、節点がk+1個の場合に可能な回転がk個存在する。

以上より、n(≧1)個の節点からなる任意の2分探索木では、ちょうどn-1個の可能な回転があることが示された。

# 13.2-3
a：1深くなる  
b：変わらない  
c：1浅くなる

# 13.3-1
2色条件5を維持できなくなるため？