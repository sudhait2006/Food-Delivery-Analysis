import pandas as pd
import matplotlib.pyplot as plt

data = {
    'Month': ['Jan', 'Feb', 'Mar', 'Apr', 'May'],
    'Orders': [120, 150, 180, 200, 250]
}

df = pd.DataFrame(data)

print(df)

plt.plot(df['Month'], df['Orders'])
plt.title('Food Delivery Orders Analysis')
plt.xlabel('Month')
plt.ylabel('Orders')
plt.show()
