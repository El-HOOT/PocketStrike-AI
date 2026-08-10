

## Security Review

The current security review handles 2 (1 blind, 1 naive) flaws in the original code

### Merge?

whether this's something the original author considers important to merge or not is unclear: 

- He didn't review the fork formally
- Didn't acknowledge or defend any of the uncovered vulnerabilities
- Didn't reply or comment on an issue asking him to toggle on security reviews for this repository

### Does it matter?

Given this project is an AI with nearly full access to one's phone, handling command-prompt injections isn't an act of luxury — it's a non-trivial MUST that a model with such permissions should have.

### Your safety

I would personally advice potential users to use the hardened version, it didn't sacrifice any functionality and is more security conscious.