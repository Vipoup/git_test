The seven rules of a great Git commit message:
1. Separate subject from body with a blank line
2. Limit the subject line to 50 characters
3. Capitalize the subject line
4. Do not end the subject line with a period
5. Use the imperative mood in the subject line
6. Wrap the body at 72 characters
7. Use the body to explain what and why vs. how


A properly formed Git commit subject line should always be able to complete the following sentence:
    If applied, this commit will __your subject line here__

For example:
    If applied, this commit will __refactor subsystem X for readability__
    If applied, this commit will __update getting started documentation__
    If applied, this commit will __remove deprecated methods__
    If applied, this commit will __release version 1.0.0__
    If applied, this commit will __merge pull request #123 from user/branch__

Notice how this doesn’t work for the other non-imperative forms:
    If applied, this commit will ~~fixed bug with Y~~
    If applied, this commit will ~~changing behavior of X~~
    If applied, this commit will ~~more fixes for broken stuff~~
    If applied, this commit will ~~sweet new API methods~~