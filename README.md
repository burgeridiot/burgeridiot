```lua
task.spawn(function()
  while true do task.wait()
     music.play(
```
<a href="http://www.youtube.com/watch?feature=player_embedded&v=DJ8bK55VP68" target="_blank"><img src="http://img.youtube.com/vi/DJ8bK55VP68/0.jpg" 
alt="The Killing Wind" width="240" height="180" border="10" /></a>
```lua
     )
  end
end)
for i = 0,31556952000,1 do task.wait() -- 31,556,952,000 is the amount of miliseconds a year has...
   daysPassed += 1
   if day.Type == "Weekday" then
      print("Another day, another burden.")
   elseif day.Type == "Weekend" then
```
![tenor](https://github.com/burgeridiot/burgeridiot/assets/98218309/742f1942-91d6-4cb4-a030-29d1846ba6d5)
```lua
  end
end
```
