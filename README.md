# labpro
from pandas import read_csv
from matplotlib import pyplot
series=read_csv("daily-total-female-births.csv")
print(series.head())
series.plot()
pyplot.show()
![image](https://github.com/user-attachments/assets/3d9d3264-19eb-4fdc-bec6-bc99cf1b89bf)
series.plot(style='-.')
pyplot.show()
![image](https://github.com/user-attachments/assets/b773d5b2-96cf-42ee-9b4d-3ac4b4543c07)
series.hist()
pyplot.show()
![image](https://github.com/user-attachments/assets/4af9cd9e-f1c1-49ff-a49c-40275a136033)
series.plot(kind='kde')
pyplot.show()
![image](https://github.com/user-attachments/assets/a94c03e6-dcb6-4a33-b1b0-5435c66df396)



