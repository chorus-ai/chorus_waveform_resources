---
name: Readiness Checklist v1
about: Create an issue to assess waveform submission readiness
title: "[Enter your site acronym here] readiness checklist"
labels: checklist
assignees: ''
---

# Readiness checklist

This checklist should be used to assess the readiness of your sites year 1 waveform submission.

Before completing this checklist, please read the following two documents:

- [Framework for contributing waveforms](https://chorus-ai.github.io/Chorus_SOP/docs/Waveform-Data/)
- [Format guidelines](https://chorus-ai.github.io/Chorus_SOP/docs/Waveform-Data/Waveform-File-Format)

## 1. General

I confirm that I have submitted the following information in a `SUBMISSION.md` file:

- [ ] a: Number of encounters, highlighting any shortcomings related to the Data Requests SOP
- [ ] b: Number of sessions for each waveform type (e.g. ICU monitor; EEG; Numerics)
- [ ] c: Description of approach for date shifting
- [ ] d: Any known issues

## 2. Waveform details

I confirm that waveforms were prepared following the guidelines above, including:

- [ ] a: Files and folders follow the suggested naming recommendation
- [ ] b: Segments are a maximum of 8 hours
- [ ] c: Gaps are dealt with according to the guidelines above
- [ ] d: Code for converting to the submission format has been shared (optional)

## 3. Additional requirements for non-WFDB formatted waveforms

I confirm that I have submitted all information required to interpret my waveforms (in the `SUBMISSION.md` file), including:

- [ ] a: Description of each variable (e.g. `StartTime`, `ChannelName`, `Samples`) with data type
- [ ] b: Units for each variable, where applicable
- [ ] c: Method for decoding data, where applicable
- [ ] d: Indication of how to determine the sample number (or "monotonic time") at the start of each segment / message stream, where applicable
- [ ] e: Specification of the timestamp variables which indicate the wall-clock time at the start and end of each segment / message stream, where applicable
- [ ] f: Details on how to convert to uniform intervals, if not already in uniform intervals