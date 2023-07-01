# SDL3 CMake Template

## Development

To start developing, first generate the CMake project files :
```
$ cmake .
```
Next you can try building the project :
```
$ cmake --build . --config <mode>
```
### ! Running the build
You must add the `SDL3.dll` library to the same directory as your executable. (`/Debug` | `/Release`)<br>
<sup>*You can find `SDL3.dll` in `/_deps/sdl-build/Debug/`.*</sup>

<br>

## CMake

### Generating the Project files
<sub>*On Windows this will generate the .sln file*</sub>
```
$ cmake .
```

<br>

### Building the Project
<sub>*Change the `<mode>` to the build mode (Debug | Release)*</sub>
```
$ cmake --build . --config <mode>
```
