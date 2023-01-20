# Hello World Rust OS

![_Hello_World__Rust_OS](https://user-images.githubusercontent.com/119659110/213738815-b9a7cc42-d348-4980-b920-f715781c3e8d.png)

These files are used to make A "Hello World!" operating system using Rust
this uses A .BIN file instead of A .ISO file so a good way to run this OS is using the qemu virtual machine [qemu download page ](https://www.qemu.org/download) - [Windows qemu download](https://qemu.weilnetz.de/w64/) - [Windows Direct qemu download](https://qemu.weilnetz.de/w64/qemu-w64-setup-20221230.exe)


# How to run this in qemu Windows
Once downloaded run "qemu-system-x86_64" in your windows powershell/command promt if this doesn't return anything you can add it to your enviromental path or just run it from the qemu folder directly with the .BIN file inside once finished setting it up run "qemu-system-x86_64 -drive format=raw,file=my_os.bin"
and now the OS should be on your'e screen


![Code_ygorGF0Py6](https://user-images.githubusercontent.com/119659110/213742343-bd605879-df1e-472a-9486-32bd6cd18a22.png)


# Credit 

All credit goes to Philipp Oppermann you can follow his blog/tutorial on creating A Rust Operating System on [his website](https://os.phil-opp.com/)
