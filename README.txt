this boiler plate is all current and contains:
create-react-app(react + node + development tools like webpack)
electron
electron-builder

this package is configured for yarn.

to start dev server use command "yarn dev"
this will give you an auto updated electron window to show your code as you type using webpack.

build react app as normal

when ready to compile for distribution type "yarn dist"
this command auto builds the project and then packs it up into an installer using electron-builder. 