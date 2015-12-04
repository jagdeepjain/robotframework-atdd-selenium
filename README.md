# robotframework-atdd-selenium
Sample project demonstrating how to do Acceptance Test Driven Development using robot-framework and selenium

# install
install selenium using `pip install robotframework-selenium2library`

# follow BDD using Gherkin
Use Given, When and Then key words to write tests
Have Keywords folder containing all common expression in Given, When and Then present under each Scenario's.

# running tests
C:\robotframework-atdd-selenium>pybot tests/google-search.txt

# report
`==============================================================================`

`Google-Search :: Test google search with specific word`

`==============================================================================`

`Scenario: Search specific word in google search engine                | PASS |`

`------------------------------------------------------------------------------`

`Google-Search :: Test google search with specific word                | PASS |`

`1 critical test, 1 passed, 0 failed`

`1 test total, 1 passed, 0 failed`

`==============================================================================`

`Output:  C:\robotframework-atdd-selenium\output.xml`

`Log:     C:\robotframework-atdd-selenium\log.html`

`Report:  C:\robotframework-atdd-selenium\report.html`

It has:
* `log.html` containing all the details of each test step.
* `report.html` containing graphical report with good color notations
* `output.xml` provides test results in `XML` format