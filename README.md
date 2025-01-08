# Building GCC for any-any-any as a Windows Executable using Cygwin

- This guide details the process of building a cross-compiler version of GCC that runs on Windows (via Cygwin) and targets any platform.

1. Prerequisites

    - Install Cygwin
        - Download the Cygwin installer from Cygwin's official website.
        - During installation, select the following packages:
            - gcc-core: Native GCC compiler for Cygwin.
            - make: Build system.
            - binutils: Tools for assembling and linking.
            - gmp-devel, mpfr-devel, mpc-devel, and isl-devel: Math libraries required by GCC.
            - wget, tar, python3: Utilities to fetch and extract source code.
            - git: If you want to clone the source.

    - Verify Installation
        - Ensure the tools are available in your Cygwin terminal:
####
         gcc --version

2. Download Required Source Code
    
    - Download required gcc version from
        - https://ftp.gnu.org/gnu/gcc/
    - Download binutils source
        - https://ftp.gnu.org/gnu/binutils/

