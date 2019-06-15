# Hero Guards

For those working in the Common Data Service, it is common to have a "hero" record which is a curated example shown in demonstrations. Hero Guards may be associated with these key records to protect them from accidental or malicious deletion.

Unintended deletion of a hero record is aggravating and is unfortunately common in demo envirnometns where the demo persona often has an "administrator" security role in order to demonstrate a wide variety of capabilities.

There is not an out of the box way to do this, however it is possible to accomplish with a no-code, configuration-based solution. **Hero Guards** standardizes this solution and enables quick and easy deployment of this protection.

## Usage

This solution is intended for use with the Common Data Service in an environment containing Sales and Service entities from the Common Data Model (dependencies on Lead, Opportunity, and Case entities).

### Installation:

1) Install the managed solution file in your Dynamics 365 instance
2) Assign the *Hero Protector* Security Role to any user who will create/remove hero Guards
3) Open the Hero Guard model-driven PowerApp from the app selector

### Assign a Guard to a record:

1) Select **"New Guard**
2) Assocaite with at least one record and choose **Save**.

### Remove a Guard:

1) Open an existing Guard record
2) Choose **Delete** from the action menu

## Contribute

All feedback and suggestions are welcome!
