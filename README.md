# ProofPost

ProofPost is a messaging platform designed for security and privacy, harnessing the Mina Protocol's zero-knowledge proof system. It ensures user conversations remain private and secure, with the additional benefit of blockchain-based authentication.

## Features

- **End-to-End Encrypted Messaging**: Users can send and receive messages with the confidence that all communications are secure and private.
- **Blockchain-Based Authentication**: The Mina Protocol is used to authenticate users securely, without revealing sensitive personal data.
- **Privacy by Default**: User identities are verified through zero-knowledge proofs, ensuring anonymity and privacy.
- **Immutable Message Records**: Messages are timestamped and recorded on the Mina blockchain, providing an immutable history of communication.
- **User-Friendly Web Interface**: A clean and intuitive web interface for a seamless messaging experience.
- **Decentralized Operation**: There's no central point of control or failure, making the platform resilient and censorship-resistant.
- **Onboarding with Ease**: New users can quickly set up an account and start messaging with minimal barriers.

## How It Works

### User Registration and Login

- Users create an account on ProofPost, generating a unique cryptographic identity.
- During login, the user identity is authenticated via a zero-knowledge proof without exposing any private credentials.

### Sending and Receiving Messages

- **Sending**: Messages are encrypted client-side and sent with a zk-SNARK (Succinct Non-interactive ARgument of Knowledge) to prove the sender’s identity without revealing it.
- **Receiving**: Upon receiving, messages are decrypted by the recipient, and the zk-SNARK is verified to ensure the message’s integrity and sender's authenticity.

### Blockchain Interaction

- ProofPost interacts with the Mina blockchain by submitting proofs for each message sent, ensuring that all communication is recorded and verifiable without compromising privacy.

## Getting Started

To run ProofPost locally or contribute to its development, follow these steps:

### Prerequisites

- Node.js >= 14.x
- Yarn or npm package manager
- Access to a Mina Protocol node (local or remote)

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/proofpost.git
   cd proofpost
   ```

2. Install the dependencies:
   ```sh
   npm install
   # or
   yarn install
   ```

3. Set up environment variables:
   Create a `.env` file in the root directory and add the following:
   ```plaintext
   MINA_ENDPOINT=<mina_protocol_node_endpoint>
   ```

### Running ProofPost

1. Start the ProofPost application:
   ```sh
   npm run start
   # or
   yarn start
   ```

2. Navigate to `http://localhost:3000` in your web browser to use the app.

## Testing

To run the test suite:

```sh
npm run test
# or
yarn test
```

## Deployment

For deployment purposes, you can build the app using:

```sh
npm run build
# or
yarn build
```

This command will create a `build` directory with all the compiled assets ready for deployment to a web server.

## Contributing

Please read [CONTRIBUTING.md](CONTRIBUTING.md) for details on our code of conduct and the process for submitting pull requests.

## Versioning

We use [Github](http://github.com/) for versioning.

## Authors

- **Quality Apps** - *Initial work* - [DevQAPPs](https://github.com/DevQAPPs)

## License

This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## Acknowledgments

- 

---
