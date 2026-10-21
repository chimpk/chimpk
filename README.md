<div align="center">

  <h1>👋 Hi, I'm <a href="https://github.com/chimpk">@chimpk</a></h1>

  <p align="center">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&pause=1000&color=38BDF8&center=true&vcenter=true&width=600&lines=Android+Mobile+Application+Developer;MVVM+Architecture+%26+Clean+Code;Firebase+%26+Cloud+Backend+Integration;Real-Time+Data+Sync+%26+Security+Rules" alt="Typing Banner" />
  </p>

  <p align="center">
    <b>Mobile Software Engineer</b> focused on building robust, real-time Android applications with clean architecture and reactive cloud backends.
  </p>

  <p align="center">
    <a href="#-about-me">About Me</a> •
    <a href="#-tech-stack">Tech Stack</a> •
    <a href="#-featured-projects">Featured Projects</a> •
    <a href="#-github-analytics">Analytics</a> •
    <a href="#-engineering-philosophy">Philosophy</a>
  </p>

  <br />
</div>

---

## 📌 About Me

I specialize in **native Android mobile development** with a core focus on **Java (JDK 17)**, **MVVM Architecture**, and **Firebase Cloud Infrastructure**. My projects emphasize end-to-end mobile engineering—from responsive UI with ViewBinding and Material Design components to security-first backend policies and real-time cloud data streams.

- 📱 **Mobile Development**: Native Android development targeting modern APIs (`targetSdk 34`, `minSdk 26`) utilizing Architecture Components (`ViewModel`, `LiveData`, `ViewBinding`, `Navigation`).
- ☁️ **Cloud Backend Integration**: Architecting real-time NoSQL data models in **Cloud Firestore**, media asset storage via **Cloud Storage for Firebase**, and structured access with **Firebase Authentication**.
- 🔒 **Security & Access Control**: Authoring declarative, role-based Firestore and Cloud Storage Security Rules enforcing granular field-level permission matrices (Admin, Manager, Employee).
- ⚡ **Performance & Data Engineering**: Implementing bidirectional snapshot listeners for real-time synchronization, offline caching, and high-performance batch CSV data import/export.

---

## 🛠️ Tech Stack

### 🚀 Languages & Core Platform
<p>
  <img src="https://img.shields.io/badge/Java_17-ED8B00?style=for-the-badge&logo=openjdk&logoColor=white" alt="Java 17" />
  <img src="https://img.shields.io/badge/Android_SDK-343F71?style=for-the-badge&logo=android&logoColor=white" alt="Android SDK" />
  <img src="https://img.shields.io/badge/Gradle_KTS-02303A?style=for-the-badge&logo=gradle&logoColor=white" alt="Gradle" />
  <img src="https://img.shields.io/badge/XML-00599C?style=for-the-badge&logo=xml&logoColor=white" alt="XML" />
</p>

### 📐 Mobile Architecture & Libraries
<p>
  <img src="https://img.shields.io/badge/MVVM_Architecture-007ACC?style=for-the-badge&logo=android&logoColor=white" alt="MVVM" />
  <img src="https://img.shields.io/badge/Android_Jetpack-4285F4?style=for-the-badge&logo=android&logoColor=white" alt="Android Jetpack" />
  <img src="https://img.shields.io/badge/LiveData_%26_ViewModel-3DDC84?style=for-the-badge&logo=android&logoColor=white" alt="LiveData & ViewModel" />
  <img src="https://img.shields.io/badge/ViewBinding-008080?style=for-the-badge&logo=android&logoColor=white" alt="ViewBinding" />
  <img src="https://img.shields.io/badge/Glide-4285F4?style=for-the-badge&logo=google&logoColor=white" alt="Glide" />
</p>

### ☁️ Cloud & Backend Infrastructure
<p>
  <img src="https://img.shields.io/badge/Firebase-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase" />
  <img src="https://img.shields.io/badge/Cloud_Firestore-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Cloud Firestore" />
  <img src="https://img.shields.io/badge/Cloud_Storage-4285F4?style=for-the-badge&logo=googlecloud&logoColor=white" alt="Cloud Storage" />
  <img src="https://img.shields.io/badge/Security_Rules-FF6F00?style=for-the-badge&logo=firebase&logoColor=white" alt="Security Rules" />
</p>

