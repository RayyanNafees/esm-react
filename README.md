# ESM React

Running a React Application without a bundler like `create-react-app` or `create-vite` or installing any library into `node_modules` but just simply using CDNs

## Running the application
Add your entry file, suppose `main.tsx` into the html as `type="module"`

Add this into your index.html inside the root of your project
```html
<script type="module" src="path/to/main.tsx"></script>
```

Then run the index.html in the root by simply running

```sh
npx vite
```

> Powered by [ems.sh](https://code.esm.sh)
