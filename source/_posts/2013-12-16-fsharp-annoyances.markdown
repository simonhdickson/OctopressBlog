---
layout: post
title: "F# annoyances"
date: 2013-12-16 00:29
comments: true
categories: [fsharp,]
---
While I do love F#, there is one particular thing that I have been annoyed by a few times recently. The following syntax:

```fsharp
let x = 1;2
```

Now, without running it, looking it up or googling for it, what do you think this means? My first thought was that x would be equal to 1 and 2 would be ignored. Then my second thought was that it was short hand for declaring a list, same as this:

```fsharp
let x = [1;2]
```

But no, neither of these two thing is what this code does, infact it sets x to be equal to 2, and the 1 is ignored.

Now this may not sound all that confusing on the 