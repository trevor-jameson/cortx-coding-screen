# Coding screen for Cortx

Imagine we want to represent different ways of writing the same sentence. For instance:
{I am|I'm} {working on|starting} this {online |}interview. I hope Cortx thinks I am {{very|extremely} qualified|great|awesome}{!|.}

In this example anything surrounded by { and } and separated by | represent different options equally valid ways this sentence can be written. So {interesting|exciting|intriguing} means "interesting", "exciting", or "intriguing" could each be correctly used at that point in the sentence.

So the original example can be expressed in many different ways - here are a couple:
I'm working on this interview. I hope Cortx thinks I am awesome!
I am working on this online interview. I hope Cortx thinks I am extremely qualified.

Write a program that takes as input a string in the above {option1|option2|...} format and randomly generates a possible output. Note that there can be multiple levels of nested options - for instance {this {specific|particular} example|an example {like|such as} this}

You should test your code before submitting (and we will try to run your code) however please do all of your writing in this window and try your best to document in the comments your thoughts, strategies, and approaches as much as possible.

Good luck!
