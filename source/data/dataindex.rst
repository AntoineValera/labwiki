.. _dataindex:

What to do with Data
####################

.. toctree::
   :maxdepth: 3
   :caption: See also:
   
   data/preprocess
   data/nwb
   data/behaviour


Storage
=======

Backup data available on \\192.168.15.13\silverlab-rigX (eg silverlab-rig3) [Need account for access]

Data Formats
============

Acquisition
-----------
Labview Functional Imaging Data is saved as separate TDMS per trial. Matlab acquisition saves separate .mat files per ROI and Trial. Each Video camera saves binary files for whole recording. For analyses, videos are exported to .avi (compressed), and functional data exported to TIFFS or .mat. See separate section for more details :ref:`preprocess`

Formats
-------
Data is formatted as x-y-z-time-channel-roi-trial [where x refers to scanning direction, and z=1 except for volume scans]
For variable scans, data is a cell array [roi x trial] of 5D data structures [ x-y-z-time-channel ]