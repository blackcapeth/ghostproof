# ghostproof

A memory game themed around zero knowledge proofs. The verifier shows a hidden pattern on a 5 by 5 grid, then asks about only some of the cells. You prove you recall which of those were real, and you reveal nothing about the rest.

There are five rounds. You need four accepted proofs to pass. After the last round the game draws a pixel avatar.

This is an unofficial fan project. It is not affiliated with any protocol team.

## Live site

https://blackcapeth.github.io/ghostproof/

## How to use

The site is a single static `index.html` file. Clone the repository and open that file in a browser:

```
git clone https://github.com/blackcapeth/ghostproof.git
cd ghostproof
```

Then open `index.html` in your browser, or serve the folder with any static file server.

Choose Begin verification, memorize the lit cells, then click only the challenged cells that were real and submit the proof. Run again returns you to the start screen.
