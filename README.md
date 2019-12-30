# c3lingo-stats

Parse and summarise the contents of the Etherpads that c3lingo uses to assign translation shifts at Chaos events

## Requirements

Python 3 with Pandas (`pip install pandas`).

## Usage

Export the pads you want to include as plain text and pass the paths as arguments to `main.py`.

```sh
./main.py pads/*.txt
```

## Analysis

You can run some analysis using the `Translation stats.ipnyb` notebook. To open it, you'll need to install the additional `jupyter` requirement.

Simply open the notebook, tap **Kernel** and push **Restart & run all** to get fresh data.