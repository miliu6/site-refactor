# Code Refactor

## Description

In this project, I was tasked with refactoring an existing code that was given to me. Code refactoring is essential in ways that help organize the source code, improve its search engine optimization, and of course helping out future debuggers by abiding by the scouts rule *always leave the code better than you found it*.

The first step I took in refactoring was by changing most of the <div> tags to semantic html elements. I included ones such as <header>, <section>, <aside>, and <footer>. After adding semantic elements I refactored all the heading attributes so that they fell in sequential order. The six <img> tags did not have alt attributes included so I went ahead and added them. I also noticed that clicking on the search engine optimization button did not bring you down to its description. To fix this I added its missing "id" so that it would link to the css file properly. Now that I was dont refactoring the html file, I had to make sure the css selectors were also refactored to match the html file it is linked to. I have added comments in the css file to show the changes that were made.

## Screenshots

```md
![html](assets/images/Screen%20Shot%202022-03-24%20at%205.38.14%20PM.png)
![html](assets/images/Screen%20Shot%202022-03-24%20at%205.38.26%20PM.png)
![css](assets/images/Screen%20Shot%202022-03-24%20at%205.42.38%20PM.png)
![css](assets/images/Screen%20Shot%202022-03-24%20at%205.42.43%20PM.png)
```

## Deployed Link

https://miliu6.github.io/site-refactor/