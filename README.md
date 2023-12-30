# Final Year Project at FAST NUCES

# Background and significance: 
Affective computing is a fundamental step towards enabling human computer interaction, as human communication is filled with affective content which conveys a speaker's private state, i.e., their current mood, their emotional state, or their sentiment towards a certain object of conversation. Along with emotion detection, sentiment analysis is an important stepping stone towards this goal. On a more practical level, being able to automatically determine what people think about an idea, product, or policy is of interest to companies, governments, and private citizens.

We argue that the division of fine-grained sentiment into various sub-tasks (aspect-based sentiment, targeted sentiment, end2end, sentiment target extraction) has become counter-productive, as it is often unclear whether improvements in a subtask (e.g., extracting targets) cause improvements in the overall task. Additionally, explicitly predicting all elements increases the transparency and interpretability of sentiment models. This is beneficial for error analysis, as well as explaining biases that models learn, as we can more easily inspect if certain targets are correlated with a certain polarit.

# Problem description
Predict all structured sentiment graphs in a text (see the examples below). We can formalize this as finding all the opinion tuples O = Oi,...,On in a text. Each opinion Oi is a tuple (h, t, e, p).

where h is a holder who expresses a polarity p towards a target t through a sentiment expression e, implicitly defining the relationships between the elements of a sentiment graph.

The two examples below (first in English, then in Basque) give a visual representation of these sentiment graphs.

![multi_sent_graph](https://github.com/anasamin26/Structured-Sentiment-Analysis/assets/44112604/8c2892e9-fdfb-41e0-a757-021a5415d916)

