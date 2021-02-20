<img width="150" height="150" align="left" style="float: left; margin: 0 10px 0 0;" alt="DDPE" src="https://github.com/Androz2091/discord-data-package-explorer/raw/master/public/favicon.png">  

# [Discord Data Package Explorer](https://ddpe.netlify.app)

What is there **really** in your Discord Data package? And how can this data be useful? Discord Data Package Explorer does the job for you!

## Example

![Example](./example.png)

### Installation

Discord Data Package Explorer is built with **[Svelte](https://svelte.dev)**, and is quite easy to install.

* Clone the repository.
* Install the dependencies using `npm install` or `yarn install`.
* Start the app using `npm run dev` or `yarn dev`!

### ZIP Library

I decided to use zip.js instead of JSZip. Some benchmarks with the same package file:

| **Name** | **Time to read files** |
|----------|----------|
| Zip.js | **47 seconds** |
| JSZip | 123 seconds |
