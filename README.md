# devtoolset-3

Packages to downgrade the gcc compiler version to 4.9.2 in Fedora.

## Steps
```
  $ git clone https://github.com/DevipriyaSarkar/devtoolset-3.git
  $ cd devtoolset-3
  $ dnf install ./*
  $ scl enable devtoolset-3 bash
```

**NOTE:** Be aware that the command `scl enable devtoolset-3 bash` enables gcc/g++ v4.9 in the current terminal session only.
