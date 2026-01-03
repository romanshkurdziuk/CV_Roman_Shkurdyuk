# Hi, I'm Roman Shkurdziuk 👋

<p align="center">
  <em>A C++ Systems Developer specializing in Multithreading, IPC, and Performance.</em>
</p>

---

I am a developer passionate about building efficient and reliable software systems. I enjoy diving into the low-level aspects of operating systems to write fast and predictable code. My strong suit is hands-on experience in solving classic synchronization and inter-process communication challenges using the **Windows API**.

- 🔭 **Core Specialization:** Systems Programming in C++ on the Windows platform.
- 🌱 **Key Interests:** Concurrency, Inter-Process Communication (IPC), Software Architecture.
- 💡 **My Approach:** I focus on writing clean, testable code using modern tools like CMake and GoogleTest.

---

### 🛠️ Tech Stack & Skills

<table>
  <tr>
    <td align="center" width="180">
      <strong>Languages</strong>
    </td>
    <td>
      <a href="https://isocpp.org/" target="_blank"><img src="https://img.shields.io/badge/C++-17-blue.svg?style=for-the-badge&logo=c%2B%2B"></a>
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Systems Programming</strong>
    </td>
    <td>
      <img src="https://img.shields.io/badge/Windows_API-Win32-0078D6.svg?style=for-the-badge&logo=windows">
      <img src="https://img.shields.io/badge/Multithreading-orange?style=for-the-badge">
      <img src="https://img.shields.io/badge/IPC-blueviolet?style=for-the-badge">
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Synchronization Primitives</strong>
    </td>
    <td>
      <code>Mutex</code>, <code>Semaphore</code>, <code>Event</code>, <code>Critical Section</code>
    </td>
  </tr>
    <tr>
    <td align="center">
      <strong>Algorithms & Data Structures</strong>
    </td>
    <td>
      <code>Dijkstra</code>, <code>DFS/BFS</code>, <code>Dynamic Programming</code>, <code>Segment Trees</code>, <code>DSU</code>, <code>BST</code>
    </td>
  </tr>
  <tr>
    <td align="center">
      <strong>Tools & Toolchain</strong>
    </td>
    <td>
      <img src="https://img.shields.io/badge/CMake-064F8C.svg?style=for-the-badge&logo=cmake">
      <img src="https://img.shields.io/badge/Git-F05032.svg?style=for-the-badge&logo=git&logoColor=white">
      <img src="https://img.shields.io/badge/GoogleTest-4285F4.svg?style=for-the-badge&logo=google&logoColor=white">
      <img src="https://img.shields.io/badge/VS_Code-007ACC.svg?style=for-the-badge&logo=visual-studio-code&logoColor=white">
    </td>
  </tr>
</table>

---

### 📊 GitHub Stats

<p align="center">
  <a href="https://github.com/romanshkurdziuk">
    <img height="180em" src="https://github-readme-stats.vercel.app/api?username=romanshkurdziuk&show_icons=true&theme=dracula&count_private=true&include_all_commits=true" />
    <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=romanshkurdziuk&layout=compact&theme=dracula" />
  </a>
</p>

---

### 🚀 Featured Projects

<details>
  <summary><strong>🔗 Client-Server System via Named Pipes (OS Lab 5)</strong></summary>
  
  *   **Description:** A multithreaded server and client application for remote access to a binary file. Implemented a locking mechanism for safe concurrent operations.
  *   **Key Technologies:** `C++17`, `Windows API`, `Named Pipes`, `CreateThread`, `Mutex` (implicitly via locking logic).
  *   **Architecture:** The server handles each client in a dedicated thread, ensuring high responsiveness.
</details>

<details>
  <summary><strong>🚦 Thread Synchronization Simulator (OS Lab 3)</strong></summary>
  
  *   **Description:** An application that simulates a thread race for a shared resource (an array) and implements a mechanism for manual **deadlock** resolution.
  *   **Key Technologies:** `C++17`, `WinAPI`, `Critical Section`, `Events`, `RAII (ScopedLock)`.
  *   **Architecture:** The core logic is encapsulated in a dedicated controller class, with `main` serving only as an entry point.
</details>

<details>
  <summary><strong>🔄 Inter-Process Communication via Ring Buffer (OS Lab 4)</strong></summary>
  
  *   **Description:** A messaging system between multiple sender processes and a single receiver process via a shared file organized as a **ring buffer (FIFO)**.
  *   **Key Technologies:** `C++17`, `WinAPI`, `Mutex`, `Semaphore`, `Shared Memory (File-backed)`.
  *   **Tooling:** The project is fully configured with `CMake` and covered by **integration tests**.
</details>

---

### 📫 Connect with Me

<p align="left">
  <strong>Email:</strong> <a href="mailto:romansh0106@gmail.com">romansh0106@gmail.com</a><br/>
  <strong>Telegram:</strong> <a href="https://t.me/Romashku01">@Romashku01</a>
</p>