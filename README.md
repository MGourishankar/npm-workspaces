# npm-workspaces

Workspaces help us setup monorepo/micro-frontend architecture in JS project. Workspaces are usually defined via the workspaces property of the package.json file, e.g:

`"workspaces": [
    "packages/*",
    "apps/*"
],`

# build
`npm run build` at root

# run app1
`cd apps/app1`
`npm run start`

output - Hello from App1


# run app2
`cd ../.. && cd apps/app2`
`npm run start`

output - Hello from App2