# DigiZoo

You are in now the owner and creator of the **DigiZoo** a place where digital pets come to live and play. What started out as a grandiose idea has now become a digital reality, but you are quickly realizing that digital pets do not live in the harmony that you hoped for. 

There are some issues that need to be resolved...organizational issues that will keep the pets happy and healthy and living in harmony. 

### A Pet

The idea of a `VirtualPet` remains the same as before.
Attributes (instance variables) that a virtual pet might have, along with some ideas for activities (methods) that might address them are:

- hunger (feed it)
- thirst (water it)
- waste (let it out to the bathroom)
- boredom (play with it)
- sickness (take it to the doctor)

Your methods should cause the appropriate instance variables to update - for instance, if you have a `feed()` method, it might make `hunger` go down, but make `thirst` go up.

Attributes that might update when `tick()` is called:
  - boredom increasing
  - hunger increasing
  - sleepiness increasing

### The Pets in DigiZoo
  
A `VirtualPet` should now become **abstract**. The idea of a pet needs to be more particular, which we will develop in **concrete** classes. Here is a list of the kinds of pets we have in our zoo.

- In general we have `Canine`s and `Feline`s, some of which are `Domesticated` and others which are `Feral`. There are some rules when interacting with these pets that will keep the zoo in harmony...
  - You can `play()` with `Domesticated` pets to keep them happy but DO NOT play with `Feral`
  - You can `walk()` ONLY `Domesticated` `Canines`
  - `Feral` pets must be kept in cages organized by their own specific type (genus/classification)... for example `Lion`s must be caged with `Lion`s and separate from `Tiger`s
  - `Domesticated` pets get along well with one another...just keep them separate from `Feral` please or it won't be pretty
 
 - You have the following `VirtualPet`s in your zoo...you are in charge of determining which are `Domesticated` or `Feral` in your software
  - `Cat`
  - `Dog`
  - `Lion`
  - `Tiger`
  - `Wolf`

### Your Tasks

- Create an abstract `VirtualPet` similar to the Employee class from the Hospital Project that houses common properties and behaviors
  - Each pet must have a name and type...type can be as generic or specific as you would like to make it
- Create a `Zoo` similar to the Hospital class from the Hospial Project
  - Be able to add a pet
  - Be able to remove a pet
  - Be able to display all pets in the zoo, sorted by pet name
- Create abstract classes or interfaces for `Canine` `Feline` `Domesticated` and `Feral`...this organization will be your choice
- Create specific classes for `Cat`, `Dog`, `Lion`, `Tiger`, and `Wolf`
- **Stretch Tasks:** create more specific versions of DigiPets...like `Labrador`, `GoldenRetriever`, `Siamese`, `GrayWolf` etc...

