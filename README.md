# weirdness.patch
.. investigation ( for 1 nd) 
- this plugin is really raw.. the source is the very minimum and for some reason changing targets is a pain in vs
- I really love this plugin - and family
1. will you host a binary release: no... ( its not my project. I am only patching it )
### going to be quite the story since I dont really know cpp to this level yet..
1. the host can confuse you and this means its tricky to realise what it needs to fix it; ( for example dealloc somewhere ) or return state ()
2. omg host editor is too annoting: Editing xml. Considering paying for the lion is mayve gonna happen
## reasons
1. you can crash hosts on a few of them - its likely two issues.. etc. It seems maybe todo with bursts when i noticed it and allocation therefore ( guess ) 
2. it could be the host I am stuck with at the moment.
### work
1. try upgrade to 2019 `res/ide`
2. try fix defaults `src/patch`
3. try fix max/min  `src/patch`
4. try to fix why gui change can use gain/complexity O() crash `src/patch`
5. try to fix limit for gen midi drums `src/patch` Im not sure the reason for this ... 
  i. refactor code to use less cpu if this was the reason back then I notice `/3` for concurrent
6. try to make a template for each plugin to upgrade in automated manner `res/plugin` `res/plugin/restructure/base` etc
