# toki-pona-orpo
This project aims to provide a high-quality toki pona ORPO dataset, most suited for a chat bot LLM model.

Data collected here are from a private data collection web ui, where users can contribute and edit.

Please DM me on discord for more information & how to contribute: `mega_b`

---

## Data formatting

The dataset is a JSON file.
Each entry of the ORPO dataset contains the following:

- Instruction - Can be either an instruction to the chatbot, or a question.
- Input - If the instruction calls for the input, then this is filled out, other wise it's left blank.
- Accepted - This the best response to the instruction. (e.g following the instruction, being nice, 100% accurate response.)
- Rejected - This is an example of a bad response to the instruction. (e.g inaccurate toki pona, being rude, not following the instruction)

---

This project is under an MIT license, which means you may use this dataset in any way you want, as long as it isn't for any illegal and/or unethical purposes.
You may use this data, modify it, etc. to fit your criteria.
You must credit this github url: `johnpaulbin/toki-pona-orpo` in your applications.
