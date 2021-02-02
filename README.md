# Gourmet
Small project for learning haskell.

This project aims to generate a random meal, for my flatmates and myself to dinner each day. The plan is to increase the difficulty of the tools used as I learn more haskell. Maybe the use of tools became overengineering. If that happens it would mean that I have learned a lot :).

pd: this project will forever be in alpha probably.
pd2: If you want to do this, maybe golang or python are more useful for this purpose. Nonetheless, you won't learn haskell.

## Version 1

The plan is to have a file `dinners.yml` in which all possible dinner within the realm of our kitchen are listed. I will also like to have a diverticena (happydinner) mode on which only unhealthy food is allowed (e.g. tacos or pizza). Also a detox mode on which no diverticena dish is allowed. 

We choose yaml format as it would be easily scalable in case we want to add more data to the program.

Example file:

```yml
Pizza:
  diverticena: 1
  detox: 0

Crema:
  variaciones: Calabacín, Almendras, Verduras
  diverticena: 0
  detox: 1

Sandwhich:
  diverticena: 1
  detox: 1

Tortilla:
  diverticena: 0
  detox: 1
  variaciones: Revuelto Setas, Tortilla patatas, Tortilla wrap
```



## Further Development ideas

- Nice interface.
- Be able to run this in a Google-Home-like device or telegram bot.
- Choose by ingredient.
