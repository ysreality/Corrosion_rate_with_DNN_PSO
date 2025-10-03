# Corrosion rate with DNN model and PSO optimize(Keras)

## Summary

運用深度類神經建立腐蝕率預測模型，使用Keras的架構，主要搭配relu活化函數，因為有數值過小容易失真，故再使用Leaky ReLU來加強數值訊號
並使用迭代搜尋法找出最佳參數組合，使得該訓練模型能有效地進行收斂

結果顯示，該模型的成效是優良的，但業主希望可以再降低誤差率，因此根據數篇文獻探討得知，使用PSO(粒子群演算法，Particle Swarm Optimization)能有效地改善類神經的權重
使得該模型的效能會有效提升，並降低其誤差程度，在實務的應用端可以有效的發揮其功用

