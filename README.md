# System Temperature Checker

<br>
<div align="center">

![language](https://img.shields.io/github/languages/top/th3-riddler/System-Temperature-Checker?style=for-the-badge&logo=rust&color=orange)
![GitHub](https://img.shields.io/badge/github-000000?style=for-the-badge&logo=github)
![OS](https://img.shields.io/badge/linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)

<img src="https://rustacean.net/assets/rustacean-flat-happy.png" height="300px">
</div>
<br>

A simple command line tool to check the system temperature, including CPU and NVIDIA GPU temperature, written in Rust. <br>
In order to run this script, you need `lm-sensors` and `nvidia-smi` installed on your system. <br>

## Compilation
To compile the code, you need to run the following command in the terminal: 
```bash
cargo build --release
```
> You can even `strip` the binary to reduce its size:
> ```bash
> strip target/release/<BinaryName>
> ```
