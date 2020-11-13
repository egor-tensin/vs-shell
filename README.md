Visual Studio shell
===================

This is a GitHub action that sets up a Visual Studio shell in your workflow
run.
This is similar to running one of the vcvars*.bat scripts or launching one of
the "Command Tools for VS" Start Menu shortcuts, but it's also shell-agnostic.
Use it in your workflow like this:

    - name: Set up Visual Studio shell
      uses: egor-tensin/vs-shell@v1
      with:
        arch: x64

`x64` is the default value for the `arch` parameter and can be omitted.
Use `x86` if you want to build 32-bit binaries.

License
-------

Distributed under the MIT License.
See [LICENSE.txt] for details.

[LICENSE.txt]: LICENSE.txt
