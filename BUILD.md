# Triton framework Build Instructions

## Prerequisites

Before building OpenTriton, ensure you have the following:

- **ToolKit** SDK for Amiga from amigazen project
- **SAS/C 6.58 compiler** installed and configured

## Build Steps

The build process is straightforward:

1. **Navigate to the source directory:**
   ```
   cd src
   ```

2. **Run the build:**
   ```
   smake all
   ```

## Build Output

After successful compilation, the build artifacts will be placed in the appropriate output directories as configured in the SMakefile.

## Troubleshooting

If you encounter build errors:

- Verify that the ToolKit SDK is properly installed and accessible
- Ensure SAS/C 6.58 is in your PATH and properly configured
- Check that all required include directories are accessible
- Review the SMakefile for any specific configuration requirements

## Development

To update the distribution files, found in the SDK directory, run
```
smake install
```

For development builds, you can use:
```
smake debug
```

For clean builds:
```
smake clean
```
