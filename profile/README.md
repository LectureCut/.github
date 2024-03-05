<div align=center> 

# Hey there! 👋
</div>

---
# 📝 Description
**LectureCut** is a video editor designed with the busy student in mind. The idea is to reduce the time spent on watching lectures by cutting out all the parts where the professor is not speaking. This is not the first project of its kind, but it was created out of frustration with the performance of the existing solutions and the loss in quality that comes with using them. The goal is to provide a fast, reliable, and easy-to-use tool that can be used by anyone, regardless of their technical proficiency.

# 🚀 Features
- **Fast**: *LectureCut* is designed to be as fast as possible. It uses some trickery to prevent the necessity of re-encoding the video. This may result in a video file that does not meet industry standards but is still within specifications.
- **Easy to use**: The user interface is designed to be as simple as possible. It is enough to select the video and the rest is done automatically. Currently, we only offer a command-line interface, but a graphical user interface is planned.
- **Cross-platform**: *LectureCut* is written in Rust and C++. This allows it to be compiled for a wide range of platforms, including Windows, macOS, and Linux. (Pre-built binaries are not available yet, but they will be in the future.)

# 📦 Installation and 📖 Usage
The installation method depends on the version you want to use. For the command-line interface, follow the instructions in the [CLI README](https://github.com/LectureCut/CLI). For the graphical user interface, you will have to wait a little longer.

LectureCut is designed from the ground up to be as intuitive as possible. For the command-line interface, it is usually enough to know the following command:
```sh
lecturecut -i input.mp4
```

For more information, simply add the `--help` flag:
```sh
lecturecut --help
```

# 📜 License
All modules are licensed under the MIT license. For more information, see the respective `LICENSE` files.

# 🤝 Contributing
We are always happy about any kind of contribution. If you want to contribute, just fork the repository and create a pull request. If you have any questions, feel free to open an issue.