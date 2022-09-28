<h2>TeachPeer Requirements</h2>

<p>TeachPeer is a learning platform focused on making learning fun and effective. It does this by recording measurements of learning time and progress. It provides APIs to read and record student specific time series data pertaining to learning experiences and learning assessments. It also calculates student specific credits calculated using a combination of learning time and assessment performance. It uses this data to measure the relationship between learning experiences and learning outcomes. It also gives students a sense of progress by keeping track of sustained effort and performance. It uses that data to help drive learning effectiveness.</p>

it has ...
- [ ] users called STUDENTS
- [ ] data-times when STUDENTS experiece LEARNING-ITEMS, called EXPERINECES
- [ ] associated facts called LEARNING-ITEMS (think n-sided flashcards)
  - [ ] LearningItems examples:
  - [ ] 心 - xīn - 'zh/xin1.mp3' - heart
  - [ ] Battle of Hastings - 14 October 1066 - East Sussex
  - [ ] scala.collection.immutable.TreeMap - An immutable SortedMap whose values are stored in a red-black tree.
- [ ] EXPERINECES, a date-time STUDENTS experience an LEARNING-ITEMS
- [ ] ASSESSMENTS, a date-time & 0-100 score when STUDENTS see ASSESSMENT-ITEMS
- [ ] ASSESSMENT-ITEMS reveal 1 side of a LEARNING-ITEMS, requesting others
- [ ] CLASSES, Students with LEARNING-ITEMS in common
- [ ] MODULES, external apps with access to native functions and data
- [ ] COINS, points associated with STUDENTS and their EXPERIENCES and ASSESSMENTS

it can ...
- [ ] authenticate Students via password
- [ ] expose native functions via gRPC
- [ ] transfer COINS between STUDENTS
- [ ] credit STUDENTS with COINS
