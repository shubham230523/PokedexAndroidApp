# PokedexAndroidApp 🎮⚡

A beautifully designed, high-performance Pokedex application for Android. This project leverages the **PokéAPI** to provide a comprehensive database of Pokémon, featuring high-quality images, detailed stats, and evolution chains. It serves as a showcase for modern Android development patterns including **Clean Architecture**, **MVVM**, and **Jetpack Compose**.

---

## 🎯 Project Purpose

The goal of this project is to demonstrate a "Real-World" implementation of a data-driven mobile app. It focuses on:
* **Efficient Data Fetching:** Handling paginated API responses from PokéAPI.
* **Image Caching:** Optimizing the loading of high-resolution Pokémon sprites for a smooth scrolling experience.
* **Modern UI/UX:** Using a declarative UI approach with Compose to create a dynamic and responsive interface.
* **Dependency Management:** Implementing **Hilt** for a clean, testable dependency injection graph.

---

## 🌟 Key Features

* **Complete Pokémon Directory:** Browse through a vast list of Pokémon with lazy-loading support.
* **Advanced Search & Filtering:** Quickly find Pokémon by name or index.
* **Detailed Stats View:** Interactive progress bars showing HP, Attack, Defense, and Speed.
* **Type-Based Theming:** The UI dynamically changes colors based on the primary type of the Pokémon (e.g., Fire is Red, Water is Blue).
* **Evolution Chains:** Visual representation of how a Pokémon evolves.
* **Offline Caching:** Basic support for viewing previously loaded Pokémon data without an active connection.

---

## 🏗 Architecture & Tech Stack

The app is built using the **MVVM (Model-View-ViewModel)** pattern to ensure a strict separation of concerns:

| Category | Technology |
| :--- | :--- |
| **UI Framework** | Jetpack Compose |
| **Networking** | Retrofit + OkHttp |
| **Dependency Injection** | Dagger Hilt |
| **Image Loading** | Coil / Glide |
| **Asynchronous Tasks** | Kotlin Coroutines & Flow |
| **Navigation** | Compose Navigation |

---

## 🚀 Improvements & Roadmap

* **Favorites System:** Allow users to "Heart" Pokémon and save them to a local Room database.
* **Comparison Tool:** A feature to compare stats between two different Pokémon side-by-side.
* **Voice Search:** Integration with Android Speech-to-Text for hands-free searching.
* **Animations:** Adding **Lottie** animations for loading states and transitions.

---

## 🤝 Contributing

Contributions are always welcome! Whether you want to fix a bug or propose a new feature:

1. Fork the Project.
2. Create your Feature Branch (`git checkout -b feature/NewFeature`).
3. Commit your changes (`git commit -m 'Add some NewFeature'`).
4. Push to the Branch (`git push origin feature/NewFeature`).
5. Open a Pull Request.

---

### 👨‍💻 Author
**Shubham**
* [GitHub](https://github.com/shubham230523)
