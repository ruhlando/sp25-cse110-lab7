### Name: Fabio Ruhland

### Check your Understanding
 1) Where would you fit your automated tests in your Recipe project development pipeline? Select one of the following and explain why.
    1) Within a Github action that runs whenever code is pushed 
    2) Manually run them locally before pushing code
    3) Run them all after all development is completed </br>

    1 is the correct answer becuse:
       - Immediate feedback: Running tests on every push ensures that any broken behavior is caught as soon as new code is introduced
       - Scalability: As test suite grows, a GitHub Action can parallelize and manage them without manual intervention

 2) Would you use an end to end test to check if a function is returning the correct output? (yes/no) </br>
   No — use a unit test to verify a function’s return value. E2E tests are for emulating user flows, not checking individual functions.

 3) What is the difference between navigation and snapshot mode?
   - Navigation mode runs the audit right after the page loads, measuring load performance (e.g. how fast content paints, time to interactive)
   - Snapshot mode captures the page in its current state and checks things like accessibility and best-practices in that static view, but it doesn’t measure load timing or JS performance.

 4) Name three things we could do to improve the CSE 110 shop site based on the Lighthouse results
    1) optimize images (compress or resize)
    2) improve accessibility (`<html>` element does not have a [lang] attribute)
    3) SEO -> Dcoument does not have a meta description
   





