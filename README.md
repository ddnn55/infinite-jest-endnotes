# infinite-jest-endnotes

## Why

I borrowed a free audiobook copy of Infinite Jest via Libby, but the edition does not read the endnotes, it only reads the number of the endnote. This way, I can read the endnotes ergonomically on my phone while listening to the audiobook on the go.

## How

* I copy-pasted the endnotes from https://archive.org/details/InfiniteJest into a .txt file.
* `index.html`:
    * fetches the .txt file
    * detects where each endnote begins
    * puts each endnote in a `<p>`
    
Most likely some paragraph formatting present in the PDF is lost. And there may be other issues.

TODO
* train an LLM from scratch on only Infinite Jest for funsies?
* preserve paragraph formatting in original text
