﻿## How to contribute (Teach AnimalFactsBot a new animal):

Check the open issues to claim a listed animal, or come up with your own. Be sure to also check currently open pull requests to make sure you don't duplicate someone else's work.

        Due to Hacktoberfests pull requests are coming in fast! Comment on an issue you are going to work on - and also check open pull requests before you do work someone else has already done.

Steps:
* Fork/clone the repo
* Add a tuple of strings of facts (to animalfacts.py) pertaining to a particular animal. Name the tuple variable following the format 'NAMEOFANIMAL_FACTS'. Put the tuple in alphabetical order with the other tuples.
* Add your tuple to the ALL_FACTS tuple.
* Add a line to the check_comment_for_animal() function for your animal following the format.
* Add your animal to the Readme
* Add me on Twitter @joelatwar

Please:
* Don't add a very small set of facts (this will cause the bot to be repetitive regarding your animal).
* Each fact must make sense independent of the other facts in the tuple because users will only get one fact at a time.
* Only add TRUE facts. Please no trolling with 'alternative facts'.
* Don't add 'seal', 'bat' or 'duck' facts unless you've figured out how to not reply to homonyms.
* Don't add 'cat' or 'dog' because they are just too common on reddit.

If you have a question the quickest way to reach is me on twitter @joelatwar


# animal-facts-bot

Animal-facts-bot is a Reddit bot that searches for comments on reddit that contain the name of the animal and then replies to the comment with a fact about that animal.

You can see the bot in action at https://www.reddit.com/user/AnimalFactsBot/comments/

### Current supported animals:
* aardvark
* albatross
* alligator
* alpaca
* anglerfish
* ant
* anteater
* antelope
* armadillo
* badger
* bear
* beaver
* bison
* bobcat
* buffalo
* camel
* capybara
* chameleon
* cheetah
* chipmunk
* chinchilla
* clownfish
* cobra
* cougar
* cow
* crab
* crayfish
* crocodile
* cuttlefish
* deer
* degu
* dingo
* dodo
* dolphin
* dragon
* dugong
* eagle
* echidna
* eel
* elephant
* elk
* emu
* falcon
* flamingo
* fox
* frog
* gazelle
* gecko
* giraffe
* grasshopper
* goat
* goose
* gopher
* gorilla
* hamster
* hedgehog
* hippo
* honeybee
* horse
* hummingbird
* husky
* iguana
* jackal
* jellyfish
* kangaroo
* kiwi
* koala
* lion
* lemur
* leopard
* lynx
* lion
* lizard
* lobster
* llama
* manatee
* mantis shrimp
* meerkat
* mink
* mongoose
* monkey
* moose
* narwhal
* newt
* ocelot
* octopus
* opossum
* orangutan
* oryx
* orca
* ostrich
* otter
* owl
* panda
* pangolin
* panther
* parrot
* peacock
* peccary
* penguin
* pig
* pigeon
* platypus
* puma
* rabbit
* raccoon
* rattlesnake
* raven
* salmon
* scorpion
* seagull
* sea cucumber
* sea urchin
* shark
* sheep
* skunk
* sloth
* snail
* snake
* squid
* squirrel
* stingray
* sunfish
* tarantula
* tardigrade
* tiger
* trout
* toucan
* turtle
* vampire bat
* wallaby
* walrus
* warthog
* whale
* wolf
* wolverine
* yak
* zebra

### AnimalFactsBot will reply to its replies if they contain the phrases:
* good bot
* bad bot
* thank
* more
* silly
* TIL
* AnimalFactsBot

AnimalFactsBot gets these fairly often.
