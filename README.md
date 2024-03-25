# mermaid-gdocs
[Mermaidsjs](https://mermaidjs.github.io/) wrapper for google docs.

Installed for Smartly.io google org by default. 
 * The script is deployed [here](https://docs.google.com/document/d/1rWbQdhUmCmLRzoHYSBfhC_txTWxie6ofEspoJigKQaU/edit),
 * Google project [here](https://console.cloud.google.com/apis/api/appsmarket-component.googleapis.com/credentials?authuser=0&project=fast-drake-418308)

# known limitations

- only inline images work in google docs
- google slide not supported
- icons (fontawesome) not supported
- seems to bug with google chrome on mac

# Development setup

To test the editor ui outside of google docs, serve the src folder, for example `npx http-server src` and open http://127.0.0.1:8080 in your browser.

`src/Code.gs` is a copy of what's running in apps script, same for  `src/appsscript.json`. 


# License : MIT

Do whatever you want with this code, but i'm not responsible if it breaks. I'm trying to publish it on the google apps store so that people can use it in their google docs
