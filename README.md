# Meta Tags
This class is used for generating meta tags.

### Initializing Class 
Initializion of the class can be done in two ways

```
$meta = new Meta;
$meta->charset('UTF-8');
```

The class can also be initialized with the charset type

```
$meta = new Meta('UTF-8');
```


### Sample Usage
When we store a list of meta attributes values, we can export the data to view the content.

```
$meta->name('viewport', 'width=device-width, initial-scale=.9, maximum-scale=1.0, user-scalable=1');
$meta->name('description', 'website_description');

$meta->export(); 
```

In order to return the generated tags, rather than use the "export()" method, we have to use the "dump()" instead which will add the html meta tags into the web page as shown below.

```
$meta->name('viewport', 'width=device-width, initial-scale=.9, maximum-scale=1.0, user-scalable=1');
$meta->name('description', 'website_description');

$meta->dump(); 
```

#### Methods
charset
drop
dump
equiv
export 
link
name
og
prop
refresh
samples

#####Notice
For more information on how to use class, visit the attached documenation.

