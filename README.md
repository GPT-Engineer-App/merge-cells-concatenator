# merge-cells-concatenator


lets assume we have two documents, each has a certain table with some rows and their cells.

My goal is two navigate to a certain cell in the second document, and to clone its whole content
and to append the cloned content to the end of a certain cell in the first document.

A "merge" or "concatenation" to keep it in other words.

The cloned content may comprise any kind of child-node, as well as fields, anything!
(in other words: any "content-composition")

The PSEUDO-Code for the Java-Method i am looking for is as follows:

public static void mergeCells(Cell targetCell, Cell sourceCell)
{
for(Node child : sourceCell.getChildNodes())
{
targetCell.append(child.clone());
}
}

Any ideas with aspose.words java


Regards!

Mikel

## Collaborate with GPT Engineer

This is a [gptengineer.app](https://gptengineer.app)-synced repository 🌟🤖

Changes made via gptengineer.app will be committed to this repo.

If you clone this repo and push changes, you will have them reflected in the GPT Engineer UI.

## Tech stack

This project is built with React and Chakra UI.

- Vite
- React
- Chakra UI

## Setup

```sh
git clone https://github.com/GPT-Engineer-App/merge-cells-concatenator.git
cd merge-cells-concatenator
npm i
```

```sh
npm run dev
```

This will run a dev server with auto reloading and an instant preview.

## Requirements

- Node.js & npm - [install with nvm](https://github.com/nvm-sh/nvm#installing-and-updating)
