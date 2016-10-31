# spa-webserver
A dev webserver that redirects non-existent files to the nearest index.html. 
This allows for SPA-style client-side navigation. 

## Install
```
npm install spa-webserver --save
```

## Use
```
spa-webserver -d './build'
```

Opts:
- `-d`: root directory (defaults to ./)
- `-p`: port (defaults to process.env.PORT)


## License

Released under an MIT license.

## Related
- [link-react](https://github.com/thinkloop/link-react/): A generalized link <a> component that allows client-side navigation while taking into account exceptions

## Other
- [memoizerific](https://github.com/thinkloop/memoizerific/): Fast, small, efficient JavaScript memoization to memoize JS functions
- [todo-app](https://github.com/thinkloop/todo-app/): Example todo app of extreme decoupling of react, redux and selectors

## Like it? Star It
