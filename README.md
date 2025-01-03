The program:

• prints six sentences, one each for these grammar combinations: single past, single present, single future, plural past, plural present, plural future.

• function main calls make_sentence six times with different arguments each time and prints the returned sentence for all six sentences.

• function make_sentence has two parameters and calls get_determiner, get_noun, get_verb and get_prepositional_phrase and builds and returns a sentence.

• includes a function named get_determiner that takes one parameter and uses that parameter to choose a list of singular or plural determiners and then chooses and returns one determiner.

• includes a function named get_noun that takes one parameter and uses that parameter to choose a list of singular or plural nouns and then chooses and returns one noun.

• includes a function named get_verb that takes two parameters and uses those parameters to choose a list of past, present, or future and singular or plural verbs and then chooses and returns one verb.

• includes a function named get_preposition that takes no parameters and chooses and returns one preposition.

• includes a function named get_prepositional_phrase that takes one parameter and uses that parameter when calling get_determiner and get_noun.

• builds sentences that include two prepositional phrases.
