# editor-picoc

This is an online **C-editor** that uses a **client-side compiler (picoc)**.  
  
[Demo](https://editor-picoc.glitch.me/)  
  
![editor-client-side](preview.gif "editor-client-side")  
  
I used some great techniques and frameworks such as *Emscripten*, [picoc-js](https://www.npmjs.com/package/picoc-js) and [Monaco](https://microsoft.github.io/monaco-editor/) in this project.  
Because it is small and suitable for our requirements, we opted for the [picoc](https://gitlab.com/zsaleeba/picoc) interpreter from *Zik Saleeba*. Special thanks to *Krithik Rao* for recompiling *picoc* to WASM.  
Feel free to customize the interpreters or programming languages that have been used.

## installation

Install the following javascript runtime and container virtualization tool.
- [Node.js](https://nodejs.org/en/download/)
  
Download all required dependencies and start *Node.js*.
  
```
npm install
npm start
```