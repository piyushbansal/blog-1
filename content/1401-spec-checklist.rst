


* Form fields and validation

  Although form fields can easily be shown as to which ones are required
  (usually with a star), the more in-depth validation is often missing from
  flats. Also, in my experience designers often layout the successful routes
  that users will have, often error messages and pages are not included.

  * What are the formats? Email address, postal code, name (lengths)?
  * What characters should be allowed, which ones should be blocked?
  * Whare are the error messages? Do they differ for missing vs erroneous data?
    Where will they be presented to the visitor.

  For example, in a sign up form that might need a name and email address:

    * What are the requirements for email address? Yes it should look like
      person@example.com, but should the server do the backend checks to ensure
      that the server at example.com will receive email, or that even
      example.com exists?
    * What about name fields - what are the requirements regarding length and
      formatting? Are there any forbidden characters?
    * What will the error messages be when each of these fields fails
      validation? Are there different messages for each type of failure?
