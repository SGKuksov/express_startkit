# Express application generator

Use the application generator tool, express-generator, to quickly create an application skeleton.
The express-generator package installs the express command-line tool. Use the following command to do so:

```bash
npm install express-generator -g
```

Create new project:
```bash
express --css <engine> --git --pug <dir>
```

Install dependencies:
```bash
cd myapp
npm install
```

On MacOS or Linux, run the app with this command:
```bash
DEBUG=myapp:* npm start
```

On Windows, use this command:
```bash
set DEBUG=myapp:* & npm start
```