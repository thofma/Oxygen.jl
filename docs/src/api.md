# Api

Documentation for Oxygen.jl

## Starting the webserver
```@docs 
serve
serveparallel
```

## Routing 

```@docs
@get(path, func)
@post(path, func)
@put(path, func)
@patch(path, func)
@delete(path, func)
@route(methods, path, func)

get(path, func)
post(path, func)
put(path, func)
patch(path, func)
delete(path, func)
route(methods, path, func)
```

## Mounting Files
```@docs
@staticfiles
@dynamicfiles
staticfiles
dynamicfiles
file
```

## Autogenerated Docs
```@docs
configdocs
enabledocs
disabledocs
isdocsenabled
mergeschema
setschema
getschema
enabledocs
disabledocs
isdocsenabled
```

## Helper functions 
```@docs 
queryparams
html
text
json
binary
```

## Repeat Tasks & Cron Scheduling
```@docs 
@cron
starttasks
stoptasks
startcronjobs
stopcronjobs
```

## Extra's
```@docs 
router
internalrequest
redirect
terminate
resetstate
```