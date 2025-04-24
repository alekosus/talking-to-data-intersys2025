# Appendix F. Examples of factual errors of LLMs found during evaluation analysis

## Fabrication of facts:

**Fragment**: The ship will sail to the Pacific Ocean with young engineers and stokers.

**Answer**: The ship will sail to the Pacific Ocean *to train* young engineers and stokers.

**Explanation**: There is no indication of training in the fragment.

## Incorrect interpretation of misspelled terms:

**Fragment**: The ship was built in *Keel* as a transport

**Answer**: The ship was built in *Keel*.

**Explanation**: Keel is a part of a ship, mistakenly written with a capital letter. It is perceived by the model as a location.

## Misattribution of diary authorship to mentioned individuals:

**Fragment**: In the morning, *I* inspected the new ship... In the evening, the Ghana cin-ema was shown in the dining room – they showed views of Crimea and comic scenes.

**Answer**: The *sailors'* life included inspecting new ships, swimming in the sea and even leisure – the sailors watched films with views of Crimea and comic scenes.

**Explanation**: Identification of the author with sailors without mention in the frag-ments.

## Drawing conclusions unsupported by source fragments:

**Fragment**: R. is silent for days on end, reluctantly answers the doctor's questions, and nothing interests him. The lieutenant, who needs outside help the most, resorts to it the least. His face is bloodless, he lies all the time with his eyes half-closed, you can't hear him breathing, and it seems as if he is not alive.

**Answer**: A wounded lieutenant is mentioned who lost a leg and needed constant help, but rarely asked for it. He was indifferent to the doctors' questions and spent time alone, *which indicates insufficient attention to the psychological state of patients*.

**Explanation**: The fragment does not contain enough information about the conclu-sion.
