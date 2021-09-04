# dvachecker
DVA checker



## ランドルト環の画像について.

ランドルト環のsvg 画像は, 画像のサイズを100とすると, 切れ目のサイズが20です.
視力は, 切れ目を分単位の視角で表したものの逆数です.
画像の実サイズを C [m], 画像までの距離を L [m]としたとき, 次で表せます:
`10800/(\pi * \arctan(0.2 C/L))`

$$ \frac{10800}{\pi\arctan(\frac{C}{5L})} $$

(ただし, \arctan は, アークタンジェントで値の単位は[rad]であること, CもLも 同じ単位 [m] であることに注意してください. \piは円周率です.)



逆に, 距離L[m]だけ離れた場所から視力Vを計測するためのランドルト環の画像サイズは, 次で表せます:
`5L \tan(10800/(\pi V))`

$$ 5L \tan(\frac{10800}{\pi V})$$

(ただし, \tanは, 引数に[rad]をとる正接関数です.)