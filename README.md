# 0 - Introduction

Install all pachage in each folder

# 1 - Launch the the folder backend: npm start

# 2 - In the browser, launch the page - http://localhost:9000/graphql - in the graphql server, in front of the address bar, there is a gear icon (click it), enable the subscription with graphql-ws, and run the query:

    subscription{

transactionAdded {
id
from
to
gas
gasPrice
value
nonce
}
}

You can see the result in the state of subcrpiton to green.

# 2 - launch the the folder client: npm start

# 3 - launch the folder node-web3-listen-events: node index.js

# 4 - refresh the page http://localhost:3000/
