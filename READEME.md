*1*. **Install promtool and set up the environment:**

`docker pull ishario/promtool:1.0.0`

`docker run --rm -it ishario/promtool:1.0.0 bash`


*2*. **Then test if the CLI is correctly installed with:**

`promtool --version`

*3*. **Expected result:**

**Check syntax errors:** `promtool check rules alerts.yml`

    Checking alerts.yml
    SUCCESS: 2 rules found

**Run the unit test:** `promtool test rules test.yml`

    Unit Testing:  test.yml
    SUCCESS