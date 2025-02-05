#Data for the column chart (example: sales by region)
regions = ['North', 'South', 'East', 'West']
sales = [3500, 4200, 3000, 5500]
plt.bar(regions, sales, color='skyblue')
plt.title('Sales by Region')
plt.xlabel('Region')
plt.ylabel('Sales Amount ($)')
plt.show() 
