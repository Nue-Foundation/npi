# 🚀 Welcome to `npi`! 🎉

Introducing `npi`, the all-in-one command-line tool for managing your projects with flair and style. Just like Rust's Cargo or JavaScript's npm, `npi` is here to make your life easier with a touch of fun! 😎

## Getting Started 📦

# 🎉🎉 GOOD NEWS! 🎉🎉
You don’t need a personal access token anymore! 🚀🙌 Just imagine the freedom! 🌟 No more token headaches, just pure, unadulterated repo love! 💖🎁

### Installation 💻

Download the pre-compiled `npi.exe` from the [releases page](https://github.com/Nue-Foundation/npi) and place it in a directory included in your system's PATH. Now you're ready to roll! 🚀

### Usage 📜

This tool is powered by the magical `npi` command. Let's dive into what you can do with it.

#### Listing Projects 📝

Want to see all the cool projects in the `NuePkgs` organization? Easy peasy! Just run:

```sh
npi list 
```
And voilà! You'll get a list of all the repositories. It's like magic! 🧙‍♂️

#### Downloading a Project 📥

Need to download a project for some serious hacking? We've got you covered:

```sh
npi download [repo] 
```

Replace [repo] with the name of the repository you want to download. We'll zip it up and deliver it right to your doorstep. 🎁

#### Listing Files in a Project 📂

Curious about what's inside a project? Peek inside with:

```sh
npi list-files [repo] 
```

Replace [repo] with the name of the repository, and you'll get a full list of files and directories. It's like having x-ray vision! 🦸‍♂️

### Example Workflow 🛠️

Here's a quick rundown of how you might use npi in your daily routine:

```sh
PS K:\npi-dev\demo> .\npi list
NuePkgs/.github
NuePkgs/mdm-lib
NuePkgs/types-lib
PS K:\npi-dev\demo> .\npi list-files types-lib
LICENSE
README.md
types
types/collections
types/collections/array.pkg
types/collections/complex_array.pkg
types/collections/tensor.pkg
types/collections/vector.pkg
types/values
types/values/string.pkg
PS K:\npi-dev\demo> .\npi get types-lib       
Successfully Geted and unzipped types-lib
PS K:\npi-dev\demo> ls


    Directory: G:\fri3nds\y-category-Projects\pkg-exe-for-windows


Mode                 LastWriteTime         Length Name
----                 -------------         ------ ----
d-----          8/3/2024   8:27 AM                .vs
d-----          8/4/2024  12:05 AM                Release
d-----          8/7/2024  10:42 AM                Release-npi
d-----          8/7/2024  10:44 AM                types-lib-main  <= This is that dir
-a----          8/3/2024   7:52 AM            530 go.mod
-a----          8/3/2024   7:52 AM           3267 go.sum
-a----          8/7/2024  10:43 AM       11822080 npi.exe
-a----          8/7/2024  10:43 AM           4193 npi.go
-a----          8/3/2024   8:26 AM       11836928 pkg-v1.exe
-a----          8/4/2024  12:05 AM       11839488 pkg.exe
-a----          8/4/2024  12:04 AM           5047 pkg.go
-a----          8/3/2024   7:31 AM            534 steps-todo.txt


PS K:\npi-dev\demo>
```

### Conclusion 📚

npi is here to revolutionize the way you manage your projects. It's powerful, easy to use, and just plain fun. So go ahead, give it a spin, and let the magic happen! ✨

Happy coding! 👨‍💻👩‍💻

