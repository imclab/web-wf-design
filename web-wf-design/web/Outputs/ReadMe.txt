This Folder is the root for the output/result files of a Taverna workflow run.

Each Taverna Run (not WireIt run) will create its own directory.

Directory names are time based YEAY_MONTH_DAY_HOUR_MINUTE_SECOND so they sort by time.

Each directory contains three files:

- BaclavaOutput.xml is the actual output file as generated by the Taverna Command Line Tool.
- Output.txt is the output that the Taverna Command Line Tool sent to the console plus a bit of extra information added by the wrapper.
- TavernaLog.txt is the Taverna Command Line Tool log file (assuming logging is set up correctly).