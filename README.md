# Zero Exchange App

**Zero Exchange App** is an open‑source web interface for **Zero Exchange**, a fork of Uniswap that enables **cross‑chain liquidity between Ethereum and Avalanche**. This repository is based on the original implementation and focuses on maintaining clarity, developer‑friendliness, and ease of contribution.

---

## ✨ Highlights

* Cross‑chain liquidity support (Ethereum ↔ Avalanche)
* Built on a Uniswap‑based architecture
* Clean, modern frontend
* Styled and formatted using **Prettier**
* Lint and formatting friendly

---

## 🌐 Links

* **Website:** [https://0.exchange](https://0.exchange)
* **App:** [https://app.0.exchange](https://app.0.exchange)
* **Blog:** [https://blog.0.exchange](https://blog.0.exchange)
* **Twitter:** @OfficialZeroDEX
* **Email:** [hello@0.exchange](mailto:hello@0.exchange)
* **Discord:** Zero Exchange
* **Learn More:** [https://0.exchange](https://0.exchange)

---

## 🧑‍💻 Development

### Install Dependencies

```bash
yarn
```

---

### Run Locally

```bash
yarn start
```

The app will be available at:

```
http://localhost:3000
```

---

## ⚙️ Environment Configuration (Optional)

To set a default network when no wallet is connected:

1. Create a local environment file:

```bash
cp .env .env.local
```

2. Update the following variables in `.env.local`:

```env
REACT_APP_NETWORK_ID={YOUR_NETWORK_ID}
REACT_APP_NETWORK_URL=https://{YOUR_NETWORK_ID}.infura.io/v3/{YOUR_INFURA_KEY}
```

⚠️ **Important Notes**:

* The interface only works on **testnets** where **Uniswap V2** and **Multicall** contracts are deployed.
* Unsupported networks will not function correctly.

---

## 🤝 Contributions

Contributions are welcome and appreciated!

* Please open **all pull requests against the `master` branch**
* CI checks will automatically run on every PR
* Follow the existing code style and ensure formatting passes

---

## 📜 License

This project is open‑source and available under its respective license. See the `LICENSE` file for details.

---

## 🙏 Acknowledgements

* Inspired by **Uniswap**
* Built and maintained by the **Zero Exchange** community
