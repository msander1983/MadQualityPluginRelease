# 1.0.7
- Corrected a bug that prevented the "FileNameRegex" function from working. 
- Added more default rules based on the "Write Good" rules. 
- Activated all rules again.
- Added a tab for each category of rules so that you can copy & paste them into the first tab to activate them.
- Extended trial.
- Various rule changes. 

# 1.0.6
- Corrected the en/em-dash rule. The previous REGEX expression took too long to process. 
- Added a box with the message in the results window. If the description or message has a link, you can click it to open in your browser. 
- Files are now processed in parallel to make the processing faster. 
- Added a progress bar for each individual file so that you can see the progress. 
- Disabled some of the more processor intensive rules in the default template. Added tabs for structural rules and MS manual of style. 
- CANCEL => Cancel

# 1.0.5
- The "IgnoreCase" setting was ignored, but isn't anymore.
- Added feature to use rules at other location, e.g. "G:\my Rule.xlsx" or "https://www.github.com/.../rules.xlsx".
- Added button to open the folders with the rules, for easy import/export. 
- Corrected bugs in the rule sets. 
- Corrected resize bug in the results window.

# 1.0.4
- The results window no longer stays on top.
- The processing modal window no longer stays on top while processing. 

# 1.0.3
- Regular expressions now operate on strings without taking inline tags into consideration. 
- Added Microsoft Manual of Style rules to the template. 
- Added progress bar and cancel button.

# 1.0.2
- Regular expressions now operate on an elements string value with tags replaced rather than the element value, which would exclude content in e.g. span tags in paragraphs. 

# 1.0.1
- Bug fixes