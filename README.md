# Medicine-repository-

## set up the needed libraries


```npm install -g npm@10.9.0```


## create new react project

```npx create-react-app my-react-app --template typescript```
or

```yarn create react-app my-react-app --template typescript```

## start the project
```npm start```

This will lead to this port:

```http://localhost:3000/```

## set up the structure of the dirs
```
my-react-app/
├── node_modules/
├── public/
├── src/
│   ├── components/
│   │   └── GanttChart.tsx
│   ├── App.tsx
│   ├── index.tsx
│   └── ...
├── package.json
├── tsconfig.json
└── ...

```


``` node -r dotenv/config dist/index.js --experimental-specifier-resolution=node ```
