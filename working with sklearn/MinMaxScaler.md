# you should not do this thing when you train a model

    data = [[1,2,3,4,5,6,7,8,9,0], [0, 9, 8, 7, 6, 5, 4 ,3, 2, 1], [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]]
  
  
    data1 = data[0]
    data2 = data[1]
    data3 = data[2]
  
    mxs = MinMaxScaler(feature_range=(0, 1))
  
    mxs.fit_transform(data1)
    mxs.fit_transform(data2)
    mxs.fit_transform(data3)
  
## or

    data = [[1,2,3,4,5,6,7,8,9,0], [0, 9, 8, 7, 6, 5, 4 ,3, 2, 1], [0, 1, 2, 3, 4, 5, 6, 7, 8, 9]]
  
  
    for i in range(len(data))
      data1.append(data[i][0])
      data2.append(data[i][1])
      data3.append(data[i][2])
      data4.append(data[i][3])
      data5.append(data[i][4])
      data6.append(data[i][5])
      data7.append(data[i][6])
      data8.append(data[i][7])
      data9.append(data[i][8])
      data10.append(data[i][9])
      
  
    mxs = MinMaxScaler(feature_range=(0, 1))
  
    mxs.fit_transform(data1)
    mxs.fit_transform(data2)
    mxs.fit_transform(data3)
    mxs.fit_transform(data4)
    mxs.fit_transform(data5)
    mxs.fit_transform(data6)
    mxs.fit_transform(data7)
    mxs.fit_transform(data8)
    mxs.fit_transform(data9)
    mxs.fit_transform(data10)
