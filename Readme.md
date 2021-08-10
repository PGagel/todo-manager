# ToDo Manger (tdm)

This small program manges todo lists and displays them to you. You can add Tasks, estimated work hours required, tags, and more.

## Prerequisites
TDM requires the following libraries and programs:
- CMake@>3.10

## Build

A simple build pipeline could look like this:
```bash
cd /path/to/TDM
mkdir build && cd build
cmake ..
make
```

## Usage

To create Todo Notes simply type `tdm` in your console.
This will prompt you with the choice to list your current notes or create new ones.
If you want bypass the initial selection, simply add `--create` or `--list` to the command.
These arguments will respectively put you into task creation or display the task list.
