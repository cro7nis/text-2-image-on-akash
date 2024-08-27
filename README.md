# Text to Image on Akash Network

Text-to-image app powerered by [Playground v2.5 – 1024px Aesthetic Model](https://huggingface.co/playgroundai/playground-v2.5-1024px-aesthetic).

Its a clone from huggingface [space](https://huggingface.co/spaces/playgroundai/playground-v2.5) from [playgroundai](https://huggingface.co/playgroundai)

The project is developed for the **Run app similar to SDXL on Akash Network** zealy task which is hosted by [Akash](https://zealy.io/cw/akashnetwork/questboard).

## Deploy on Akash guide <img src="./assets/akash-logo.png" alt="drawing" width=20 height=20/>



https://github.com/user-attachments/assets/c4b4d269-a9c7-4cea-b166-d51d83d473b9



- Create and fund a Keplr or Leap wallet
  - [Keplr wallet](https://akash.network/docs/getting-started/token-and-wallets/#keplr-wallet)
  - [Leap wallet](https://akash.network/docs/getting-started/token-and-wallets/#leap-cosmos-wallet)
- Visit https://deploy.cloudmos.io/
- Connect your wallet
  - You need to have at least 0.5 AKT in your wallet
- Press the deploy button
- Select "Build your template"
- (Optional) Name your deployment
- Select YAML and paste the [deploy.yaml](deploy.yaml) contents
- Press "Create Deployment"
- Accept wallet transaction
- Review bids and select provider
- Accept provider transaction
- Go to LEASES and press the URI
- Check the [Akash docs](https://akash.network/docs/deployments/cloudmos-deploy/) if you have and questions
- Start generating speech!
  - Add the input text for speech generation
  - Provide a description of the speaker to adapt the generated voice