### ⚙️ Developer Tools & Environment
<p>
  <img src="https://img.shields.io/badge/Android_Studio-3DDC84?style=for-the-badge&logo=androidstudio&logoColor=white" alt="Android Studio" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git" />
  <img src="https://img.shields.io/badge/Firebase_CLI-FFCA28?style=for-the-badge&logo=firebase&logoColor=black" alt="Firebase CLI" />
</p>

---

## 💻 Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3 align="center">📱 Student Management System</h3>
      <p align="center">
        <a href="https://github.com/chimpk/student-management-midterm">
          <img src="https://img.shields.io/badge/Repo-student--management--midterm-blue?style=flat-square&logo=github" alt="Repository" />
        </a>
      </p>
      <p><b>Real-time Android student management system with role-based authorization & cloud sync.</b></p>
      <ul>
        <li><b>Architecture</b>: MVVM with Android Architecture Components (ViewModel, LiveData, ViewBinding, Navigation).</li>
        <li><b>Role-Based Access (RBAC)</b>: Granular permission matrix for <i>Admin</i> (account management & audit logs), <i>Manager</i> (full student CRUD & batch I/O), and <i>Employee</i> (read-only view & avatar update).</li>
        <li><b>Cloud Infrastructure</b>: Bi-directional Cloud Firestore real-time snapshot listeners with offline persistence and Firebase Storage avatar handling.</li>
        <li><b>Batch Data & Security</b>: UTF-8 BOM CSV import/export engine and declarative <code>firestore.rules</code> / <code>storage.rules</code>.</li>
      </ul>
      <p><b>Tech</b>: Java 17 • Android SDK • Firebase Firestore • Cloud Storage • Glide • Gradle</p>
    </td>
    <td width="50%" valign="top">
      <h3 align="center">🏦 Banking System Mobile App</h3>
      <p align="center">
        <a href="https://github.com/chimpk/BankFinalTerm">
          <img src="https://img.shields.io/badge/Repo-BankFinalTerm-blue?style=flat-square&logo=github" alt="Repository" />
        </a>
      </p>
      <p><b>Mobile banking application emphasizing security, transaction rules, and account operations.</b></p>
      <ul>
        <li><b>Architecture</b>: Clean Android MVVM structure leveraging Kotlin DSL build configurations (<code>settings.gradle.kts</code>).</li>
        <li><b>Security & Rules</b>: Advanced Firestore security policies governing financial data schema validation, access rights, and document structures.</li>
        <li><b>Backend & Storage</b>: Comprehensive Firebase suite integration with automated script tooling and database indexing configuration (<code>firestore.indexes.json</code>).</li>
        <li><b>Media Caching</b>: Optimized network request handling and image resource loading using Glide.</li>
      </ul>
      <p><b>Tech</b>: Java 17 • Android SDK • Cloud Firestore • Firebase Rules • Firebase CLI • Gradle</p>
    </td>
  </tr>
</table>

---

## 📊 GitHub Analytics

<div align="center">
  <table border="0">
    <tr>
      <td>
        <img height="180em" src="https://github-readme-stats.vercel.app/api?username=chimpk&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38BDF8&text_color=94A3B8&icon_color=38BDF8" alt="GitHub Stats" />
      </td>
      <td>
        <img height="180em" src="https://github-readme-stats.vercel.app/api/top-langs/?username=chimpk&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=38BDF8&text_color=94A3B8" alt="Most Used Languages" />
      </td>
    </tr>
  </table>

  <br />

  <img src="https://github-readme-streak-stats.herokuapp.com/?user=chimpk&theme=tokyonight&hide_border=true&background=0d1117&ring=38BDF8&fire=38BDF8&currStreakLabel=38BDF8" alt="GitHub Streak" />
</div>

---

## ⚡ Engineering Philosophy

```json
{
  "developer": "chimpk",
  "focus": "Mobile Software Engineering & Cloud Backend Integration",
  "principles": {
    "architecture": "Clean MVVM with separation of concerns",
    "realtime": "Event-driven reactive snapshot listeners over manual polling",
    "security": "Enforce zero-trust access control at the database layer (Firestore Rules)",
    "user_experience": "Smooth UI transitions, offline persistence, and robust data integrity"
  },
  "current_stack": ["Java 17", "Android SDK", "Firebase Firestore", "Cloud Storage", "Gradle"]
}
```

---

<div align="center">
  <p><i>Crafted with precision for @chimpk</i></p>
  <p>
    <a href="https://github.com/chimpk">
      <img src="https://img.shields.io/badge/GitHub-chimpk-181717?style=flat-square&logo=github" alt="GitHub Profile" />
    </a>
  </p>
</div>
