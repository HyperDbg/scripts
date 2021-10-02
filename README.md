# HyperDbg Script

This repo is a collection of useful HyperDbg scripts. 

You can use the '[.script](https://docs.hyperdbg.com/commands/meta-commands/.script)' command to run these scripts. For more examples, take a look at [here](https://docs.hyperdbg.com/using-hyperdbg/examples/running-hyperdbg-script).

## Usage

You can use scripts in the HyperDbg environment:

```
HyperDbg> .script c:\users\sina\desktop\script.txt
```

or you can directly run them :
```
C:\Users\sina\Desktop\HyperDbg>hyperdbg-cli.exe --script c:\users\sina\desktop\script.txt
```

## Basics
**hello_world.dbg**: The *Hello World!* script.

## DFIR (Digital Forensics and Incident Response)
**process_behavior_logger.dbg**: Gathering information about different behavior of a process like system calls, memory allocations, CPUIDs, etc.

## Contributing
Pull requests are super welcome. For major changes, please open an issue first to discuss what you would like to change.

## License
[MIT](https://choosealicense.com/licenses/mit/)
