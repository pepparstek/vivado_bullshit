# Debug

Problems encountered during debugging sessions.

## New signals

When adding signals in "Set up Debug" and they exist in the ILA after going through the setup but doesn't show up when loading the bitstream into the device it can be because of cached files in "{repo}.hw". Delete the files inside in the .hw folder to force Vivado to recreate them and re-run Synth/Impl/Bitstream process again.