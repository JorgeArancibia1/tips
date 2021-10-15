# Agregar fuentes de font Awesome a tu proyecto de React.js

1. Agrega los siguientes comandos:

- `npm i --save @fontawesome/fontawesome-svg-core`
- `npm install --save @fontawesome/free-solid-svg-icons`
- `npm install --save @fontawesome/react-fontawesome `

2. Importa o agrega el componente de FontAwesome con la siguiente línea de código:

- `import { FontAwesomeIcon } from "@fortawesome/react-fontawesome";`

3. Importa o agrega el icono que quieres utilizar de la siguiente manera:

- `import { faSignOutAlt } from "@fortawesome/free-solid-svg-icons";`

3. Por último aplica el componente en tú código de la siguiente manera:

- `<FontAwesomeIcon icon={faSignOutAlt}></FontAwesomeIcon>`

## Llevado a un ejemplo, se vería de la siguiente manera:

```
import React from "react";
import { FontAwesomeIcon } from "@fortawesome/react-fontawesome";
import { faSignOutAlt } from "@fortawesome/free-solid-svg-icons";

export const Navbar = () => {
	return (
		<div className="navbar navbar-dark bg-dark mb-4">
			<span className="navbar-brand">Jorge</span>

			<button className="btn btn-outline-danger">
				<i class="fas fa-sign-out-alt"></i>
				<FontAwesomeIcon icon={faSignOutAlt}></FontAwesomeIcon>
			</button>
		</div>
	);
};
```

De esta forma podrás agregar íconos gratuitos de Font Awesome a tu proyecto. :smile:
