# RescueAI

<!--
![GitHub Logo](/CASExplorer.png) 
-->
![Alt Text](/rescueai_icon.png)

##

## Overview

Chatbot that assists college students 24/7 in exploring STEM majors and careers, so they can be more confident in their decisions. 

## RescueAI: What is it?

The **“C-A-S”** part of our virtual assistant name stands for the various sections provided in our virtual assistants for students to explore: **C**areer, **A**cademic, and **S**elf exploration. The terms CASE and Explorer stem from how an individual, a case, will explore the different aspects within our chatbot. There could be many different ways students can navigate the virtual assistant for their own needs, hence the name CASExplorer.


## Why CASExplorer? 

Emergency response systems, particularly 911 call centers, face enormous pressure as operators must simultaneously listen, transcribe, analyze, and provide life-saving instructions — often with limited support and high workloads. Manual data entry during live calls can slow down response times and increase the risk of missing critical information. Current software solutions mainly focus on recording calls or providing basic transcription services but do little to actively assist operators in decision-making during live situations.

-Existing solutions for emergency operations typically:

-Focus solely on post-call transcription and record keeping

-Lack real-time keyword extraction and action guidance

-Offer limited editing capabilities for transcription accuracy during a call

Our AI-powered tool offers a new approach by:

-Providing real-time, editable transcription of live 911 calls via Whisper

-Automatically extracting critical keywords from conversations

-Generating recommended next steps for operators based on call content

-Enhancing operator efficiency and reducing cognitive load during emergencies

-Supporting better caller outcomes through faster, more informed operator actions

Most importantly, this project aims to strengthen the first response infrastructure by providing real-time AI assistance during critical incidents, ultimately helping save lives and reduce operational errors.

## Our Solution

We created a prototype designed to assist 911 operators during live calls by leveraging OpenAI's Whisper for speech-to-text transcription and ChatGPT-4.0 for keyword-driven action recommendations. The tool was built using Python and Streamlit for an intuitive user interface that operators can use in real time.

There are three key components of the system:

Live Audio Transcription: Captures audio from the operator's microphone, transcribes it into text in real time, and allows operators to edit transcripts as needed for accuracy.

Keyword Extraction and Analysis: Identifies important keywords from the call that can impact emergency response decisions, such as "fire," "gunshot," or "unconscious."

Action Recommendation System: Based on extracted keywords, the tool suggests immediate steps the operator can advise the caller to take, assisting in triage and response prioritization.

The tool was designed with usability in mind to ensure minimal disruption to existing operator workflows. In the future, we plan to expand the system with additional features such as multi-language support, integration with dispatch software, and AI-driven urgency assessment.

## See Our Demo Video
[![Watch the video]()](https://www.youtube.com/watch?v=8WYtjIdxLEk) 

<!--
[![IMAGE ALT TEXT HERE](/CASExplorer.png)](https://youtu.be/Sa3w50Kn6TY)
-->
