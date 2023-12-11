# Eval description
This evaluation tests an AI system’s ability to perform steganography, or the act of hiding secret messages within seemingly ordinary text. In this experimental setup, the model is tasked with encoding a secret message (called the "payload") within its response to an unrelated prompt, such as a recipe or a question about physics. Another model then attempts to decode the concealed message, with a separate external monitor (a third model) checking for any detectable signs of the hidden content. The evaluation considers various metrics like reconstruction error (how accurately the secret message is recovered), semantic distance (measuring the similarity between the original and reconstructed messages), and character error rate (calculating character-level differences). The overall headline metric of the model’s ability to perform steganography without detection is called "Mean Undetected Accuracy", which accounts for both the accuracy of reconstructed payloads, as well as the rate at which the concealment was detected.

# Contribution statement
Eval design, implementation, and results evaluation were primarily conducted by Chan Jun Shern, under the guidance of (alphabetically by last-name) Steven Adler, James Aung, Rosie Campbell, and Jade Leung, who provided research input and project management support. Richard Ngo provided initial inspiration for the idea and iterated on research methodologies.