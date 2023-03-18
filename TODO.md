# Things Todo

- Add history off all the things
- Add Configuration file support
  - Default models
  - Default parameters

- Allow for different Models easily
  - Different for ask/shell/code commands
  - Auto-Ask different models same question and load result in VIM.

- Smart context
  - Save the Chat context per easily.  Auto-reset if it too long
  - Pre-Written "loaders" that can feed the current context:
    - Document
    - CSV
    - Local System information
    - Username, base paths, major tools.

- Pre-written "prompts" that can easily be pulled in w/ Parameters.
  - ask -p children-story --characters "Axel, Luke, Neo"

- library format for easy Telegram integration

## Places to look

## Possible interface:
ask:
  - model cgpt3.5
  - Prompt "Answer the question without restating it."
  - Context
    - Personal
    - Machine

code:
  - model: davinci
  - parameters
    - lang = python
  - default-Prompt "only return a bug free executable program in {{lang}}"
  - default-context:
    

ai [ask --context machine "Some question"

