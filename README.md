Tokens are the small units of text that a language model processes instead of reading entire sentences at once. A token can be a word, part of a word, a character, or even punctuation depending on the tokenizer being used. For example, the sentence “Transformers are powerful” may be split into tokens such as “Transform”, “ers”, “are”, and “powerful”. Tokenization helps the model convert human language into numerical representations that a computer can understand and process efficiently.

During processing, each token is transformed into vectors called embeddings, which capture meaning and relationships between words. These embeddings allow the model to recognize context, grammar, and semantic similarities between different pieces of text. Tokens are therefore the foundation of how transformer models interpret language, generate responses, and perform tasks such as translation, summarization, and question answering.

                                         ATTENTION

Attention is a mechanism that enables a transformer model to focus on the most relevant parts of an input sequence when processing information. Instead of treating every word equally, attention assigns different importance scores to tokens based on their relationship to one another. For example, in the sentence “The cat sat on the mat because it was soft,” attention helps the model understand that “it” refers to “the mat” rather than “the cat.”

The most common form used in transformers is called self-attention, where each token compares itself with every other token in the sequence to gather contextual information. This process allows the model to understand long-range dependencies and contextual meaning much more effectively than traditional sequential models. Attention is one of the key innovations that makes transformer architectures highly effective for natural language processing tasks.

                                    TRANSFORMER BLOCKS

Transformer blocks are the core building units of transformer models. Each block typically contains two major components: a self-attention layer and a feed-forward neural network. The self-attention layer allows the model to determine relationships between tokens, while the feed-forward network processes and refines the extracted information. Additional mechanisms such as normalization and residual connections help stabilize learning and improve performance.

Multiple transformer blocks are stacked together to form deep neural architectures capable of learning complex language patterns. Early layers may capture simple grammatical structures, while deeper layers learn higher-level semantic and contextual relationships. By repeatedly processing tokens through these blocks, transformer models can generate coherent text, answer questions, and perform advanced reasoning tasks with high accuracy.# Task-2

                                  FLOW DIAGRAM
                                 flowchart LR
    A[Input Text] --> B[Tokenization]
    B --> C[Transformer Layers]
    C --> D[Output] 
