SETUP THE PROJECT 
(https://learn.figment.io/tutorials/setup-the-project)
-------------------------------------
Let's setup the project to connect & interact with the Solana blockchain.
The following software is required to set up and complete the Solana Pathway.
  - git installed
  - NodeJS v14.17.0 or higher installed
  - yarn installed
Star cloning the repository and instaling the dependencies with yarn.
`
$ git clone https://github.com/figment-networks/learn-web3-dapp.git
$ cd learn-web3-dapp
$ yarn
`

# Set your API Key
Create an .env.local file at the root of the directory. Copy and paste the contents of the existing .env.example into the new file and save it to disk (alternatively, you can rename .env.example).
The value for DATAHUB_SOLANA_API_KEY can be found on the DataHub Services Dashboard. Click on the Solana icon in the list of available protocols and then copy your key as shown below. You can now paste your personal API key into .env.local . This will authenticate you and enable you to make JSON-RPC requests to the Solana cluster via DataHub.