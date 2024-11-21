# Boutique-online #

This is a demo backend server

### Prerequisites ###

You will need to have Node and `npm` installed locally on your machine.

### Installation ###

Clone this repo. From within the project folder, run `npm install`. You 
can then run the server with `node server`. 
The server should run on `localhost` with default port `3000`. If the
server runs on another port for any reason, this is printed to the
console when the server starts, e.g. `Listening on port 3001`.

### routes ###
cameras:
get all:
/routes/camera

get one
/routes/camera/:id

post
/routes/camera/order

 * Expects request to contain:
 * contact: {
 *   firstName: string,
 *   lastName: string,
 *   address: string,
 *   city: string,
 *   email: string
 * }
 * products: [string] <-- array of product _id

teddys:
/routes/teddy

furnitures:
/routes/furniture