Using the CLI

Instale Foundation con este comando:

	npm install foundation-cli --global

cd skeleton_gulp_mailing
	npm install

Build Commands

Para iniciar el proceso de construcción. Se abrirá una nueva pestaña de explorador con un servidor que apunte a los archivos del proyecto.

	npm start

Para en línea su CSS en su HTML junto con el resto del proceso de la estructura.

	npm run build 

Genera un archivo zip de produccion.

	npm run zip

src->assets->scss->_settings.scss

"Por default el mailing tendra un width de 680px"

	_settings.scss
	$global-width: 680px;
	