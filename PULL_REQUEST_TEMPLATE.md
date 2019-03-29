#### What's this PR do?
- Allows a customer to update their case

#### Where should the reviewer start?
spec/features/update_case_spec.rb

#### How should this be manually tested?
Look up a valid case and update the shipping status
(Use a test dealer, rather than a real dealer to avoid annoying our customers)

#### Any background context you want to provide?
We consider it sufficiently secure to allow someone with the case number to update the case

#### What are the relevant tickets?

Tracker [#156547283](https://www.pivotaltracker.com/story/show/156547283)

#### Screenshots (if appropriate)


#### Definition of Done:
- [ ] Is there appropriate rspec coverage?
- [ ] Has [wiki](https://github.com/RadialDevGroup/inada-order-access/wiki) been updated to reflect any changes to data structures or specifications
- ~~Does this PR have any migrations?~~
- ~~Does this PR require a Selenium test? (e.g. Browser-specific bugs or complicated UI bugs)~~
- ~~If this feature updates dependencies, has the README been updated?~~
- ~~If this will require new infrastructure, has the appropriate party been notified~~
- ~~If this will require changes to the Salesforce schema, has the appropriate party been notified?~~
- ~~Have you made the appropriate modifications to CI (cicleci.yml)?~~
