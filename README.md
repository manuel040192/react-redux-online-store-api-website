https://celadon-salmiakki-0c0e8b.netlify.app/

**Información destacada:**

- El reducer de productos contiene una action que toma el estado existente con ...state y añade un payload que contiene productos con products: payload.

- Se obtienen datos de un servidor, se envía una action y luego se actualiza la store con los datos del servidor.

- En la sección de return de un hook useEffect, se colocó lo que se desea que suceda cuando un componente es desmontado, lo cual en este caso fue el remover a un producto de un estado, para que éste no aparezca por un instante antes de que cargue un producto que fue seleccionado después de que otro fue seleccionado y que luego se volviera a la página de productos.

- El reducer de productos seleccionados contiene una action que retorna un objeto vacío, lo cual hace que se vacíe el estado de productos seleccionados.

**Highlighted information:**

- The products' reducer contains an action that takes the existing state with ...state and adds a payload that contains products with products: payload.

- Data is obtained from a server, and an action that contains that data in a payload is dispatched, and then the store is updated with the data of the server.

- In the return section of a useEffect hook, it was placed what is wanted to happen when a component is unmounted, which in this case was to remove a product from a state, so that it doesn't show on the screen for an instant before a product that was selected is loaded after another one was selected and then a user has gone back to the products' page. 

- The selected products' reducer contains an action that returns an empty object, which makes the selected products' state become empty.
