# lein-deploy-uberjar

This a simple lein plugin that will take a built uberjar and deploy it to a
defined repository in the project.

# Example:

Add this to your plugins section in your project.clj

```clojure
[camechis/deploy-uberjar "0.2.0"]
```

Set uberjar-name 
```
:uberjar-name "your-standalone.jar"
```

The following will deploy the uberjar to the release repository

```
lein deploy-uberjar release
```
