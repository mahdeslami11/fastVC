---
layout: default
title: Fast VC
---

## Abstract

Current state-of-the-art *voice conversion (VC)* tools rely on neural models trained on massive corpora of data for hundreds of hours. This approach surely leads to astonishing results, but lacks in speed, simplicity and accessibility. In this paper we introduce a simple and fast *any-to-any non-parallel* voice conversion tool that is able to perform its task provided only with a small audio excerpt of target speaker. We consider a modular approach to VC, cascading an *automatic-speech-recognition (ASR)* model, used to transcribe the source speech, and a *text-to-speech (TTS)* model, to generate the target speech. This approach presents a straightforward pipeline, allows to use already available models and opens doors to many expansions. We prove out speakr output to be intelligible and distinguishable between differeners.

## Audio examples

### Class 1

<div class="container">
   <div class="column-left">
     <h6>Source speaker</h6>
     <audio src="audio/class_3_source.wav" controls preload></audio>
   </div>
   <div class="column-center">
     <h6>Target speaker</h6>
     <audio src="audio/class_3_target.wav" controls preload></audio>
   </div>
   <div class="column-right">
     <h6>Output</h6>
     <audio src="audio/class_3_output.wav" controls preload></audio>
   </div>
</div>

### Class 2

<div class="container">
   <div class="column-left">
     <h6>Source speaker</h6>
     <audio src="audio/class_4_source.wav" controls preload></audio>
   </div>
   <div class="column-center">
     <h6>Target speaker</h6>
     <audio src="audio/class_4_target.wav" controls preload></audio>
   </div>
   <div class="column-right">
     <h6>Output</h6>
     <audio src="audio/class_4_output.wav" controls preload></audio>
   </div>
</div>

### Class 3

<div class="container">
   <div class="column-left">
     <h6>Source speaker</h6>
     <audio src="audio/class_5_source.wav" controls preload></audio>
   </div>
   <div class="column-center">
     <h6>Target speaker</h6>
     <audio src="audio/class_5_target.wav" controls preload></audio>
   </div>
   <div class="column-right">
     <h6>Output</h6>
     <audio src="audio/class_5_output.wav" controls preload></audio>
   </div>
</div>

### Class 4

<div class="container">
   <div class="column-left">
     <h6>Source speaker</h6>
     <audio src="audio/class_1_source.wav" controls preload></audio>
   </div>
   <div class="column-center">
     <h6>Target speaker</h6>
     <audio src="audio/class_1_target.wav" controls preload></audio>
   </div>
   <div class="column-right">
     <h6>Output</h6>
     <audio src="audio/class_1_output.wav" controls preload></audio>
   </div>
</div>

### Class 5

<div class="container">
   <div class="column-left">
     <h6>Source speaker</h6>
     <audio src="audio/class_2_source.wav" controls preload></audio>
   </div>
   <div class="column-center">
     <h6>Target speaker</h6>
     <audio src="audio/class_2_target.wav" controls preload></audio>
   </div>
   <div class="column-right">
     <h6>Output</h6>
     <audio src="audio/class_2_output.wav" controls preload></audio>
   </div>
</div>
