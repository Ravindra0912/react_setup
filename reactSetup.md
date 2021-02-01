#React setup 

1. npm init
2.  npm install react react-dom (this adds node_modules you don’t need to add node_modules you just have to have a package.json file on which you can install and node_modules get added)
3.  npm intall @babel/code @babel/preset-env(transpiles modern js code to older js code for compatability) @babel/preset-react(JSX->Vanilla react) babel-loader(connects babel to webpack)
    4. create a .babelrc file
        1. add to the file:
            1. {
                1. “presets”:[@babel]
            2. }