# Capability improvement roadmap
- [ ] Continuous capability measurements
  - [ ] Create a step that asks “did it run/work/perfect”?Create a step that asks “did it run/work/perfect” in the end [#240](https://github.com/AntonOsika/gpt-engineer/issues/240)
  - [ ] Run the benchmark repeatedly and document the results for the different "step configs" (`STEPS` in `steps.py`) [#239](https://github.com/AntonOsika/gpt-engineer/issues/239)
  - [ ] Document the best performing configs, and feed this into our roadmap
- [ ] Self healing code
  - [ ] Feed the results of failing tests back into GPT4 and ask it to fix the code
- [ ] Ask human for what is not working as expected in a loop, and feed it into
GPT4 to fix the code, until the human is happy or give up
- [ ] Break down the code generation in much smaller parts. Then generate test for
each subpart, and do the loop of running the tests for each part, feeding
results into GPT4, and let it edit the code until they pass
- [ ] Run very small tests with GPT3.5 in CI, to make sure we don't worsen
performance over time
- [ ] Let gpt-engineer plan which "steps" to carry out itself, depending on the
task, by giving it few shot example of what are usually "the right sized steps" to carry
out for other projects


# Experiments to try out
- [ ] Microsoft guidance, and benchmark if this helsp improve it


# How you can help out
You can:
- Sign up to help [measure the progress of gpt-engineer towards AGI](https://forms.gle/TMX68mScyxQUsE6Y9)
- Submit PRs to address one of the above items
