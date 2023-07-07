This is a [Next.js](https://nextjs.org/) project 
Bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started
add your OpenAI API key found [here](https://platform.openai.com/account/api-keys) in _.env_ File

### Prerequisites

- [Node.js](https://nodejs.org/en/download/)
- [Yarn](https://classic.yarnpkg.com/en/docs/install/#mac-stable)
- `wget` (on macOS, you can install this with `brew install wget`)



Ingest/Load our data source.


change PDF to md.
change variable  _FILENAME_ in _ingest.ts_ 


Next, 
install dependencies 
>>> yarn
saved yarn.lock file

Run the ingestion script:
>>> yarn ingest
will parse the data, split text, create embeddings, store them in a vectorstore, and then save it to the `data/` directory.


### run the development server
>>> yarn dev

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

