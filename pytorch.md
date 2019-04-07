# How to load data from txt
```javascript
import matplotlib.pyplot as plt
import numpy as np
data = np.loadtxt("loss_list.txt")
plt.plot(data)
plt.show()
```
# 动态画图
```javascript
plt.ion()
plt.cla()

plt.plot()
plt.plot()

plt.ioff()
plt.show()
```
# save&load pytorch model
```javascript
torch.save(net.state_dict(), './net.pkl')
创建一个网络名为net以后
net.load_state_dict(torch.load('./cnn.pkl'))
```
