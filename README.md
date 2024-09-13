# Ollama REST API

This project uses Ollama to create a custom LLM model based on Llama 3.1, built from a Modelfile. The model’s parameters are adjusted to generate more creative and fun responses. A simple Node.js script is then used to send prompts via a REST API and log the responses to the console.

## Requisites

 - [Node.js](https://nodejs.org/en/)
 - [Ollama](https://ollama.com/)

## Usage

1. Run the model lama3.1 in your local machine with ollama:

    ```bash
    ollama create my-model -f ./Modelfile
    ```

2. Clone the project and navigate to the project directory:

    ```bash
    git clone https://github.com/stevansehn/node-ollama-modelfile.git
    cd node-ollama-modelfile
    ```
3. Install packages:

    ```bash
    npm i
    ```

4. Run the script:

    ```bash
    node index.js
    ```

## Completion Example

### Question:

Which came first: the chicken or the egg?

### Answer:

The age-old question that has puzzled philosophers, scientists, and (most importantly) your average Joe for centuries!

Well, let's crack open this mystery (get it?) together. 

In all seriousness, though, there are two main theories:

1. **The Chicken Came First Theory**: This idea suggests that birds evolved from reptiles, and eventually, the first chicken-like creature emerged. From there, natural selection favored chickens over other bird species! 
2. **The Egg Came First Theory**: On the other hand, some folks believe that birds evolved from a type of dinosaur called theropods, which laid eggs containing chicks with slightly different characteristics each time they hatched.

Science-wise, it's hard to say exactly when the first chicken-features developed. But this much is certain: **chickens today are directly descended from wild jungle fowl** (yes, those crazy birds that go "Bock! Bock!" in the forest). 

So, while we can't pinpoint an exact timeline, it's safe to say that chickens did indeed come first... or at least their ancestors did. The egg was probably just a sneaky little pre-chicken helping hand.

Now, who's up for some chicken-themed snacks and debate this further?

(P.S. Don't worry if you still don't have an answer – neither do the experts!)

## Compare with the same Chat with default parameters 

### Question:

Which came first: the chicken or the egg?

### Answer:

One of the most enduring and intriguing questions of all time!

From a biological standpoint, it's difficult to say for certain which came first, but here are some arguments and insights:

**The evolutionary perspective:**

According to evolutionary theory, birds evolved from reptiles over millions of years. The first birds are believed to have emerged during the Jurassic period, around 150 million years ago. These early birds were likely small, feathered creatures that hatched from eggs laid by their reptilian ancestors.

As the evolution of birds continued, they developed characteristics such as feathers, wings, and lightweight bones. It's thought that these changes occurred gradually over many generations, with each new generation producing offspring that were slightly more adapted to their environment.

Given this framework, it's likely that birds evolved from a group of reptiles that laid eggs, rather than chickens specifically laying eggs that hatched into chickens. Therefore, in this context, the egg came before the chicken (or at least, the modern chicken).

**The genetic perspective:**

From a genetic standpoint, the question is more complex. The modern domesticated chicken (Gallus gallus domesticus) is a distinct species that has undergone significant selective breeding over thousands of years.

Studies have shown that chickens and their close relatives, such as jungle fowl (Gallus gallus), share a common ancestor that lived around 58,000 to 100,000 years ago. This ancestral population likely had a high degree of genetic variation, which was later reduced through artificial selection in the process of domestication.

In this context, it's difficult to pinpoint exactly when the modern chicken emerged as a distinct species. However, it's clear that the process of domestication involved significant changes to the genetics of the ancestors of modern chickens.

**The answer: neither?**

So, did the egg come before the chicken, or did the chicken lay the first egg?

In a sense, the question is moot. The process of evolution and natural selection unfolded over millions of years, with many species emerging and going extinct along the way. The transition from a reptile to a bird-like creature was likely a gradual one, involving many generations of animals that laid eggs.

So, in conclusion, it's not necessarily either/or; rather, the evolution of birds and chickens involved a long process of incremental changes over millions of years, with many intermediate forms and species along the way.