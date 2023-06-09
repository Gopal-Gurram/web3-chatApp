# Backend Setup

Clone this repository onto your local machine.

Navigate to the backend directory.

Open the [.env] file in your text editor and replace the [API_KEY] and [PRIVATE_KEY] fields with your own values.

Run the following command to install the necessary packages:

`npm install`

```shell
npx hardhat help
npx hardhat test
REPORT_GAS=true npx hardhat test
npx hardhat node
```

Run the following command to compile and deploy the smart contract to the Mumbai test network.

`npx hardhat run --network mumbai scripts/deploy.js`

Save the [`CONTRACT_ADDRESS] for frontend.

## Frontend Setup

Navigate to the frontend directory.

Open the [src/App.js] file in your text editor.

Replace the [CONTRACT_ADDRESS] field with the contract address you copied from the previous step.

Run the following command to install the necessary packages:

`npm install`

Run the following command to start the application:

`npm start`

Open your web browser and navigate to [http://localhost:3000](http://localhost:3000) to view the application.
