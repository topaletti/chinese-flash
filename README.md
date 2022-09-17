# Chinese Sentence Flash

I'd been learning Chinese for a few years and wanted a tool that would give me a steady influx of text with the option to adjust the difficulty of the material. I scraped the text used in this app (several thousand individual sentences and phrases with transcriptions and translations) from an online grammar wiki under a Creative Commons license and put the data into a JSON file, which the app fetches via JavaScript and unpacks into React components.

The app uses Babel to compile the JSX in `index.html` when you open the file in your browser, which is not how you would do it for serious apps because it would slow them down, but it makes deployment much easier and doesn't hurt with simple apps like this one.
