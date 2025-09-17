## Overview

Hospital name:

Brief description of the dataset: <number of patients, the years covered by your waveform data, the types (e.g. high-frequency telemetry, low-frequency telemetry, EEG) of waveform files being submitted and the number of each type>

Any known issues: <if there are any known issues with the waveforms, please make them known so we can try to address them>


<!-- Uncomment and fill this out if you manipulated your waveform data to handle gaps and overlaps
## Gaps and Overlaps

Were you able to differentiate between gaps due to missing data and other types of gaps (e.g. a gap due to a clock resync)?

Describe how you modified your data for each gap type:
-->

## Format Details

The description (e.g. StartTime represents the time at the start of the first sample in the message stream), data type, and unit (where applicable) for each variable:

| Variable name | Description                           | Data type | Unit |
|---------------|---------------------------------------|-----------|------|
|               |                                       |           |      |
|               |                                       |           |      |
|               |                                       |           |      |
|               |                                       |           |      |


Details on how the data is encoded, if applicable:

Details on whether sample intervals are uniform across waveform types and channels (high-frequency waveforms should have uniform sample intervals, but if this is not the case please explain why - we expect that numerics files may have non-uniform sample intervals):

Pair-based submissions
- Instructions for how to determine the sample number (or "monotonic time") at the start of each segment / message stream:

- Specification of the timestamp variables that represent the wall-clock time at the start and end of each segment / message stream:

## Waveform EHR Linkage  
      
Please outline the process you used for linking `session_id` from your waveform data to `visit_detail_id` in your OMOP EHR data: