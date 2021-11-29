# NgrxExample

### 1.) Install store

> With reducer/action ties built in (doesn't work)

`npm install @ngrx/store --save --minimal false`

> * Create a src/app/reducers folder, unless the statePath flag is provided, 
in which case this would be created based on the flag.

> * Create a src/app/reducers/index.ts file with an empty State interface, 
an empty reducers map, and an empty metaReducers array. This may be created 
under a different directory if the statePath flag is provided.

> * Update your src/app/app.module.ts > imports array with StoreModule.forRoot(reducers, { metaReducers }). 
If you provided flags then the command will attempt to locate and update module found by the flags.

### Auto Store setup also (doesn't work)

`ng generate store State --root --state-path store --module app.module.ts`
> https://ngrx.io/guide/schematics/store

##

### 2.) Just copy rest from this site 😂

https://stackblitz.com/angular/xbdxjlqgpyq?

> Install redux-dev tools in chrome

> And also within the project

`npm install @ngrx/store-devtools`

