```haskell
import System.Random

insults :: [String]
insults =
          [ "If ignorance is bliss, you must be the happiest person alive."
          , "I'm pretty sure your code is a war crime."
          , "Did you write that code with your feet?"
          , "Your code is the reason why aliens won't talk to us."
          , "It's a miracle your code compiles at all."
          , "I've seen better code in a beginner's tutorial."
          , "Your code is a monument to everything that's wrong with programming."
          , "If your code were a movie, it would be a never-ending horror film."
          , "Your code is like a bad haircut: it's obvious that you tried to do it yourself."
          ]

main :: IO ()
main = do
  let range = (0, length insults - 1)
  randIndex <- randomRIO range
  putStrLn $ insults !! randIndex

```
<p align="center">
  <a href="https://keys.openpgp.org/search?q=sogreatandpowerful%40tuta.io">PGP KEY</a>
</p>
