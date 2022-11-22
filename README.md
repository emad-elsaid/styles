# Styles

Experimental CSS framework. It combines the basic utility classes of TailwindCSS and beautiful color palette of elementaryOS

This project is in a very early stage and subject to change

The goal so far:

- Have one CSS file output.
- Utility classes similar to TailwindCSS without the custom `rule-[custom-value]` syntax as it require JIT.
- The beauty of elementaryOS by providing extra CSS classes for that.

# Development

- `sass` directory include the source files. and the output is `styles.css` in the root.
- for building the project `cmd/build`
- for building while developing `cmd/watch`
