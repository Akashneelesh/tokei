# Tokei Contract

## 🛠️ Build

To build the project, run:

```bash
scarb build
```

## 🧪 Test

To test the project, run:

```bash
snforge test
```

## 🚀 Deploy
Note : [For Testing Purpose the credentials have been hardcoded and have not been put in an env - Be mindful while using]
        
To deploy the project on testnet, you need to:
- Change directory to stay in the main directory `tokei` folder
- Run the deployment script using `npx ts-node src/scripts/deployment.ts`
- And you will have a new deployed contract

## 🔬 Interaction
To interact with the existing contract, you need to :
### User Interaction
- To create a new stream with duration,
  - Run the interaction script using `npx ts-node src/scripts/user_interaction.ts`  
  - You will have ended up creating a new stream.
  - Similarly to interact with other user functionalities refer the user_interaction.ts

### Admin Interaction
- To set the protocol fee,
  - Run the interaction script using `npx ts-node src/scripts/admin_interaction.ts`
  - You will end up setting a new protocol fee for a given asset.
  - Similarly to interact with other user functionalities refer the admin_interaction.ts
        
## 📚 Resources

Here are some resources to help you get started:

- [Cairo Book](https://book.cairo-lang.org/)
- [Starknet Book](https://book.starknet.io/)
- [Starknet Foundry Book](https://foundry-rs.github.io/starknet-foundry/)
- [Starknet By Example](https://starknet-by-example.voyager.online/)
- [Starkli Book](https://book.starkli.rs/)

## 📖 License

This project is licensed under the **MIT license**. See [LICENSE](LICENSE) for more information.
