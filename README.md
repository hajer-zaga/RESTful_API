# RESTful API with Express

## Introduction

In this project, I have developed an application programming interface (API) for a web server that stores and modifies information about chilies :hot_pepper: (represented by a JSON object). Through the API, the client will be able to implement CRUD functionality (Create, Read, Update and Delete) on the chilli objects stored in the web application. This functionality is implemented using the HTTP protocol.


## Getting Started 🙂

To get started with the project, follow these steps:


1. **Download and open the repository**: Download the repository to your local machine and open it in your preferred code editor.

2. **Open the project in VSCode**: Launch Visual Studio Code (VSCode) and open the project folder.

3. **Install all the packages we require**: Open a new terminal window in VSCode and enter this command.
```
npm i
```

4. **Run the client**: In the same terminal window, run the following command to start the client:

```
node client.js
```

You should see 'Listening on port 3000' in the terminal.


5. **Run the server**: Open a new terminal window in VSCode and run the following command to start the server:

```
node server.js
```

You should see 'Listening on port 3001' in the terminal.


6. **Yup! you successfully run the project**: 👏

You can access the client at <http://localhost:3000> and interact with the server.


The Client App ![Reference Image](/screenshots/fig2.png)


## Testing 🧐

Now we can test our server through the client application!
Lets create a couple new chillis! Here I’ve created 3.


- Chillis 1 : {Name: Chipotle Pepper} {Country: Mexico} {Heat: 2500}
- Chillis 2 : {Name: Cayenne Pepper} {Country: French GUyana} {Heat: 50000}
- Chillis 3 : {Name: Devils Tongue Pepper} {Country: USA} {Heat: 250000}


![Reference Image](/screenshots/fig3.png)
![Reference Image](/screenshots/fig4.png)
![Reference Image](/screenshots/fig5.png)


After adding the 3 chilies, you can test the others CRUD functionality of this API:

- To add a new item, use the ADD button. 
- Press the FETCH button to display the list of items that have been added. 
- Use the UPDATE button to modify an item, 
- The REMOVE button to delete an item. 
- You can verify the deletion, addition, or modification by pressing the FETCH button again.


#### You can be assured that each of your posts/additions received a 200 OK status, indicating a successful response. 👍

