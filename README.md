Unoffical documentation of FamilySearch extensions to [GEDCOM X](http://www.gedcomx.org/).

The are no official docs so we have to piece together the spec based
on the canonical [Java implementation](https://github.com/FamilySearch/gedcomx-java/tree/master/extensions/familysearch/familysearch-api-model/src/main/java/org/familysearch/platform).
We can also use the [FamilySearch developer docs](https://familysearch.org/developers/docs/api/fs_json)
but the docs mix the FamilySearch extensions with the core GEDCOM X data model.
Thus we use the Java code to obtain a list of extensions and optionally use the
developer docs for a more consumable explanation of the extensions.

## Data Types

* ArtifactMetadata
* ChangeInfo
* ChildAndParentsRelationship
* Comment
* Discussion
* DiscussionReference
* Error
* FamilySearch
* FeatureSet
* FeedbackInfo
* MatchInfo
* Merge
* MergeAnalysis
* MergeConflict
* Ordinance
* Reservation
* SearchInfo
* Tag
* User
* UserHistoryInfo

## Property Extensions

* SourceReference.tags
* Gedcomx
  * childAndParentsRelationships
  * discussions
  * users
  * merges
  * mergeAnalyses
  * features
* AtomEntry.changeInfo

## Enumerations

* changeObjectModifier
* changeObjectType
* changeOperation
* matchStatus
* ordinanceStatus
* familySearchFactType
