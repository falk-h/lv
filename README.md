# lv

Quick and dirty script to "calculate" the week in the academic year for some swedish universities.

## Dependencies

- Bash or Zsh

## Installation

1. git clone
2. Copy lv to some folder in your path.
3. Make it executable (`chmod +x /path/to/lv`)

## Usage

	lv [OPTION]

	-d DATE    Get the week for DATE. Default is today.
	-h         Display this help message

## Output

- LVn for teaching weeks
- TV for examination weeks
- OTV for reexamination weeks
- Vn for other weeks

Where n is the number of the week.