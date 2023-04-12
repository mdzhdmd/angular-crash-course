# Angular Crash Course 2021 (Task Tracker App)

This is the project from the [YouTube crash course](https://youtu.be/3dHNOWTI7H8 "Angular Crash Course 2021"). It includes the [Angular](https://angular.io/) ui as well as [JSON-Server](https://www.npmjs.com/package/json-server) for our mock backend.

## Usage

### Install dependencies

```
npm install
```

### Run Angular server (http://localhost:4200)

```
ng serve -o
```

### Run the JSON server (http://localhost:3000)

```
npx json-server --watch db.json
```

The port might be different, change url in `src/app/services/task.service.ts` if needed.