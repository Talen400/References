
# 📚 References Repository

This repository contains an organized collection of PDF references on computer science, programming, networking, cybersecurity, Linux, and more. It serves as a personal library for study and quick reference.

---

## 📂 Directory Structure

```
References/
├── books/
│   ├── algorithms/
│   ├── programming_c_cpp/
│   ├── Programação/
│   ├── RedesDeComputadores/
│   ├── cybersecurity/
│   ├── linux/
│   ├── networking_os/
│   └── misc/
├── container/
│   └── debian_docker_dev/
├── LICENSE
└── README.md
```

- PDF files are organized by topic under the `books/` folder.
- `Programação/` contains general programming materials (distinct from `programming_c_cpp/`).
- `RedesDeComputadores/` contains spreadsheets or materials focused on computer networks.
- The `misc/` folder contains uncategorized or miscellaneous files.

---

## 📖 How to Use

1. **Clone the repository**:

   ```bash
   git clone https://github.com/Talen400/References.git
   cd References
   ```

2. **Browse PDFs**:

   Navigate to the desired folder and open the PDFs using your preferred viewer (Evince, Okular, Adobe, etc.).

3. **Docker Environment**:

   Go to `container/debian_docker_dev/` and follow the instructions in the included scripts to set up a Docker development environment.

---

## 📦 Git LFS

Some large files (such as PDFs and Docker images) are managed using [Git Large File Storage (LFS)](https://git-lfs.github.com). Make sure you have Git LFS installed before cloning the repository:

```bash
sudo apt install git-lfs
git lfs install
```

---

## ⚖️ License

This project is licensed under the terms of the **MIT License**. See the [LICENSE](LICENSE) file for details.