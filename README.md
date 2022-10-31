# Artificial-Neural-Network-for-Gas-Classification

## 📝 Table of Contents

- [About](#about)
- [How does it work](#work)
- [Authors](#authors)

## 🧐 About <a name = "about"></a>

My first Artificial Neural Network which is capable of multi-gas classification. This proeject is developed for self-learning purposes

This ANN can classify if the following gases are present with 91% accuracy:
- Hydrogren
- Formaldehyde
- Toluene
- Nitrogen Dioxide



## 🚀 How does it work <a name = "work"></a>:
Following are the steps taken to build the ANN model:

- Step 1: Gas sensor detects gas concentration, humidity and temperature, then stores the data to MongoDB database through Arduino board
- Step 2: User accesses the dashboard, and send a request to the backend
- Step 3: Backend API processes the request
- Step 4: Backend script is executed, send a request to the database
- Step 5: The requested data is sent back to backend
- Step 6: Requested data is sent back to the frontend, and being displayed on the dashboard 

### 📥 **Components** 
 - Python
     - [PyTorch](https://pytorch.org/)
     - [Pandas](https://pandas.pydata.org/)


## ✍️ Authors <a name = "authors"></a>

- [@Jason Wong](https://github.com/jason2134)

