# Crypto Master
## A crypto searching application made with react, bootstrap and axios
### We are using Crypto Gecko API to get data about coins.

## Preview
![cryptomaster](https://user-images.githubusercontent.com/116850173/200366976-dcd89624-4071-4070-9f1d-9a3e61c0c9ce.gif)

### Searching Coins
The input in the search bar is a controlled component the reason why it's a controlled component and not just assigned with a ref is because
we want to update the list of the mapped search result on every letter we type.
We make a get request after we type more than 2 letters on the search bar. This prevents trying to load every coin containing the first letter you type from the API.<br>

![image](https://user-images.githubusercontent.com/116850173/200369232-9226db6d-8fb5-4afd-9dca-56fcdb4ff4bb.png)

### Pages
By clicking the buttons that are below and above the coin list you can change what gets mapped in the screen.
The moment you change the page you are on you make a get request from the api with the current page number that we are in right now.

<br> ![image](https://user-images.githubusercontent.com/116850173/200369715-10c51d97-edfe-4533-8a1e-2ad029747769.png)

