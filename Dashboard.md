### Personal Dashboard
**`Organizing my life and tracking my project progress`**

---
### Project: Airplane Identification Summary
[Project Link](Portfolio/Airplane_Identification.md)
```mermaid
kanban
  [To Do]
    [Identification Chart]
    [Pie Chart]
    [Quizzes]
    [Conclusion]
    [Compile Resources]
  [In progress]
    [Break Down Planes by Category]
  [Ready for deploy]
    [Purpose]
  [Ready for test]
    [TBD]
  [Done]
    [TBD]
```


---
### Personal To Do List
```mermaid
%%{init: {'theme':'forest'}}%%
kanban
  [Personal]
    [Record Writing Video Shots]
    [Lessons Learned from Moving]
    [Top 5 Video]
  [School]
    [UW Masters Degree Recap]
    [3D Printing Phase]
  [Career]
    [Interview Yourself]
    [Plane Identification]
    [How Infrared Works]
  [Life]
    [Car Registration & Smog Check]
    [Register for SEA2POR Race & Text Drew]
    [Cascades Promo Message]
  [Completed]
    [Create Documentation]
    [Create Blog about the new diagram]
```


---
```mermaid
kanban
  Todo
    [Create Documentation]
    [Create Blog about the new diagram]
  [In progress]
    [Create renderer so that it works in all cases. We also add som extra text here for testing purposes. And some more just for the extra flare.]
  [Ready for deploy]
    [Design grammar]@{ assigned: 'knsv' }
  [Ready for test]
    [Create parsing tests]@{ ticket: MC-2038, assigned: 'K.Sveidqvist', priority: 'High' }
    [last item]@{ priority: 'Very Low', assigned: 'knsv' }
  [Done]
    [define getData]
    [Title of diagram is more than 100 chars when user duplicates diagram with 100 char]@{ ticket: MC-2036, priority: 'Very High'}
    [Update DB function]@{ ticket: MC-2037, assigned: knsv, priority: 'High' }

  id12[Can't reproduce]
    id3[Weird flickering in Firefox]
```
