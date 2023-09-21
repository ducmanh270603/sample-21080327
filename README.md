# sample-21080327

## Finally done update image 
Time to go home

![](images/7529_KEKW.png)

### Wait
Attendance has not been taken yet

![](images/7285-kekwait.png)

import pandas as pd
import numpy as np
import matplotlib.pyplot as plt

labels=["North","East","West","South"]
yvals=[10,1,2,7]

nbars=len(labels)
y=np.arange(nbars)

plt.bar(labels,yvals, color='olive')
plt.plot()

plt.xlabel("Region")
plt.yticks(ticks=y)
plt.ylabel("Number of transactions")
plt.title("Company performance")
plt.show()
