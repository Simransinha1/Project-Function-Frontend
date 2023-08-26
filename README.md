# Ethereum Contract Application Using Hardhat Framework

## Project Overview

This project involves the creation of a simple Ethereum contract application, allowing users to interact with a contract deployed on the local Hardhat network. The contract includes functions for depositing and withdrawing funds, and these actions reflect on the application's frontend, built with Next.js.

## Getting Started

### Installation

1. Clone the repository to your local machine.

   Command Line:
   
   git clone <repository_url>
   

2. Navigate to the project folder.

   Command Line:
   
   cd <project_directory>
   

3. Install the project's dependencies.

   Command Line:
   
   npm install
   

### Running the Application

1. Open two terminals in your preferred code editor (e.g., Visual Studio Code).

2. In the second terminal, start the local Hardhat network.

   Command Line:
   
   npx hardhat node
   

3. In the third terminal, deploy the contract to the local network.

   Command Line:
   
   npx hardhat run --network localhost scripts/deploy.js
   

4. Return to the first terminal and launch the frontend application.

   Command Line:
   
   npm run dev
   

5. Open a web browser and go to `http://localhost:3000` to access the application.

## Assistance

If you encounter any issues or have questions, feel free to reach out to the creators.

## Authors

- Original Template: MetacrafterChris
- Creator: [Simran](mailto:21bcs3832@cuchd.in)

## License

This project is licensed under the [MIT License](https://license.md/).
