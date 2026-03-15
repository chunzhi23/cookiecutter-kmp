# Cookiecutter Kotlin Multiplatform

A [Cookiecutter](https://github.com/cookiecutter/cookiecutter) template for [Gradle](https://gradle.org/) based on [Kotlin Multiplatform](https://kotlinlang.org/docs/multiplatform.html) projects.

## Usage

First, install cookiecutter.

```bash
pip install cookiecutter
```

Then, you need to add the path where `cookiecutter.exe` at into system environmental variable so that you can reach out executing cookiecutter with this repo:

```bash
cookiecutter https://github.com/seik/cookiecutter-kotlin
```

or

```bash
cookiecutter https://github.com/chunzhi23/cookiecutter-kmp.git
```

Answer the prompts with your own desired options. For example:

```console
  [1/11] project_name (My Kotlin Project):
  [2/11] project_slug (my-kotlin-project):
  [3/11] class_name (MyKotlinProject):
  [4/11] package_base (com.example):
  [5/11] package_name (com.example.mykotlinproject):
  [6/11] package_path (com/example/mykotlinproject):
  [7/11] group (com.example.mykotlinproject):
  [8/11] version (0.1.0):
  [9/11] kotlin_version (2.3.10):
  [10/11] gradle_version (9.4.0):
  [11/11] use_git (y):
```

Your project has been generated!

See the [cookiecutter documentation](http://cookiecutter.readthedocs.org/en/latest/usage.html) for further details.
