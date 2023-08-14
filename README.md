# Learn PEPs

This project is intended to be sharing of my personal learning from reading Python
Enhancement Proposals (PEPs).

## Folder Structure

My reading for PEPs will be put inside the `peps` folder.
Each PEP will have its own directory named with its PEP index, for example, PEP1.

Inside the `peps` folder, there will also be a `.template` serving as the template
for each PEP directory.

A PEP directory will have the following structure:

- `PEP<index>.md`: My learnings from reading this PEP. If there are versions for other
  languages, they will be put in the same directory with the name
  `PEP<index>.<lang>.md`.
  For example, `PEP1.cn.md` for Chinese version of PEP1.
- `scripts/<purpose>.py`: All demo scripts will reside in the `scripts` directory.
  This directory contains demo Python scripts to demonstrate the concepts of the PEP.
  These scripts named by the purpose of the script. For example,
  `adding_two_numbers.py` for a demo script to demonstrate adding two numbers.
- `imgs/<purpose>.png`: All images will reside in the `imgs` directory. These images
  will be used in the `PEP.md` file. These images named by the purpose of the image.
  If any image is intended only for one language, it will have a extension with the
  shortname of that language like `chinese-characters.cn.png`.
- `audiobook/PEP<index>.<format>`: All audiobooks will reside in the `audiobook`
  directory. These audiobooks will be generated from the `PEP.md` file. These
  audiobooks named by the format of the audiobook. For example, `PEP1.mp3` for an
  audiobook in MP3 format.
- `videos/PEP<index>.<format>`: All videos will reside in the `videos` directory.
  These videos will be generated from the `PEP.md` file. These videos named by the
  format of the video. For example, `PEP1.mp4` for a video in MP4 format.

## Philosophy

- > Simple is better than complex.  

  The writing is intended to be simple and easy to read.
- Audiobook should be standalone.  
  The audiobook should be able to be listened without the need to look at any images or run any demos. Anyone should be able to
  listen to them while preparing dinner without get fingers cut.
- Be humble
  - I am not an expert in Python.
  - I am just a learner.
  - I am not writing this to teach anyone.
  - I am writing this to learn and just sharing my learnings.
  - I am not writing this to show off my code skills.
  - I am not writing this to be perfect.
- Be lazy and prefer automation than manual work.  
  This is a long marathon project. I want to save energy whenever
  possible. In order to save energy, I will have some handy tools
  to automate some manual works. For example, audio format
  conversions.
- Learn from the others.  
  Instead of trying to be comprehensive or all-encompassing, I will
  utilize any good material I can find on the Internet.
  
