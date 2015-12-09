# EJ4TR
The Enhanced JUnit 4 Test Runner is part of the RySource suite of solutions designed to simplify and
enhance the testing and quality assurance of software development. It gives the test developer the
tools to better align with AGILE practices amongst adding more metadata and verbosity to their
existing framework without sacrificing the standardised approach in which Junit 4 is deployed.

<h2>How it works?</h2>
The EJ4TR extends the existing Suite class to provide the same setup and configuration process of a
traditional JUnit 4 implementation. When enabled with the @RunWith annotation, the end
developer can configure and retrieve callbacks on events by using the provided annotations or
interfaces as described in the JavaDoc or Getting Started section of the official documentation.

<h3>Report Styles Support</h3>
- Excel Style (In Beta)
- JUnit XML (Currently in Development)

<h3>Callbacks</h3>
<i>Implemented using the EnhancedTestInterface</i>
- onTestFailure (Fired upon a test failing an assertion)
- onTestFinished (Fired upon a test finishing)
- onTestIgnored (Fired when a test is ignored using the @Ignore annotation)
- onTestPassed (Fired when a test finishes without hitting any false assertions)
- onTestStarted (Fired when a test starts executing)

<h3>Getting Started</h3>
Please follow the official startup documentation included in this repository.

<h3>Comments or Suggestions?</h3>
Please contact me on ryandixon1993@gmail.com

<hr />

<h3>Screenshots</h3>
<i>Excel Reports</i><br />
<a href='http://postimg.org/image/lh5rwnj4x/' target='_blank'><img src='http://s24.postimg.org/lh5rwnj4x/Untitled.jpg' border='0' alt="Untitled" /></a>
<a href='http://postimg.org/image/6jxavn5wh/' target='_blank'><img src='http://s24.postimg.org/6jxavn5wh/Untitled1.jpg' border='0' alt="Untitled1" /></a>