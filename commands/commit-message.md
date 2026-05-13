---
description: Create a commit message by analyzing the git diffs
allowed-tools: Bash(git status:*), Bash(git diff:*), Bash(git commit:*)
---

## Context
- Current git status: ! `git status`
- Current git diff: ! `git diff`

## Your task

Analyze only the staged git changes and create a commit message. Use present tense, explain why was it done and what changes are done.

## Format
 Use the following format

 ```
 <type_of_change>: <consice_description>
 <optional_description_summary>
 ```

 type of change can be Feature or BugFix, depending upon the change. It is a Feature if the changes are include adding new functionaloty, if it is just adjustment or fixing any existing code treat is as BugFix

 ## Output

 1. Show summary of changes
 2. Propose commit message and show 
 3. Ask for permission to commit

 DO NOT auto commit - wait for user approval, only commit if user say yes
