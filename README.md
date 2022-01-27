# MindOS

## Commands needed

Run development server at [http://localhost:8080/](http://localhost:8080/)...

```
npm run dev
```

Build Website

```
npm run build
```

Deploy online

```
rsync -avze ssh "/mnt/x/Data/www/Sites/mindos/mindos.in/_site/" mindos@mindos.in:"/home/mindos/public_html/"
```