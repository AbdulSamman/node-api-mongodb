# Node/Express API with simple CRUD mongodb data source

If you need to set up a quick Node/Express API, this is a good project to begin with. It has a simple MVC structure with the server.ts file kept simple with the Express routes which call the corresponding functions in the model.ts file. This is one simple example of middleware, a logger which writes to a text file each time the API is accessed. The JSON file has more data than is needed so there is a light example of data cleansing from "raw books" to "book", see the IRawBook and IBook interfaces. As all my starter examples, this API uses TypeScript and ES6 modules exclusively. To add a new data source, simply change `model.ts` by swapping out the JSON-file code with code for your data source, e.g. a MongoDB or MySQL database, etc.
k to view website

- `npm run dev`
![node-api-mongodb](https://user-images.githubusercontent.com/97021586/219956761-6bdb8b2a-f717-4572-a825-6c9fc467a546.gif)
