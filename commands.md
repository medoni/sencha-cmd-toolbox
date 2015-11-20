# App
```
sencha app build                                # builds the app
sencha app build testing                        # builds as testing
```

# JavaScript
```
sencha ant refresh                              # refreshes javascript only
sencha ant -p build.environment=testing refresh # refreshes javascript only (testing)
sencha ant -p build.id=BUILDDESCR refresh       # refreshes a single build descriptor/profile
```

# Sass
```
sencha ant sass                                 # builds Sass (Theme)
sencha ant -p build.environment=testing sass    # builds Sass (Theme, testing) 
```

# Slicer
```
sencha ant slice
```

# Plumping
```
sencha diag show                                # Print sencha cmd values
sencha ant .props                               # Print all properties and there values
```