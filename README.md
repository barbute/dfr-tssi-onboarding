# dfr-tssi-onboarding

[Dallas Formula Racing](https://github.com/DallasFormulaRacing) (DFR) Electric Vehicle (EV) Electrical Subteam 2026 Fall final onboarding project.

## Description

See the [project brief](./attachments/2026-dfr-tractive_system_status_indicator_project_brief.pdf) for project requirements and details.

The project is organized similar to a [monorepo](https://en.wikipedia.org/wiki/Monorepo) and includes the files for both the firmware and the PCBs. Below is a tree diagram of the project's structure:

```
.
├── attachments
├── tssi-firmware-onboarding
├── tssi-hardware-pcb_01
├── tssi-hardware-pcb_02
└── README.md
```

## Getting started

### Requirements

**Hardware**:
- 1x [STM32H533RE Nucleo-64 development board](https://www.st.com/en/evaluation-tools/nucleo-h533re.html)

**Software**:

> The software was developed on macOS. These requirements are for [POSIX](https://en.wikipedia.org/wiki/POSIX) compatible systems.

- `make` (v4.4.1)
- `CMake` (v4.4.3)
- `gcc-arm-none-eabi`
- `openocd`
- `st-link` (v1.8.0)
- [STM32CubeMX](https://www.st.com/en/development-tools/stm32cubemx.html) (for configuring the board)
- VS Code (i mean you could use vim ig) 

### Running

> TODO add this section

## Acknowledgements

> TODO add team members/roles here
