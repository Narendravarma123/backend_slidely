



## Installation


Step:1

1.Clone this repository with the following command
```bash
  git clone https://github.com/Narendravarma123/backend_slidely.git
```

2.Make sure to put the name of the folder 
```bash
express_backend
```

3.Make sure you have the compatible versions of the Node j.s and Express js versions in your laptop
``` bash
Example:Express.js Compatibility with Node.js:
Express.js v4 is compatible with Node.js v10.15.3 and newer1.
If you’re using Express.js, you can safely use Node.js versions 10.15.3 and above.
```
4.Run the following command in your terminal in the folders path
```bash
npm install express body-parser cors typescript ts-node @types/node @types/express 
```

5.Now you have all with you.Its time to run the server
```bash
npm start
```

After running this command the server starts with the port number 3000 and all the submitted data by the front end will be stored in the db.json file existed in the folder.


6.For the json file I used the following structure
```bash
[
  {
    "id": 1,
    "Name": "karthik",
    "Email": "karthik@gmail.com",
    "Phone": "8143628288",
    "GitHub": "www.gogle.com",
    "Time": "00:00:03",
    "Timestamp": "2024-06-20T11:34:17.834Z"
  },
  ]

```
Even though the delete and edit operations are working for the server i can't be able to do it with front end using visual basic.
    
