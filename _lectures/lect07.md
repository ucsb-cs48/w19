---
num: lect07
desc: "Deployment Tips"
lecture_date: 2019-02-04
ready: true
---

# Clarification on the MVP column, tags, etc.

* Q: If we are working on an issue from MVP column, should we drag into in-progress?
* A: Yes.  We'll know its part of MVP because you tagged it with MVP

# Unit Testing, Integration Testing, Test Coverage

* Demo of Flask Tutorials Test Coverage report
    * <http://flask.pocoo.org/docs/1.0/tutorial/tests/>
* Test coverage for node.js: <https://mochajs.org/> Plus <https://istanbul.js.org/>
* Test coverage for Unity/C#: 
   * <https://newhorizongame.wordpress.com/>
   * <http://gamasutra.com/blogs/LiorTal/20140520/218123/Introduction_to_Unity_Test_Tools.php>
* Testing in React/Expo
   * <https://blog.expo.io/testing-expo-apps-with-detox-and-react-native-testing-library-7fbdbb82ac87>


# Web App Folks

Be careful about your database choice.

If you are planning to deploy to Heroku:

* Avoid tutorials based on `sqlite3`
* Instead, find tutorials based on `postgres` (`psycopg2`)
* Better yet, use a library at a higher layer of abstraction
   * `SQLAlchemy`, `alembic`, etc.
* Avoid low level SQL:
   * There are little "gotchas" with SQL dialects
   * SQL is portable in principle, but not in practice!
   * Examples: `AUTOINCREMENT` vs. `SERIAL`, `user` being a keyword, etc. 
   
Of course, you are also free to deploy on another platform.  
* In general, there's no free lunch; you have to choose which battle to fight.

