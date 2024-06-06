# NFT Minting Project

A simple JavaScript project for minting NFTs, displaying their metadata, and tracking the total supply. Configured to run in a Gitpod environment.

## Description

This project provides a basic framework for managing Non-Fungible Tokens (NFTs) using JavaScript. It includes functionalities for minting new NFTs, displaying their metadata, and tracking the total supply of minted NFTs. The project is set up to run seamlessly in a Gitpod environment, making it easy to get started with NFT development.

## Getting Started

### Prerequisites

- Node.js installed on your local machine or access to Gitpod for an online development environment.

### Installation

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/nft-minting-project.git
    ```

2. Navigate into the project directory:
    ```bash
    cd nft-minting-project
    ```

3. Open the project in Gitpod by navigating to:
    ```
    https://gitpod.io/#https://github.com/your-username/nft-minting-project
    ```

### Usage

The main functionality of the project is contained within the `playground.js` file.

1. **Minting NFTs**:
    - Use the `mintNFT` function to create new NFTs.
    - Example usage:
    ```javascript
    mintNFT("Mona Lisa", "Leonardo da Vinci", 1503, "A portrait of a woman with a mysterious smile.");
    mintNFT("Starry Night", "Vincent van Gogh", 1889, "A depiction of a night sky filled with swirling stars.");
    mintNFT("The Scream", "Edvard Munch", 1893, "An expressionist depiction of anxiety and existential dread.");
    ```

2. **Listing NFTs**:
    - Use the `listNFTs` function to display the metadata of all minted NFTs.
    - Example usage:
    ```javascript
    listNFTs();
    ```

3. **Getting Total Supply**:
    - Use the `getTotalSupply` function to print the total number of minted NFTs.
    - Example usage:
    ```javascript
    getTotalSupply();
    ```

### Example Code

Here's an example of how the functions can be used together:

```javascript
// Minting example NFTs
mintNFT("Mona Lisa", "Leonardo da Vinci", 1503, "A portrait of a woman with a mysterious smile.");
mintNFT("Starry Night", "Vincent van Gogh", 1889, "A depiction of a night sky filled with swirling stars.");
mintNFT("The Scream", "Edvard Munch", 1893, "An expressionist depiction of anxiety and existential dread.");

// Listing all NFTs
listNFTs();

// Printing the total number of NFTs minted
getTotalSupply();
